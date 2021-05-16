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
## 参数传递
$0 是文件名
$1 是第一个参数
## if语句
### 判断空字符串
if [ -z ${hello} ];then
echo "the variable hello is empty"
if
## exit
exit 0 正常退出
