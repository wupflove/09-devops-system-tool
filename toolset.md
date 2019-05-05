# 研发运营一体化（DevOps）能力成熟度模型 第9部分：系统和工具

研发运营一体化（DevOps）能力成熟度模型 第9部分：系统和工具（DevOps 产品标准）属于研发运营一体化（DevOps）能力成熟度模型系列标准的一部分，旨在通过行业的力量，规范化DevOps产品的功能特性，帮助企业建设、选型和购买DevOps产品工具。

本标准由DevOps标准工作组下DevOps产品工作小组负责编写和维护。

### 工具箱列表

#### 1. [项目与开发管理](project_and_development_management.md)


| 项目管理              | 工作项管理              | 计划管理      | 文档与知识管理              | 团队协同            | 统计度量              | 项目集管理             |
| --------------------- | --------------------------- | --------------------- | --------------------------- | ------------------- | --------------------- | --------------------- |
|            |              | JIRA                  | Confluence                  | Slack               | Hygieia (国外/开源)                | Portfolio for Jira |
|                |                  | 华为DevCloud:项目管理 | 华为DevCloud:Wiki和文档管理 | 华为DevCloud:HiChat | MirrorGate            | 华为DevCloud:项目管理  |
|  |        | 阿里云效:项目协作     | ONES Project                | Mattermost          | 华为DevCloud:项目管理 | 阿里云效:项目协作      |
|      |            | ONES Project          | SharePoint |                     | CloudBees DevOptics   | Oracel Primavera       |
|           |                 | MS Project            |                             |                     | JIRA EasyBI           |                        |
|                       |  |                       |                             |                     |                       |                        |

#### 2. [持续交付](continuous_delivery.md)

| 版本控制系统          | 构建与持续集成                    | 制品管理          | 部署管理            | 发布管理             | 环境管理                | 应用配置管理 | 数据管理     |         流水线          |
| --------------------- | --------------------------------- | ----------------- | ------------------- | -------------------- | ----------------------- | ------------ | ------------ | :---------------------: |
| Gitlab:代码管理       | Maven                             | Nexus             | Ansible             | AWS CodePipeline     | Ansible                 | 携程Apollo   | Flyway       |         Jenkins         |
| Github                | EA                                | Artifactory       | Xebialabs XL Deploy | Spinnaker            | 华为DevCloud:部署       | 百度Disconf  | 蓝鲸数据平台 |   华为DevCloud:流水线   |
| 阿里云效:代码托管     | 华为DevCloud:编译构建、流水线     | Harbor            | 华为DevCloud:部署   | 华为DevCloud:发布    | 蓝鲸DevOps平台:环境管理 | 阿里云:ACM   |              |    阿里云效:持续交付    |
| 腾讯工蜂              | 蓝鲸DevOps平台:编译构建、持续集成 | 阿里云效:制品仓库 | 阿里云效:持续交付   | 阿里云效:持续交付    |                         | 蓝鲸配置平台 |              |     EasyOps:流水线      |
| 华为DevCloud:代码托管 | 阿里云效:持续交付                 | 华为DevCloud发布  | EasyOps:持续部署    | EasyOps:发布         |                         |              |              |  蓝鲸DevOps平台:流水线  |
|                       | Jenkins                           |                   | 蓝鲸作业平台        | 蓝鲸SaaS（标准运维） |                         |              |              | 蓝鲸DevOps平台:持续集成 |
|                       | Travis CI                         |                   |                     |                      |                         |              |              |                         |
|                       | Bamboo                            |                   |                     |                      |                         |              |              |                         |

#### 3. [测试管理](test_management.md)

| 用例与测试计划管理 | 测试数据管理                   |
| ------------------ | ------------------------------ |
| TestLink           | 华为DevCloud云测               |
| HP Quality Center  | 亚信智测云AiTC                 |
| 华为DevCloud:云测  | Alauda Cloud Enterprise（ACE） |
| 阿里云效:持续交付  | 东软UniEAP UTF自动化测试平台   |
| ONES TestCase      |                                |
|                    |                                |

#### 4. [自动化测试](test_automation.md)

| 静态代码检查          | 单元测试 | 接口/服务测试     | UI测试            | 移动应用测试              | 性能测试          |
| --------------------- | -------- | ----------------- | ----------------- | ------------------------- | ----------------- |
| SonarQube             | JUnit    | Postman           | RobotFramework    | Appium                    | Jmeter            |
| Coverity              | Xunit    | RESTClient        | Selenium          | 华为DevCloud:移动应用测试 | Locust            |
| Klocwork              | PHPUnit  | SoapUI            | 阿里云效:持续交付 |                           | 华为DevCloud:云测 |
| 华为DevCloud:代码检查 |          | 阿里云效:持续交付 |                   |                           |                   |

#### 5.技术运营（待定）

#### 6. [安全开发](security_development.md) \ [安全交付](security_delivery.md) \ 安全运营

| 安全开发              | 安全交付          | 安全运营 |
| --------------------- | ----------------- | -------- |
| BlackDuck             | Appscan           |          |
| Checkmarx             | Fortify           |          |
| FOSSID                | 华为云:漏洞扫描   |          |
| Fortify SCA           | 阿里云效:持续交付 |          |
| 华为DevCloud:代码检查 |                   |          |

#### 7. [应用设计与开发](application_design_and_development.md)

| 应用框架                 | 集成开发环境                       |
| ------------------------ | ---------------------------------- |
| Dubbo                    | AWS Cloud9                         |
| TARS (国产/开源)         | Eclipse Che                        |
| EDAS                     | Codenvy                            |
| 灵雀云（Alauda EE PaaS） | 华为DevCloud:CloudIDE（国产/商业） |
| 华为云 ServiceStage      | Coding:WebIDE                      |
| EMAS                     | OrionHub                           |
| 谐云（观云台）           |                                    |





#### 