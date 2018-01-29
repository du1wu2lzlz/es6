# es6-lessons

最简单的ES6学习环境，请使用 *最新* Chrome 浏览器，最差也要使用 360安全浏览器9.1以上版本（它的webkit内核是55）


### 如何使用

1. **下载**

2. **安装**

	- Windows

	  如果安装了Git，会有个Gitbash命令行，打开它尽情使用吧

	  ```shell
	  cd es6-lessons
	  npm install
	  npm install webpack webpack-dev-server -g
	  ```

3. **使用**

	a. 在命令行执行

	  ```shell
	  npm start
	  ```

	b. 在浏览器输入 [http://localhost:9000](http://localhost:9000)

	c. 去 index.js 去编写代码吧，浏览器会自动刷新，不要忘了打开Chrome浏览器调试面板看输出。（按F12即可）

	  ```javascript
	  let log=(item)=>{console.log(item)};
	  log('我要学习ES6')
	  ```
	d. 如果在Chrome浏览器的调试面板console中看到 我要学习ES6，恭喜你已经运行成功了。

### 帮助

  想测试任何ES6的语法，直接在index.js写，在Chrome面板调试看结果就好。

