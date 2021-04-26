# Shell
## 循环字符串
### 方法1
arr=("0" "1" "2" "3" "4" "5" "6" "7" "8" "9" "a" "b" "c" "e" "e" "f")

for value in ${arr[@]}
do
echo $value
done
### 方法2
for (( i = 0 ; i < ${#arr[@]} ; i++ ))
do
echo ${arr[$i]}
done
