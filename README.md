1. 第一次使用配置：

	git config --global user.name "zh597588308"

	git config --global user.email "zh597588308@sina.com"

	ssh-keygen -t rsa -C "zh597588308@sina.com"

	ssh -T git@github.com

2.下载：
	git pull git@github.com:zh597588308/test.git master

3.上传：

	3.1 下载：
		git init
		git pull git@github.com:zh597588308/test.git master

	3.2 修改提交本地
		git add .
		git commit -m 'localhost test zh597588308'

	3.3 选择路径(只需要一次，第二次不需要)
		git remote add origin git@github.com:zh597588308/test.git
		or
		git remote add origin https://github.com/zh597588308/test.git

	3.4 提交
		git push origin