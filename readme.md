#BackCMS

基于 Laravel 的CMS,功能非常简洁.

包含功能
1.单页组件
2.文章组件
3.表单组件.
4.多角色权限
5.系统文件组件

##安装方式
1.下载文件
2.访问 http://xxxxx/ 提示安装
3.安装成功后,会在 /storage/app 生成 installed 文件


##卸载数据
访问 /storage/app 下 installed 文件 ,里面有卸载密码.
访问 http://xxxxx/install/uninstall/卸载密码
卸载成功

如果还有问题...
看下数据库链接
composer dumpautoload
composer update
artisan key:generate

后台模版基于 cockpit ,系统开发 Laravel 5.2 + vue