
# 项目部署工具Capistrano

[Capostrano搭建](https://github.com/users/torow/projects/4#card-19891051)
	
## 部署命令

	## 正式环境
	cap production deploy

	## 测试环境
	cap staging deploy

## 版本回滚
	
	cap production/staging deploy:rollback

## 新增部署
	例如：在deploy文件下添加dev.rb, 配置好 cap dev deploy