# jxqh_1
小程序docs

存放文档以及设计图

designs/drafts 存放草图

designs/ui 存放设计好的页面

swagger.yml 为接口文件


#### 商家端权限：

—————
- 超级管理员（可添加、删除、查看管理员、操作员，拥有所有权限，即所有公司权限。可添加公司、门店，不把该权限交给公司管理员）
	- 管理员（权限列表—> 店长所有权限加 所有门店、公司的管理，可添加管理员）
		-  店长（权限列表—>员工所有权限加 查询门店业绩、财务报表、营业记录、会员删除、员工管理、日常开支、所有员工预约信息）
		-  员工（权限列表—>取单、挂单、查询员工业绩、会员卡充值、开卡、会员查询和增加、个人预约信息），默认具有员工权限。
		-  自定义（权限列表—>自定义）		注：管理员只能设置自己已有权限


	- 操作员（为管理员添加公司、门店以及其他操作）

根据权限列表返回菜单—> menu

—————
用户端完全独立，不设置权限。

