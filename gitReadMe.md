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
    git 有三个区域, 分别控制各种情况;

### 工作区
    1. 在修改该文件夹的内容后, 可以输入git status命令, 出现红色的颜色的文件名(用户刚刚修改的文件);
    2. 现在的状态就是工作区;


### 暂存区
    3. 出现红色文件名后可以通过, git add . 或者 git add 该文件名 进行提交至暂存区域
    4. 提交完毕后, 再次查看git status 该文件的名称变成绿色;

### 版本区
    5. 变成绿色后, 可以进行提交至版本区域, 通过 git commit -m 'message' // 提交至版本区域;
    6. 再次查看git status, 发现已经没有任务可以操作的文件;
    7. 可以通过git log 查看提交日志;