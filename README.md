# gpio_timer_rtc_irqs

This repository included an example of how to use AXI GPIO and AXI Timer design and enable irq's on it.

To be able to use more than one signal and different interrupts Concat IP is used.

# Design

I am using Shared peripheral interrups (SPI) in this design. 

![](images/gpio_timer_irqs.png?raw=true)

# Versions

Vivado version for this design is 2014.4.

# Target platform

Target platform is zynq 7000 zedboard.

# Compile and run sample

Just use Xilinx SDK with the project is included in this repo and there should not be any problem to make a correct deploy.

Enjoy!
