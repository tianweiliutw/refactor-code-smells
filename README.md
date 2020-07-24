# 重构线上练功房代码坏味道
本项目为ThoughWorks内部【敏捷工程实践系列】之「重构」线上练功房代码块味道练习作业基础代码库


目的：

1. 简化课后练习的基础工作量。

## 开发环境
 - JDK1.8
 - JUnit 5
 - Gradle 5.2.1


## 作业说明

### 见码识味
在`cc.xpbootcamp.code_smell_recognise`package下有编号 `$01 ~ $24`共24种坏味道，每个人阅读这24种坏味道，并识别出他们分别是什么坏味道，并将答案在classroom上提交。提交格式以Markdown的格式案例如下：


| 编号 | 坏味道名称 | 腐烂点 |
|:-------------|:---------------|:-------------|
| $1 | | |
| $2 | Repeated Switches | `case ENGINEER:` |
| $3 | Long Function | `statement()` |
| $4 | | |
| $5 | Loops | `for (int i = 0; i < input.length; i++) {` |
| $6 | Refused Bequest | `layEgg() vs. milk()` |
| $7 | Long Parameter List | `public User(String name, Date birthday, String location, String username, String phoneNumber, String hobbies) {` |
| $8 | Feature Envy | `Application.count++;` |
| $9 | Message Chains | `hotels.stream().flatMap(hotel -> hotel.getRooms().stream())` |
| $10 | Comments | `//        output.append("Date - " + order.getDate();` |
| $11 | Speculative Generality | `HumanAble` |
| $12 | | |
| $13 | Mysterious Name | `String ad; // 地址` |
| $14 | Temporary Field | `private List<ProductBatch> productBatchesToExpired;` |
| $15 | Mutable Data? | `missing code?` |
| $16 | Data Clumps | `this.buyerName = buyerName;` |
| $17 | Middle Man | `public Person getManager(){return department.getManager();}` |
| $18 | Shotgun Surgery | `Printer` |
| $19 | Large Class | `Poker` |
| $20 | Primitive Obsession | `private String getCity(String address) {return address.substring(address.indexOf("省") + 1, address.indexOf("市"));}` |
| $21 | Data Class | `Building, Community, Person, Room` |
| $22 | Insider Trading | `return motorist.getTitle() + " " + motorist.getFirstName() + " " + motorist.getFirstName() + ", " + Integer.toString(getPoints());` |
| $23 | Alternative Classes With Different Interfaces | `checkIp() vs. isValidIp()` |
| $24 | Divergent Change | `toXml() vs toText()` |


#### 作业要求
- 大家将代码库Fork到自己的GitHub账号，依次补全24种坏味道，将表格提交到系统中对应的题目。
