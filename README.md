### ��װbabel��ȫ��
```
	npm install babel-cli -g
```
### �����ļ�
```
	babel index.js --out-file 1.js
```
3.���������� script�Ľڵ��м���"build":"./node_modules/.bin/babel --out-dir build" ֮�����ֱ��ִ��npm run build
4.�½�.babelrc�ļ���д��:
```
{
	"presets":["es2015","react"]
}
```
5.��װԤ��  npm install babel-presets-es2015 --save


