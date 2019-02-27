### URL Scheme 

--

#### 用法

格式：  

	fpuser://[DBName]/[DBEXT]/entry?title=[xxx]&username=[ooo]
	
* 中括号代表可变参数

* [DBName]: 数据库名称
* [DBEXT]: 数据库后缀，一般为kdbx或者kdb

打开名称为[DBName]和后缀为[DBEXT]的数据库中的title为[xxx]并且username为[ooo]的登录项。

> 为了安全考虑，如果您要使用此功能，请先先在设置中开启开关。

#### 实例

目前用法，您可以用这些URL Scheme结构和参数来打开相应的登录项或者数据库。日后会添加更多的操作，例如复制、执行JS插件等操作。

* 实例
打开keepass.kdbx数据库，并且打开用户名为xiaoming的github登录项。
		
		fpuser://keepass/kdbx/entry?title=github&username=xiaoming