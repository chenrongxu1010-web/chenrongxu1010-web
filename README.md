# Hi, I'm chenrongxu1010-web 👋

四川农业大学信息工程学院学生，求职方向：**嵌入式软件实习生**。

围绕 STM32 裸机外设开发积累实践，也通过校园应用和自动化工具训练接口联调、异常定位与回归验证能力。

## 重点项目

### [STM32 环境监测与报警终端](https://github.com/chenrongxu1010-web/stm32-environment-monitor)

`C` · `STM32F401RE` · `HAL` · `STM32CubeIDE` · `I2C` · `SPI` · `UART` · `EXTI`

- 集成 AHT20 温湿度采集、SSD1306 OLED 显示及串口调试输出。
- 使用 W25Q64 保存报警配置，组织外设驱动、配置管理和报警业务模块。
- 通过 EXTI 事件标志与主循环处理按键，记录 SPI 通信异常的逐层排查过程。
- 仓库提供接口说明、工程文件及已知限制；报警恢复逻辑与硬件边界验证仍待完善，FreeRTOS 为后续学习计划。

### 小禾校园搭子｜校园应用工程实践

`JavaScript` · `Python / FastAPI` · `MySQL` · `微信云托管` · `COS`

- 面向课表、校园活动、社团和美食评价场景，实践前后端接口联调与云端服务维护。
- 处理图片上传、访问权限、内容安全检查和失败提示，结合日志定位问题。
- 使用自动化测试覆盖输入边界、权限及交互状态，关注弱网、重复操作和错误恢复。

[早期交互原型](https://github.com/chenrongxu1010-web/campus-assistant-prototype)用于展示产品探索过程，不等同于当前小程序源码；本项目是软件工程补充经历，并非嵌入式固件项目。

### [自动化测试与日志分析工具](https://github.com/chenrongxu1010-web/auto-test-log-analyzer)

`Python` · `Shell` · `Linux / WSL` · `unittest`

批量执行模拟任务，分析日志并输出 CSV / Markdown 报告，练习测试用例、缺陷记录和回归验证流程。当前任务为模拟任务，并非生产测试平台。

## 当前关注

- 外设通信、模块化 C 程序与可复现的调试记录。
- 补齐 STM32 报警边界验证和配置可靠性。
- 后续学习 FreeRTOS 任务划分、通信与同步。

欢迎围绕项目实现、问题复现和改进方案交流。
