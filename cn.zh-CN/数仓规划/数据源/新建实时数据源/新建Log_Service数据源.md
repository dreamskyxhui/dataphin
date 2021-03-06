---
keyword: Log\_Service数据源
---

# 新建Log\_Service数据源

本文为您介绍如何新建Log\_Service类型的数据源。

-   已获取业务数据库的**Endpoint**。
-   已获取业务数据库的**Project Name**。
-   已获取鉴权的**Access ID**和**Access Key**。

1.  登录[Dataphin控制台](https://dataphin.console.aliyun.com/workingArea)。

2.  在Dataphin控制台页面，选择工作区地域后，单击**进入Dataphin\>\>**。

3.  进入数仓**规划**页面。

    -   在Dataphin首页，单击顶部菜单栏的**规划**。
    -   在Dataphin首页，单击顶部菜单栏下方的**智能数仓规划**。
4.  数仓**规划**页面，单击左侧导航栏的**数据源**。

    ![fagaga](https://static-aliyun-doc.oss-accelerate.aliyuncs.com/assets/img/zh-CN/6278209951/p93923.png)

5.  在**数据源**页面，单击右上方的**新建数据源**。

6.  在**新建数据源**对话框中，填写数据源信息。

    ![faga](https://static-aliyun-doc.oss-accelerate.aliyuncs.com/assets/img/zh-CN/8855209951/p95504.png)

    |参数|描述|
    |--|--|
    |**数据源类型**|选择数据源的类型为**LOG\_SERVICE**。|
    |**数据源名称**|填写数据源名称。数据源名称由汉字、数字、字母、下划线（\_）或短划线（-）组合组成。|
    |**数据源描述**|对数据源的简单描述。|
    |**数据源配置**|选择新建数据源所属的项目：     -   如果您的开发模式是Basic模式，则新建数据源时选择**生产数据源**。
    -   如果您的开发模式是Dev-Prod模式，则可以通过两种方式新建数据源：
        -   单击**生产数据源**，完成生产数据源的配置后，单击**开发数据源**添加开发环境的数据源。

![fagaga](https://static-aliyun-doc.oss-accelerate.aliyuncs.com/assets/img/zh-CN/6278209951/p93912.png)

        -   单击**生产+开发数据源**，完成生产环境和开发环境的数据源创建。 |
    |**Endpoint**|填写连接目标数据源的地址信息。|
    |**Project Name**|填写数据源的项目名称。|
    |**Access ID**|填写连接数据源的Access ID。|
    |**Access Key**|填写连接数据源的Access Key。|

7.  数据源信息填写完成后，单击**测试连接**。

8.  测试成功后，单击**确定**，完成Log\_Service数据源的创建。


