# USB Behind the Scenes: Hands-on HID Firmware Development

## Environment Setup

* Hardware

    * Component

        1. PC
        1. STM32F429 Discovery board
        1. Raspberry pi
        1. USB Type-A to Mini-B connector
        1. USB Type-A to Micro-AB connector

    * connection

        PC <-> USB Type-A to Mini-B <-> STM32F429 <-> USB Micro-AB to Type-A <-> Raspberry pi

* Software

    1. [STM32CubeIDE](https://www.st.com/en/development-tools/stm32cubeide.html)
    1. [STM32CubeF4](https://www.st.com/content/st_com_cx/en/products/embedded-software/mcu-mpu-embedded-software/stm32-embedded-software/stm32cube-mcu-mpu-packages/stm32cubef4.html) (to get CMSIS)
    1. [ST-LINK-SERVER](https://www.st.com/content/st_com_cx/en/products/development-tools/software-development-tools/stm32-software-development-tools/stm32-performance-and-debuggers/st-link-server.html)
    1. [STSW-LINK007](https://www.st.com/content/st_com_cx/en/products/development-tools/software-development-tools/stm32-software-development-tools/stm32-programmers/stsw-link007.html) / [STSW-LINK009](https://www.st.com/content/st_com_cx/en/products/development-tools/software-development-tools/stm32-software-development-tools/stm32-utilities/stsw-link009.html) (upgrade ST-LINK firmware, optional)



