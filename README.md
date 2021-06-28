> 高考结束了，晚上无聊捣鼓的一个插件  
> 自己主要是应对玩家背包数据丢失的问题，玩家可以通过此插件，把书保存在服务端，即使玩家信息丢失，也不会影响到自己的著作  
> [MineBBS](https://www.minebbs.com/resources/1-13-x-1-17-bookedit.2553/)  

---

## 本插件有以下特点：
- **支持**玩家导入√
- **支持**玩家导出√
- **支持**玩家修改√
- **支持**玩家共享√
- **支持**玩家传抄√
- **支持**命令补全√
- **支持**手持成书，然后**抬头+潜行**来快捷编辑√
- 导出的书文件**对浏览、共享和导入开放，对修改关闭**√

---

## 命令介绍：

| 命令 | 选项 | 功能 |
| :-----| :----: | ----: |
| /book | **help** [command] | 来查看帮助​
| /book | **copy-to-writable-book** | 把主手的 成书/书与笔 复制成 书与笔 然后返还给玩家​
| /book | **export-book-to-file** <file> | 把主手的 成书/书与笔 导出书到文件​
| /book | **import-book** <file> | 从文件导入 书与笔​
| /book | **view-book** <file> [player] | 给玩家打开一本成书，若 player 未填写，则为命令发送者​

---

> ## 若腐竹或管理员需要手动编辑书文件，请注意以下事项：
> 1. 书文件采用JSONArray的方式存储，按页划分为N个元素，文件后缀名为.txt，编辑前请学习JSON相关知识
> 2. 书文件最多50页，每页最多256个字符，若超出范围，可能会导致一些问题

---

## 安装方法：丢入服务器plugins文件夹即可

---

## 重要：觉得插件好用的话别忘了给点星星 