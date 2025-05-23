# STM32F103驱动SG90舵机调试驱动库

## 简介
本仓库提供了一个用于STM32F103C8T6微控制器驱动SG90舵机的调试驱动库。该驱动库配置了多个定时器（TIM2、TIM3、TIM4）的PWM端口，并支持多种重映射模式下的不同IO口配置。通过使用该驱动库，用户可以快速、简单地配置和驱动SG90舵机，节省开发时间。

## 资源文件
- **文件名**: `stm32f103驱动SG90舵机调试驱动库.zip`
- **描述**: 该资源文件包含了STM32F103C8T6驱动SG90舵机的调试驱动库，配置了多个定时器的PWM端口，支持多种重映射模式下的不同IO口配置。

## 功能特点
- **多定时器支持**: 配置了TIM2、TIM3、TIM4的PWM端口，方便用户根据需求选择合适的定时器。
- **多种重映射模式**: 支持多种重映射模式下的不同IO口配置，适应不同的硬件连接需求。
- **简单易用**: 驱动库设计简洁，调用方便，用户可以快速上手。

## 适用对象
- 需要使用STM32F103C8T6微控制器驱动SG90舵机的开发者。
- 希望快速配置和调试SG90舵机的项目。

## 使用方法
1. 下载并解压`stm32f103驱动SG90舵机调试驱动库.zip`文件。
2. 将解压后的文件导入到您的STM32项目中。
3. 根据您的硬件连接，配置相应的定时器和IO口。
4. 调用驱动库中的函数，实现SG90舵机的控制。

## 注意事项
- 请确保您的硬件连接正确，特别是IO口和定时器的配置。
- 在使用重映射模式时，请参考STM32F103C8T6的数据手册，确保配置正确。

## 贡献
如果您在使用过程中发现任何问题或有改进建议，欢迎提交Issue或Pull Request。

## 许可证
本项目采用MIT许可证，详情请参阅LICENSE文件。

## 下载链接
[STM32F103驱动SG90舵机调试驱动库](https://pan.quark.cn/s/3166485ce3d0) 

(备用: [备用下载](https://pan.baidu.com/s/1qOLphgRgRmdCL_pMcQ5aNg?pwd=1234))

## 说明

该仓库仅用于学习交流，请勿用于商业用途。
