# 应用列表

**ActorCloud** 提供设备管理 [REST API](/rest/rest.md) 接口。

进入 **应用管理->应用列表** 页面，点击**新建**新建一个 API 凭证，通过**应用 ID **与**应用密钥**调用平台 API。

![app_details](_assets/app_details.png)


### 注意事项

- 应用必须通过应用角色分配权限，新建应用需关联相关角色；

- 应用必须指定分组权限，通过应用调用 REST API 接口在角色权限内只可管理其分组下的设备等相关资源。


> **应用密钥**可在**应用**详情页查看，请妥善保管应用信息，并及时销毁过期密钥。



# 应用角色

应用必须通过应用角色分配权限，新建应用需关联相关角色。**ActorCloud** 默认提供三种级别角色：

- 设备管理：支持查看、新建、编辑、删除、控制设备，不具有产品，分组，日志，证书管理权限；

- 数据展示：仅能查看设备、产品、分组、证书、日志等信息；

- 超级应用：能调用平台提供的所有API。

默认角色不允许修改，需要更细微的角色控制可以进行新建手动选取。

![app_roles](_assets/app_roles.png)