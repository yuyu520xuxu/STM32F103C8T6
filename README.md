# STM32F103C8T6 Blank Template

这是一个基于 **STM32F103C8T6** (Cortex-M3) 的空白工程模板，使用标准外设库 (Standard Peripheral Library) 编写。

## 🛠️ 开发环境
- **IDE / 编辑器**：VS Code
- **插件**：EIDE (Embedded IDE)
- **编译器**：ARM GNU Toolchain (arm-none-eabi-gcc)
- **构建工具**：GCC + Make (EIDE 内置)
- **烧录 / 调试工具**：ST-Link / 通过 OpenOCD 或 STM32CubeProgrammer

## 📂 目录结构
- `Libraries/`：STM32 标准外设库文件
- `Start/`：启动文件 (startup) 和核心文件 (core_cm3)
- `User/`：用户代码 (包含 `main.c`、中断处理文件等)
- `STM32F103C8T6/`：EIDE 工程配置文件夹
- `.gitignore`：Git 忽略文件配置

## 🚀 如何使用
1. 克隆本仓库到本地：
   ```bash
   git clone https://github.com/yuyu520xuxu/STM32F103C8T6.git
