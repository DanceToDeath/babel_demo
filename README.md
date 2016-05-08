### 安装babel到全局
```
	npm install babel-cli -g
```
### 编译文件
```
	babel index.js --out-file 1.js
```
3.配置命令在 script的节点中加上"build":"./node_modules/.bin/babel --out-dir build" 之后可以直接执行npm run build
4.新建.babelrc文件中写入:
```
{
	"presets":["es2015","react"]
}
```
5.安装预设  npm install babel-presets-es2015 --save


