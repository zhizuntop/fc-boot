拉取项目：
步骤1：找个目录通过命令进入，新建git代码库 执行：# git init
步骤2：克隆项目 执行：




推送项目：

步骤1：拉取项目打开git终端，
执行：git remote add origin https://github.com/zhizuntop/fc-boot.git

步骤2：因为：remote: Support for password authentication was removed on August 13, 2021. Please use a personal access token instead.所以
设置token登录。
执行：git remote set-url origin https://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@github.com/zhizuntop/fc-boot.git/

步骤3：执行推送命令
执行：sudo git push origin master