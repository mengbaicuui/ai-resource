# CLI 命令大全

> 个人 coding 知识库 - 持续更新中

---

## 🐧 Linux/macOS 通用命令（Bash/Zsh）

### 文件操作

| 命令 | 作用 | 示例 |
|------|------|------|
| `ls` | 列出文件 | `ls -la`（显示详情）|
| `cd` | 切换目录 | `cd ~/Desktop` |
| `pwd` | 显示当前路径 | |
| `mkdir` | 创建目录 | `mkdir myproject` |
| `touch` | 创建文件 | `touch index.html` |
| `cp` | 复制文件 | `cp a.txt b.txt` |
| `mv` | 移动/重命名 | `mv a.txt folder/` |
| `rm` | 删除文件 | `rm -rf folder`（慎用）|
| `cat` | 查看文件内容 | `cat readme.md` |

### 搜索 & 查找

| 命令 | 作用 | 示例 |
|------|------|------|
| `grep` | 搜索内容 | `grep "error" log.txt` |
| `find` | 查找文件 | `find . -name "*.js"` |
| `which` | 找命令路径 | `which node` |

### 系统 & 网络

| 命令 | 作用 | 示例 |
|------|------|------|
| `top` / `htop` | 查看进程 | |
| `ps` | 查看运行中的进程 | `ps aux` |
| `kill` | 终止进程 | `kill -9 1234` |
| `ping` | 测试网络连接 | `ping google.com` |
| `curl` | 请求 URL | `curl api.com` |
| `wget` | 下载文件 | `wget url` |
| `ssh` | 远程连接 | `ssh user@host` |
| `scp` | 远程拷贝文件 | `scp file.txt user@host:/path` |

### 权限 & 其他

| 命令 | 作用 | 示例 |
|------|------|------|
| `chmod` | 修改权限 | `chmod +x script.sh` |
| `chown` | 修改所有者 | `chown user:group file` |
| `tar` | 压缩/解压 | `tar -czvf archive.tar.gz folder/` |
| `echo` | 输出文本 | `echo "Hello"` |
| `history` | 查看命令历史 | |

---

## 💻 Windows PowerShell / CMD

| 命令 | 作用 |
|------|------|
| `dir` | 列出文件（等同 ls）|
| `cd` | 切换目录 |
| `mkdir` | 创建目录 |
| `del` | 删除文件 |
| `copy` | 复制文件 |
| `move` | 移动文件 |
| `type` | 查看文件内容 |
| `ipconfig` | 查看 IP 配置 |
| `tasklist` | 查看进程 |
| `netstat` | 查看网络连接 |

---

## 📦 Git（版本控制）常用命令

```bash
git init              # 初始化仓库
git clone url         # 克隆项目
git add .             # 添加到暂存区
git commit -m "msg"   # 提交
git push              # 推送到远程
git pull              # 拉取更新
git branch            # 查看分支
git checkout -b xxx   # 创建并切换分支
git merge xxx         # 合并分支
git status            # 查看状态
git log               # 查看提交历史
```

---

## 🛠️ 开发工具 CLI

### Node.js / npm

```bash
node file.js          # 运行 JS
npm install xxx        # 安装依赖
npx xxx               # 运行包
```

### Python

```bash
python script.py       # 运行 Python
pip install xxx        # 安装库
```

### Docker

```bash
docker ps              # 查看容器
docker images          # 查看镜像
docker run xxx         # 运行容器
```

### Kubernetes

```bash
kubectl get pods       # 查看 pods
kubectl apply -f xxx   # 应用配置
```

---

## 💡 持续学习建议

- 每天学习 1-2 个新命令
- 多动手在终端练习
- 善用 `man <command>` 或 `<command> --help` 查看帮助
- 遇到问题先查文档，再用搜索引擎

---

*最后更新：2026-03-22*
