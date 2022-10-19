```
#查看全局配置 主要看user.name user.email user.password
git config --list

#移除全局配置账户
git config --global --unset user.name
#查看全局用户名 已经显示为空了，说明移除成功
git config --global user.name
# 移除全局配置邮箱
git config --global --unset user.email
# 再查看全局邮箱 已经显示为空了，说明移除成功
git config --global user.email
# 移除全局密码
git config --global --unset user.password
# 查看全局密码 已经显示为空了，说明移除成功
git config --global user.password

# 设置提交的用户名和邮箱名称。
git config user.name "gs_userName"
git config user.email "gs_userName@email.com"
```
