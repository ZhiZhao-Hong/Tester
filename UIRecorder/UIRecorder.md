# UIRecorder #
## 环境配置 ##
1. install Node.js（version>=v7.x）
	> https://nodejs.org/en/
2. install chrome
	> https://www.google.com/chrome/
3. install UI Recorder
	> `npm install uirecorder mocha -g`

## 项目运行 ##
### windows下运行 ###
1. 初始化测试项目(init test project)
	> 创建测试文件夹<br> 
	> cmd下输入 : `uircorder init`
2. 开始记录测试用例
	> 编辑hosts文件<br>
	> `uirecorder sample/test.spec.js`
3. 开启webdriver server
4. 运行测试用例
	> 运行所有的测试用例 `run.bat`
	> 运行单个测试用例 `run.bat sample/test.spec.js
5. 获取报告和截图
	> ./reports/index.html <br>
	> ./reports/index.xml(Junit) <br>
	> ./reports/index.json <br>
	> ./screenshots 