# Theia

A Javascript framework for native desktop and cloud-based IDEs.

## Scope
 - Provide the end-user with a full-fledged multi-language IDE  (not just a smart editor)
 - Support equally the paradigm of Cloud IDE and Desktop IDE
 - Provide extenders with a platform on which to build their own products
 - Provide support for multiple languages via the language and debug serve protocols


0， npm install webpack webpack-dev-server -g
0.1， npm install webpack-cli -g

1, npm install 

如果您的目录中已经有一个package.json文件，并且运行了npm install，那么npm将查看该文件中的dependencies，并下载满足所有这些的最新版本。

2, npm run install          // 上一步執行了，這步不需要執行。
   npm run-script install
   
   執行package.json中的install 命令
 
     "scripts": {
        "install": "npm run install:webapp",

3， npm run build 


4， npm run clean    //刪除webapp/build 文件夾，正如script寫的那樣。


                 無效    5， add script    "start": "cd webapp && webpack-dev-server"
                        npm start 
                        打開瀏覽器， 127.0.0.1:8080