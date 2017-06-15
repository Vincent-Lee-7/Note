1. mkdir GitTest  (创建文件夹Test）
2. cd GitTest  （切换到GitTest目录）
3. touch a.md  (新建a.md文件）
4. git init  (初始化git仓库）
5. git status  (查看状态）*
6. git add  （提交到缓存，等待被提交）
7. git rm --cached  (移除缓存）
8. git commit -m 'first commit'  (正式提交）
9. git log  (查看所有产生的commit记录）
10. git branch（查看分支）
11. git branch a  （创建a分支）
12. git checkout a  （切换到a分支）
13. git checkout -b a（创建a分支并且切换到a分支）
14. git merge a  （合并分支。。需要在master目录下）
15. git branch -d a(删除分支a）
16. git branch -D a(强制删除分支a）
17. git tag  v1.0  (新建标签v1.0）
18. git checkout v1.0  (切换到v1.0）
19. ssh-keygen -t rsa  (制定rsa算法生成密钥）
20. git push origin master  (本地推送到远程master分支）
21. git pull origin master  （把远程最新代码更新到本地）
22. git clone git@github.com:.....  (把项目从github上克隆下来）
23. git remote add origin git@github.com:....(添加远程仓库）
24. git remote -v  （查看项目有哪些远程仓库）
25. 