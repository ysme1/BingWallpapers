# 每日爬取 bing 壁纸
每日爬取 bing 壁纸，存储到 wallpapers 文件夹。
## 运行方式
1. 每天下午 4 点运行 (UTC时间)
2. 监听 .github 文件夹的修改
3. 手动触发工作流程

## 需要自定义的地方
1. 创建 ssh-key 仓库变量，账号放公钥，仓库变量放私钥。
2. "your-email@example.com" 替换为您的 GitHub 邮箱地址
3. "YourGitHubUsername" 替换为您的 GitHub 用户名

# 问题
下载下来的图片，无法按照年月分类转移，只能堆积在 wallpapers 文件夹下。创建年月分类文件夹失效。
