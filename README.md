## <center>目录</center>

 - ### 1. 模块清单

     - [<h4 id="module-Risk information base-from">1.1. 风险情报库</h4>](#module-Risk information base "Risk information base")
	- [<h5 id="module-Risk information base-tableList-from">1.1.1. 表清单</h5>](#module-Risk information base-tableList "表清单")
	- [<h5 id="module-Risk information base-tableColumnList-from">1.1.2. 表列清单</h5>](#module-Risk information base-tableColumnList "表列清单")
	     - [<h6 id="module-Risk information base-tableColumnList-collections-from">1.1.2.1 collections【收藏列表】</h6>](#module-Risk information base-tableColumnList-collections "collections")
	     - [<h6 id="module-Risk information base-tableColumnList-monitor_users-from">1.1.2.2 monitor\_users【监控人名字】</h6>](#module-Risk information base-tableColumnList-monitor_users "monitor_users")
	     - [<h6 id="module-Risk information base-tableColumnList-monitor_companys-from">1.1.2.3 monitor\_companys【监控的企业】</h6>](#module-Risk information base-tableColumnList-monitor_companys "monitor_companys")
	     - [<h6 id="module-Risk information base-tableColumnList-messages-from">1.1.3.4 messages【消息】</h6>](#module-Risk information base-tableColumnList-messages "messages")

  ---

### 1. 模块清单
 - [<h4 id="module-Risk information base">1.1. 风险情报库</h4>](#module-Risk information base-from)

 - [<h5 id="module-Risk information base-tableList">1.1.1 表清单</h5>](#module-Risk information base-tableList-from)

 ---

| 名称 | 代码 | 备注 |
| ------------ | ------------ | ------------ |
| 收藏列表 | collections |  |
| 监控人名字 | monitor\_users |  |
| 监控的企业 | monitor\_companys |  |
| 消息 | messages |  |

 ---

 - [<h5 id="module-Risk information base-tableColumnList">1.1.2 表列清单</h5>](#module-Risk information base-tableColumnList-from)

 ---

 - [<h6 id="module-Risk information base-tableColumnList-collections">collections【收藏列表】</h6>](#module-Risk information base-tableColumnList-collections-from)

| 代码 | 名称 | 数据类型(MYSQL) | 主键 | 备注 |
| ------------ | ------------ | ------------ | ------------ | ------------ |
| id | id | BIGINT | √ |  |
| information\_table | 资讯所在表名 | VARCHAR(64) |  |  |
| information\_id | 资讯id | VARCHAR(64) |  |  |
| user\_id | 用户id | BIGINT |  |  |
| create\_time | 创建时间 | DATETIME |  |  |
| update\_time | 更新时间 | DATETIME |  |  |

 ---

 - [<h6 id="module-Risk information base-tableColumnList-monitor_users">monitor_users【监控人名字】</h6>](#module-Risk information base-tableColumnList-monitor_users-from)

| 代码 | 名称 | 数据类型(MYSQL) | 主键 | 备注 |
| ------------ | ------------ | ------------ | ------------ | ------------ |
| id | id | BIGINT | √ |  |
| name | 名字 | VARCHAR(32) |  |  |
| user\_id | 用户id | BIGINT |  |  |
| status | 状态 | INT |  |  |
| create\_time | 创建时间 | DATETIME |  |  |
| update\_time | 更新时间 | DATETIME |  |  |

 ---

 - [<h6 id="module-Risk information base-tableColumnList-monitor_companys">monitor_companys【监控的企业】</h6>](#module-Risk information base-tableColumnList-monitor_companys-from)

| 代码 | 名称 | 数据类型(MYSQL) | 主键 | 备注 |
| ------------ | ------------ | ------------ | ------------ | ------------ |
| id | id | BIGINT | √ |  |
| cid | 公司id | VARCHAR(64) |  |  |
| user\_id | 用户id | BIGINT |  |  |
| status | 状态 | INT |  |  |
| create\_time | 创建时间 | DATETIME |  |  |
| update\_time | 更新时间 | DATETIME |  |  |

 ---

 - [<h6 id="module-Risk information base-tableColumnList-messages">messages【消息】</h6>](#module-Risk information base-tableColumnList-messages-from)

| 代码 | 名称 | 数据类型(MYSQL) | 主键 | 备注 |
| ------------ | ------------ | ------------ | ------------ | ------------ |
| id | id | BIGINT | √ |  |
| information\_db | 资讯所在数据库名 | VARCHAR(64) |  |  |
| information\_table | 资讯所在表名 | VARCHAR(64) |  |  |
| information\_id | 资讯id | VARCHAR(64) |  |  |
| user\_id | 用户id | BIGINT |  |  |
| status | 状态 | INT |  |  |
| create\_time | 创建时间 | DATETIME |  |  |
| update\_time | 更新时间 | DATETIME |  |  |

 ---

