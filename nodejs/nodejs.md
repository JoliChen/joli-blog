##快速删除 node_modules
	cd {node_modules parent}
	npm install rimraf -g
	rimraf node_modules

##清除缓存
	npm cache clean
	<!--npm5 之后执行npm cache clean报错-->
	<!--npm5 使用了新的包管理模式，所以在升级之后，要先清空一下本地缓存。-->
	npm cache clean --force