# Web辅助功能入门编写技巧
#### 摘要
本页介绍了一些基本注意事项，可帮助您开始编写残障人士更容易访问的Web内容。这些提示是帮助您满足Web内容可访问性指南（WCAG）要求的良好实践。请点击相关WCAG要求的链接，“理解”文档中的详细背景，教程指南，用户故事等。
#### 页面内容
* <a href="#提供信息丰富，独特的页面标题">提供信息丰富，独特的页面标题</a>
* <a href="#使用标题来表达意义和结构">使用标题来表达意义和结构</a>
* <a href="#使链接文本有意义">使链接文本有意义</a>
* <a href="#为图像编写有意义的文本">为图像编写有意义的文本</a>
* <a href="#为多媒体创建文字记录和字幕">为多媒体创建文字记录和字幕</a>
* <a href="#提供明确的说明">提供明确的说明</a>
* <a href="#保持内容清晰简洁">保持内容清晰简洁</a>

### 提供信息丰富，独特的页面标题
对于每个网页，提供描述页面内容的简短标题，并将其与其他页面区分开来。页面标题通常与页面的主标题相同。首先提供独特和最相关的信息; 例如，将页面名称放在组织名称之前。对于属于多步骤过程的页面，请在页面标题中包含当前步骤。
##### 示例：页面标题
###### 主页标题
示例：使用标题来组织内容
- [x] Space Teddy Inc.
###### 页面名称后跟组织名称
- [x] Latest News • Space Teddy Inc.
###### 页面名称包括进程中的步骤
- [x] Buy Your Bear (Step 1 of 3) • Space Teddy Inc.
##### 更多信息
* WCAG
[页面标题为2.4.2](https://www.w3.org/WAI/WCAG21/quickref/#page-titled)[（了解2.4.2）](https://www.w3.org/WAI/WCAG21/Understanding/page-titled)
### 使用标题来表达意义和结构
使用简短标题对相关段落进行分组，并清楚地描述各个部分。好的标题提供了内容的概述。
##### 示例：使用标题来组织内容
###### × 缺乏标题
![image](https://www.w3.org/WAI/tips/img/headings-poor.png)
###### [查看内联示例]
###### 标题和副标题
HTML元素提供有关文档结构层次结构的信息。正确使用元素将有助于传达辅助技术的其他意义。在许多情况下，这样做也会使您的文档更容易编辑。

对于长度超过三或四段的文档，标题和副标题对于可用性和可访问性非常重要。它们帮助读者确定文档的整体轮廓并导航到感兴趣的特定信息。

标题分为1到6个等级。最高级别是“级别1”，通常对应于页面或主要文档部分的标题。子标题通过增加标题级别来继续。数字越小，部分越小，越详细。

可视阅读器通过扫描页面来查找更大尺寸或不同样式的文本来识别标题。辅助技术用户无法看到这些视觉变化，因此改变风格并不是一个充分的线索。

相反，标题必须在语义上“标记”，以便辅助技术可以识别标题。这可以作为导航辅助提供给用户。

这使得添加标题成为屏幕阅读器用户最重要的工具之一，以便他或她可以了解页面上的内容。请注意，标记通常会直观地触发格式更改，可以在许多文档中进行调整。

改编自宾夕法尼亚州立大学的标题和副标题
- [x] 使用标题和副标题
- ![image](https://www.w3.org/WAI/tips/img/headings-good.png)
#####  查看内联示例
##### 标题和副标题
HTML元素提供有关文档结构层次结构的信息。正确使用元素将有助于传达辅助技术的其他意义。在许多情况下，这样做也会使您的文档更容易编辑。

###### 标题的用途
对于长度超过三或四段的文档，标题和副标题对于可用性和可访问性非常重要。它们帮助读者确定文档的整体轮廓并导航到感兴趣的特定信息。

标题级别
标题分为1到6个等级。最高级别是“级别1”，通常对应于页面或主要文档部分的标题。子标题通过增加标题级别来继续。数字越小，部分越小，越详细。

###### 含义与格式
可视阅读器通过扫描页面来查找更大尺寸或不同样式的文本来识别标题。辅助技术用户无法看到这些视觉变化，因此改变风格并不是一个充分的线索。

相反，标题必须在语义上“标记”，以便辅助技术可以识别标题。这可以作为导航辅助提供给用户。

这使得添加标题成为屏幕阅读器用户最重要的工具之一，以便他或她可以了解页面上的内容。请注意，标记通常会直观地触发格式更改，可以在许多文档中进行调整。

改编自宾夕法尼亚州立大学的标题和副标题
#### 更多信息
* WCAG
###### [标题和标签2.4.6](https://www.w3.org/WAI/WCAG21/quickref/#headings-and-labels/)[（理解2.4.6）](https://www.w3.org/WAI/WCAG21/Understanding/headings-and-labels)
###### [章节标题2.4.10](https://www.w3.org/WAI/WCAG21/quickref/#section-headings)[（理解2.4.10）](https://www.w3.org/WAI/WCAG21/Understanding/section-headings)
###### [信息和关系1.3.1](https://www.w3.org/WAI/WCAG21/quickref/#info-and-relationships)[（理解1.3.1)](https://www.w3.org/WAI/WCAG21/Understanding/info-and-relationships)
* 用户故事[屏幕阅读器用户如何使用标题进行导航](https://www.w3.org/WAI/people-use-web/user-stories/#accountant)
### 使链接文本有意义
编写链接文本，以便描述链接目标的内容。避免使用含糊不清的链接文本，例如“点击此处”或“阅读更多”。指示有关链接目标的相关信息，例如文档类型和大小，例如“提案文档（RTF，20MB）”。
##### 示例：使用链接文本描述目标页面
###### × 无信息
有关设备独立性的更多信息，[请单击此处。](javascript:return false)
###### √ 有意义的信息
[详细了解设备独立性。](javascript: return false)
#### 更多信息
* WCAG
###### [链接目的（在上下文中）2.4.4](https://www.w3.org/WAI/WCAG21/quickref/#link-purpose-in-context)[（理解2.4.4）](https://www.w3.org/WAI/WCAG21/Understanding/link-purpose-in-context)
###### [链接目的（仅限链接）2.4.9](https://www.w3.org/WAI/WCAG21/quickref/#link-purpose-link-only)[（了解2.4.9）](https://www.w3.org/WAI/WCAG21/Understanding/link-purpose-link-only)  
### 为图像编写有意义的文本  
对于每个图像，编写能替代图片所提供的信息或功能的文本。对于纯粹的装饰性图像，不需要编写替代文本。  
##### 实例：用替代文本来传达重要的信息  
###### × 不提供信息的  
![image](https://www.w3.org/WAI/tips/img/phone_charging.png)  
为手机充电：使用提供的充电线和电源适配器将手机连接到电源插座。  
**替代图片的文字**  ：充电电话

###### √ 信息丰富的
![image](https://www.w3.org/WAI/tips/img/phone_charging.png)  
充电:使用提供的充电线和电源适配器将手机连接到电源插座。  
**替代图片的文字**：“将充电线插入手机的底部边缘。”  

*替代文本通常不明显；它出现例子里，以便您可以看到它是什么。*  
#### 更多信息  
* WCAG  
  ###### [非文本内容1.1.1](https://www.w3.org/WAI/WCAG21/quickref/#non-text-content)[（知识1.1.1）](https://www.w3.org/WAI/WCAG21/Understanding/non-text-content)  
* 教程
  ###### [图片](https://www.w3.org/WAI/tutorials/images/)  
* 用户故事  
  ###### [阐述盲人用户的文本替代方案的价值](https://www.w3.org/WAI/people-use-web/user-stories/#accountant)  
### 为多媒体创建文字记录和字幕  
对于只有音频的内容，如播客，提供一份文本。对于音频和视频内容，如培训视频，也提供说明。在笔录和字幕中包含对理解内容很重要的语音信息和声音，例如“门吱吱”。对于视频记录，还包括对重要视觉内容的描述，例如“Athan 离开房间”。  
#### 更多信息  
* WCAG  
  ###### [标题(预先录制的)1.2.2](https://www.w3.org/WAI/WCAG21/quickref/#captions-prerecorded)[（知识1.2.2）](https://www.w3.org/WAI/WCAG21/Understanding/captions-prerecorded)  
  ###### [音频描述或媒体替代(预先录制)1.2.3](https://www.w3.org/WAI/WCAG21/quickref/#audio-description-or-media-alternative-prerecorded)[（知识1.2.3）](https://www.w3.org/WAI/WCAG21/Understanding/audio-description-or-media-alternative-prerecorded)
* 用户故事  
  ###### [阐述字幕如何帮助失聪学生](https://www.w3.org/WAI/people-use-web/user-stories/#onlinestudent)

### 提供明确的说明
确保说明，指导和错误消息清晰，易于理解，并避免使用不必要的技术语言。描述输入要求，例如日期格式。
#### 示例：说明传达用户应提供的信息
密码至少应为六个字符，且至少有一个数字（0-9）。

密码：
#### 示例：错误表示问题是什么，可能还有如何解决问题
1.用户名'superbear'已在使用中
[link](https://note.youdao.com/)

2.密码至少需要包含一个号码。

#### 更多信息
- WCAG
  - [标签或说明3.3.2（了解3.3.2）](https://www.w3.org/WAI/WCAG21/quickref/#labels-or-instructions)
- 用户故事
  - [描述简单的说明可以帮助有学习困难的人](https://www.w3.org/WAI/people-use-web/user-stories/#supermarketassistant)
### 保持内容清晰简洁  
根据上下文使用简单的语言和格式。
- 写一些简短明了的句子和段落。
- 避免使用不必要的复杂单词和短语。考虑为读者可能不知道的术语提供词汇表。
- 首次使用时扩展首字母缩略词。例如，Web内容可访问性指南（WCAG）。
- 考虑为读者可能不知道的术语提供词汇表。
- 根据需要使用列表格式。
- 考虑使用图像，插图，视频，音频和符号来帮助澄清意义。
#####  示例：使内容可读且易于理解
###### ×不必要的复杂
CPP：如果发生车辆碰撞，指定代表的公司将寻求确定属于所有相关方财产的损害程度和原因。一旦我们的代表获得允许我们理解因果关系的信息，我们可能会或可能不会分配适当的货币补偿。由此产生的决定可能会出现以下选项之一：索赔未获批准并被指定为拒绝状态，索赔状态不明确，并且在进一步处理之前需要其他信息，索赔部分批准并减少付款是已分配和签发，或索赔已完全批准，并且已分配和发放索赔总额。
###### √ 更容易理解
索赔处理程序（CPP）：如果您发生车祸，我们的代理人将进行调查。调查结果将确定任何索赔付款。这可能导致：
- 批准的索赔 - 全额付款
- 部分批准的索赔 - 减少付款
- 未确定的声明 - 需要更多信息
- 被拒绝的索赔 - 没有付款
![image](https://www.w3.org/WAI/tips/img/clear_text_diagram.png)
#### 更多信息
- WCAG
  - [阅读水平3.1.5（理解3.1.5）](https://www.w3.org/WAI/WCAG21/Understanding/reading-level)
  - [不寻常的话3.1.3（理解3.1.3）](https://www.w3.org/WAI/WCAG21/Understanding/unusual-words)
  - [缩写3.1.4（理解3.1.4）](https://www.w3.org/WAI/WCAG21/Understanding/abbreviations)
- 用户故事
  - [阅读障碍的用户可以从易于阅读的文本中受益](https://www.w3.org/WAI/people-use-web/user-stories/#classroomstudent)
 ###  详细了解辅助功能
这些提示是您可以考虑用于Web可访问性的一些事项。以下资源可帮助您了解可访问性的重要性，以及有关使残疾人更方便网络访问的指南。
- [辅助功能简介 ](https://www.w3.org/WAI/fundamentals/accessibility-intro/)-介绍辅助功能并提供许多有用资源的链接
- [可访问性原则](https://www.w3.org/WAI/fundamentals/accessibility-intro/)- WCAG要求简介
- [残疾人如何使用网络 ](https://www.w3.org/WAI/people-use-web/)- 现实生活中的例子显示残疾人无障碍的重要性
- [如何满足WCAG（快速参考)](https://www.w3.org/WAI/WCAG21/quickref/) - 所有WCAG要求和技术的可定制参考
### 帮助改进此页面
请通过电子邮件将您的想法，建议或意见分享到公开存档的列表wai-eo-editors@w3.org或通过GitHub。
[电子邮件]()

[分叉和编辑GitHub]()

[新GitHub问题]()
