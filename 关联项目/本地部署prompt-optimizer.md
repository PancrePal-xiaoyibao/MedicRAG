# 1. 克隆项目
git clone https://github.com/linshenkx/prompt-optimizer.git
cd prompt-optimizer

# 2. 安装依赖
iwr https://get.pnpm.io/install.ps1 -useb | iex
pnpm install

# 2.1. 安装依赖 (国内镜像)
npm install -g pnpm --registry=https://registry.npmmirror.com
pnpm -v
pnpm install

# 3. 启动开发服务
pnpm dev               # 主开发命令：构建core/ui并运行web应用
pnpm dev:web          # 仅运行web应用
pnpm dev:fresh        # 完整重置并重新启动开发环境
