## cnSchema科技知识图谱扩展

### 概念（Class）

#### 专业（Specialty）

* From: http://cnschema.org/Specialty

#### 学者（Scholar）

* URI: http://cnschema.org/Scholar
* superClass: http://cnschema.org/Person
* 说明：在学术领域进行研究工作的人。

#### 科学活动（ScienceEvent）

* URI: http://cnschema.org/ScienceEvent
* superClass: http://cnschema.org/Event
* 说明：科学活动。

#### 学术会议（AcademicConference）

* URI: http://cnschema.org/AcademicConference
* superClass: http://cnschema.org/ScienceEvent
* 说明：学术会议。

#### 学院（Institution）

* URI: http://cnschema.org/Institution
* superClass: http://cnschema.org/Organization
* 说明：学院，研究机构。

### 属性（Property）

#### 缩写（abbreviation）

* URI: http://cnschema.org/abbreviation
* domain: http://cnschema.org/Thing
* range: http://cnschema.org/Text
* 说明：事物的缩写名字。

#### 活跃度值（activity）

* URI: http://cnschema.org/activity
* domain: http://cnschema.org/Scholar
* range: http://cnschema.org/Number
* 说明：学者的活跃度值。

#### H指数（hIndex）

* URI: http://cnschema.org/hIndex
* domain: http://cnschema.org/Scholar
* range: http://cnschema.org/Number
* 说明：学者的H-Index值。

#### 发表论文数（pubNumber）

* URI: http://cnschema.org/pubNumber
* domain: http://cnschema.org/Scholar
* range: http://cnschema.org/Number
* 说明：学者论文的总数。

#### 总引用数（totalCitation）

* URI: http://cnschema.org/totalCitation
* domain: http://cnschema.org/Scholar
* range: http://cnschema.org/Number
* 说明：学者发表论文的总引用数值。

#### 个人简介（bio）

* URI: http://cnschema.org/bio
* domain: http://cnschema.org/Person
* range: http://cnschema.org/Text
* 说明：学者的个人介绍。

#### 个人主页（homepage）

* URI: http://cnschema.org/homepage
* domain: http://cnschema.org/Person
* range: http://cnschema.org/URL
* 说明：学者的个人主页地址。

#### 孩子项目（childItem)

* URI: http://cnschema.org/childItem
* domain: http://cnschema.org/Specialty
* range: http://cnschema.org/Specialty
* 说明：下级项目。

#### 父项目（parentItem)

* URI: http://cnschema.org/parentItem
* domain: http://cnschema.org/Specialty
* range: http://cnschema.org/Specialty
* 说明：上级项目。