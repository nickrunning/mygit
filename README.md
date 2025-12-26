# mygit

自定义 Git 工具集

A collection of custom shell-based Git tools and helper scripts.

## Features / 功能

- 一组用 Shell 编写的 Git 辅助脚本，用于简化常见操作
- 自动化工作流与常用别名脚本
- 易于扩展与集成到个人 dotfiles 或 CI 中

## Installation / 安装

Clone the repository:

git clone https://github.com/nickrunning/mygit.git

进入仓库目录后将脚本添加到 PATH（可选）：

cd mygit
sudo cp -r bin/* /usr/local/bin/

或将仓库目录加入 PATH：

export PATH="$PATH:$(pwd)/bin"

## Usage / 使用方法

查看可用脚本或帮助：

ls -1 bin/

举例：

./bin/example.sh

每个脚本的顶部通常包含用法说明，请根据脚本注释运行。

## Contributing / 贡献

欢迎提交 issue、建议或 pull request。

- 提交前请确保脚本有可重复的行为并添加必要说明
- 对重大更改请先打开 issue 讨论设计

## License / 许可证

请在此处填写许可证信息（例如 MIT）。

## Contact / 联系方式

如果有问题或建议，请在仓库中打开 issue，或联系 @nickrunning。
