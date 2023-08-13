## 使用 Shell 脚本来处理 JSON
> https://www.tomczhen.com/2017/10/15/parsing-json-with-shell-script/
> https://www.jianshu.com/p/333367027eaa

- 使用 awk sed
- 使用第三方库
- 调用其他脚本解释器
## 使用第三方库处理
cat IpInfo.jso | jq '.data.ip'