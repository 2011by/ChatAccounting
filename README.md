#  ChatAccounting


## 1. 功能

### 1.1 聊天功能

聊天功能发送消息在左气泡显示出来，上传到后端，后端连接到青云客api，返回数据到左气泡，左下角有跳转到记账页面的按钮，记账完成后会返回数据显示到右气泡。

### 1.2 记账功能

记账模块为本程序核心模块之一。记账时，用户将输入消费条目、选择消费类型并输入消费金额，随后客户端会将记账数据提交至服务器，服务器进行入库处理，并返回处理结果与回复消息。客户端接受到消息后，返回到来哦天界面，并将几张信息与回复消息以消息对话的形式展现给用户。

### 1.3 账单查询功能

账单查询分为了两个部分：账单消费列表、账单统计。账单消费列表完成用户点击进入账单页面就能够看到最近的消费记录；账单统计完成用户在消费列表页面点击统计进入账单统计页面，点击月份，选择月份，显示本月消费总金额以及每个分类的金额。

### 1.4 偏好设置功能

在偏好设置中，用户可以选择机器人性格特征。在对记账信息进行回复时，系统会由用户的选择确定在语料列表中的随机范围。

