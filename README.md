## 西邮 网络 自动登陆 代码
使用 `curl` 库 和 `base64` 码库,混合 c 和 c++ 完成的小软件,用于自动登陆和维持登陆
状态,适合放在局域网内某一台内,开机自启。

## 使用方法
前提: 安装 curl-dev 库 
1. 设置登陆账号和密码
   修改 final.cpp 中 的 `ID` 和 `KEY`  宏定义
2. 编译
```
   g++ final.cpp base64.cpp -lcurl -o regist
```
3. 运行 
```
  ./regist
```
4. 运行日志 regist_log

## 另附一个使用 `shell` 写的脚本同样可以实现相似的功能
