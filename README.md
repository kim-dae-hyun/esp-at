# Overview
libat_core.a is AT Command Core, and it is the core of AT command, including the default AT instruction set, the AT command parsing, execution and responding. The lib contains 4 kinds of command, such as `AT+TEST=?`, `AT+TEST?`, `AT+TEST=“abc”` and `AT+TEST`. It supports custom AT commands based on the lib and related APIs, and ones can also define input and output medium, like uart, spi, socket, bt, etc.

The demo is the AT command set based on uart. You can replace the uart driver with other drivers whichever you want to use. But maybe you have to make some changes to run the new driver. In addition, you can add some custom AT commands in `at_custom_cmd` like `AT+CIUPDATE` if necessary.

- Documentation for the latest version: https://docs.espressif.com/projects/esp-at/. This documentation is built from the [docs directory](docs) of this repository
- [How_to_clone_project_and_compile_it.rst](docs/en/Compile_and_Develop/How_to_clone_project_and_compile_it.rst): How to compile ESP AT  
- [ESP_AT_Commands_Set.md](https://docs.espressif.com/projects/esp-at/en/latest/index.html): ESP AT Command Set  
- [How_to_set_AT_port_pin.md](docs/en/Compile_and_Develop/How_to_set_AT_port_pin.md): How to modify AT Port pin  
- [How_to_create_factory_parameter_bin.md](docs/en/Compile_and_Develop/How_to_create_factory_parameter_bin.md): How to add factory parameter 
- [How_to_customize_partitions.md](docs/en/Compile_and_Develop/How_to_customize_partitions.md): What is `The Secondary Partitions Table`    
- [How_to_add_new_platform.md](docs/en/Compile_and_Develop/How_to_add_new_platform.md): How to add new configuration for your module  
- [How_to_update_IDF.md](docs/en/Compile_and_Develop/How_to_update_IDF.md): How to update idf version  
- [How_to_enable_ESP32_AT_Classic_Bluetooth.md](docs/en/Compile_and_Develop/How_to_enable_ESP32_AT_Classic_Bluetooth.md): The example for ESP AT classic bluetooth command  
- [How_to_customize_BLE_services.md](docs/en/Compile_and_Develop/How_to_customize_BLE_services.md): How to customize ble services  
- [How_to_enable_ESP32_AT_Ethernet.md](docs/en/Compile_and_Develop/How_to_enable_ESP32_AT_Ethernet.md): How to use ethernet  
- [How_to_implement_ESP32_SDIO_AT.md](docs/en/Compile_and_Develop/How_to_implement_ESP32_SDIO_AT.md): SDIO AT user guide
- [tools](tools/README.md): Some tools ESP AT used  
- virtual machine (for windows 64bits user): [`http://download.espressif.com/esp_share/env/ubuntu1804.ova`](http://download.espressif.com/esp_share/env/ubuntu1804.ova)
- https://blog.csdn.net/espressif/article/details/79316992: CSDN espressif official blog in Chinese
