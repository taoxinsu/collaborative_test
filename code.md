***

```
at the web  click the 'fork' button

git clone xxxx

edit some

and now i will submit it
```
***

一个PR应该的格式：
# 一个PR 应该有的格式

## 这个PR做了什么
描述变更的内容

## 为何需要这个变更
说明背景和原因， 刻意算得是title的一种拓展

## 具体的变更
详细描述代码的变化

## 如何测试/ 性能原项目的比较

##  检查清单
是否遵循项目规则

##  相关问题
这个是github 关键字自动关闭功能，当PR被合并时自动关闭对应的issue（还有很多要了解的哦^_^）

一般是一个描述此后接数字

eg:
fix: #xxx(number 如同2233)
## 特别需要阐述的
<strong> 接口或者影响兼容性质的破环性变更 </strong>


# 善用标签：

## 状态标签
 `blocked`        - 被阻塞，等待其他依赖

 `WIP`            - 工作进行中（Work In Progress）

 `ready for review` - 准备审查

 `urgent`         - 紧急

 `tests needed`    - 需要测试

##  类型标签
🛠️  `refactor`       - 代码重构

⚡ `performance`     - 性能优化

🔧 `config`          - 配置变更

🧹 `cleanup`         - 清理代码

🚀 `feature`         - 新功能（enhancement的别名）

## 范围标签
🎨 `UI`              - 用户界面相关

📱 `mobile`          - 移动端相关  

🌐 `i18n`            - 国际化相关

🔒 `security`        - 安全相关

📊 `analytics`       - 数据分析相关


## 协作标签
👀 `needs review`    - 需要审查

💬 `needs discussion` - 需要讨论

📝 `needs docs`      - 需要文档

🐛 `bug`             - Bug修复

❓ `question`         - 问题



<strong> 对于一个pr的再一次提交，不会反复的触发邮件，需要引发作者注意的时候需要重新请求</strong>
