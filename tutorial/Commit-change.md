## GitHub 详细使用教程
不熟悉 GitHub 的同学可参考 GitHub官方的 [GitHub 使用帮助](https://help.github.com/en/articles/incorporating-feedback-in-your-pull-request)。

## 如何修改 Pull Request 的简易教程
PR经审核后可由翻译者整合意见并定稿，现推荐以下两种方法修改初稿。

**注：以下方法只适用于翻译者本人或者 Collaborator。其他人只能提供修改意见，但没有权限直接修改稿件。**

### 方法一：直接编辑文件
1. 在对应的PR里找到“Files Changed”
![File Chnage](resources/0.png)

2. 如图所示，点击文件右侧弹出菜单，选择“Edit file”
![edit file](resources/1-1.png)

3. 在编辑页面进行修改，完成后，拉到页面最下方，选择第一个选项。
![first option](resources/1-2.png)

### 方法二：使用 `commit change` 功能修改翻译稿
1. 在对应的PR里找到“File Changed”，审阅意见会直接显示在页面
![file change](resources/0.png)

2. 选择“commit suggestion”或“add suggestion to batch”
![apply change](resources/2-1.png)
  
   * “commit suggestion”会直接按审阅意见修改文件，每个被接受审阅意见都会更新当前文件版本一次。再次点击“commit changes”以完成修改
   ![commit change](resources/2-2-1.png)
  
   * “add suggestion to batch”可以将多个suggestions整合成一个文件并只会更新当前文件版本一次。按如图所示点击“commit changes”以完成修改
   ![add to batch](resources/2-2-2.png)

## 反馈

对该流程有任何疑问欢迎在[微信群](/docs/wechat.md)或者 [issue](/../../issues) 里留言。
