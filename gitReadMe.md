# git基本使用
 需要在github上创建账号, 需要在本机安装git软件, 并且配置于全局;

### 在本机配置git的基本信息:

    // config userName and userEmail // 查看配置信息;
    git config --global user.name 'llljingsong'
    git config --global user.email '873148577@qq.com'
    git config --list


### 初始化git仓库

    git init // 初始化一个文件夹作为git仓库;

### 查看git仓库状态

    git status // 必须有文件更新的情况下才有数据更新;
# git三个区域

### 工作区
    在修改该文件夹的内容后, 可以输入git status命令, 出现红色的颜色的文件名(用户刚刚修改的文件);
    现在的状态就是工作区;

### 暂存区

### 版本区
