## Hi there 👋
# Hi 👋, I'm 马莹莹

### 哈尔滨信息工程学院嵌入式专业学生

-  👩‍🎓 **计算机科学与技术（嵌入式方向）2027届毕业生**

- 👌**我掌握 C语言程序设计 ，C++面向对象编程 ，嵌入式系统原理及应用， Linux操作系统，计算机组成原理**
- 👍**辅修课程：计算机网络 ，数据结构与算法 ，Python程序设计 ，数字电路与逻辑 ，Qt应用开发**

## 项目经历
### **基于 STM32 的新能源汽车电池热管理监测与智能控制系统　　2026.04–2026.07**
- **技术栈： STM32F103、HAL、IIC、SPI、1-Wire、ADC、PWM、TIM、ESP8266、PyQt、立创EDA**

* 个人独立完成系统软硬件设计，实现**电池温度/电压/电流、环境温湿度及振动状态**多参数实时采集，构建“采集—判断—控制—报警—通信”闭环。
* 基于 **STM32F103 + HAL** 完成 DS18B20、ACS712、DHT11 等传感器驱动及数据滤波；利用 **TIM 实现微秒级时序控制**，完成 DHT11 40 位数据稳定读取。
* 设计**分级热管理策略**，通过 PWM 控制风扇、继电器控制水泵及保护回路，并结合蜂鸣器/LED 实现分级报警。
* 基于 **IIC + OLED、ESP8266 WiFi** 实现本地参数显示、阈值设置、数据上传及远程指令响应；基于 **Python + PyQt** 开发上位机，实现实时曲线、故障记录及数据导出。
* 针对风扇驱动噪声导致 DS18B20 采样异常的问题，通过**物理隔离、独立供电及布线优化**改善信号质量，完成软硬件联调与功能验证。

### **基于 STM32 的简易数字示波器设计与实现　　2026.03–2026.06**

- **技术栈： STM32、立创EDA、ADC、TIM、PWM、输入捕获、外部中断、FreeRTOS、LCD**
* **硬件设计：** 独立完成 STM32 主控原理图设计及 PCB 布局布线，设计模拟信号调理与 ADC 采样电路，通过**模拟/数字分区、地线规划及采样走线优化**降低数字电路对模拟信号采集的干扰。
* **底层驱动：** 基于 STM32 完成 **ADC、TIM、PWM、输入捕获、外部中断、按键、串口及 LCD** 等外设驱动开发，引入 **FreeRTOS** 实现采样、显示、按键等任务的并发调度。
* **波形采集与显示：** 利用定时器控制 ADC 周期采样，完成采样数据处理及**波形重建算法**，将 ADC 数据实时映射至 LCD 坐标系并绘制波形；支持按键调整采样参数及波形触发阈值。
* **信号测量：** 基于 ADC 采样数据实现输入信号**幅值测量**，结合 TIM 输入捕获实现**频率测量**，完成从模拟信号采集、数据处理到波形可视化的完整链路。
* **项目成果：** 独立完成从**原理图设计、PCB Layout、底层驱动、实时任务调度到波形显示与功能测试**的全流程开发，实现简易数字示波器核心功能。

- 📫 How to reach me **2870412948@qq.com**  **15754609606**

- 👨‍💻 All of my projects are available at **[https://github.com/MaYingYing-ui](https://github.com/MaYingYing-ui)**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://github.com/mayingying" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/github.svg" alt="mayingying" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://developer.mozilla.org/en-US/docs/Web/c" target="_blank" rel="noreferrer"> <img src="https://skillicons.dev/icons?i=c" alt="c" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/python" target="_blank" rel="noreferrer"> <img src="https://skillicons.dev/icons?i=py" alt="python" width="40" height="40"/> </a></p>

