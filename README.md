# xuguang

* A Vue.js project
* 多个项目公用基础的依赖包,在根目录下的node_modules
* 子项目在src中，例如本例中,src下有src项目与test1项目
* 在page.json中，设定执行命令,通过cross-env设置全局变量lzn,变量lzn的命名需要与src下文件名一致。
* 项目依赖，需要在根目录下install i加载公共依赖，也需要在个自的项目中执行install i加载个自的依赖。
* 如果需要同时启动多个项目，需要修改config/index下dev.port的端口号（高版本测vue-cli会自动累加）
* 这样更适合调用公共资源（当然你也可以发布一个本地的npm库），避免多个应用安装相同的依赖包，节省了硬盘空间，噗。。。
* 这只是一个玩具配置，囧，大的生产勿用。


