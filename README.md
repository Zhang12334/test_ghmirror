# test_ghmirror
使用方法：
if curl -fsSL "${custom_proxy}Zhang12334/test_ghmirror/releases/latest/download/test.txt" | grep -q "114514"; then <br>
&emsp;rm -f test.txt <br>
&emsp;验证成功的命令 <br>
else <br>
&emsp;rm -f test.txt <br>
&emsp;验证不成功的命令 <br>
fi <br>
