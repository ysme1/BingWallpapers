# 每日爬取 bing 壁纸
利用 Github 自动流，每日爬取 bing 壁纸，存储到 wallpapers 文件夹。
## 运行方式
1. 每天下午 4 点运行 (UTC时间)
2. 监听 .github 文件夹的修改
3. 手动触发工作流程

## 需要自定义的地方
1. 创建 ssh-key 仓库变量，账号放公钥，仓库变量放私钥。
2. "your-email@example.com" # 替换为您的 GitHub 邮箱地址
3. "YourGitHubUsername" # 替换为您的 GitHub 用户名
4. git push origin main # 假设主分支为 main，请根据实际情况替换为您的主分支名称
# 问题
1. 如果壁纸已经存在，自动流无法正常退出，会报错。
