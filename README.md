a demo for how to use bluetooth to connect to BLE 4.0 device.
you can use it to communicate with BLE device

一个微信小程序，能够搜索并连接蓝牙4.0设备，还能够和蓝牙设备进行数据交互


please modify the serviceId and characteristicId to match your bluetooth device

请将index.js文件中的 serviceId和characteristicId 修改成和你蓝牙设备相匹配

2017-04-13
增加通用模块，发现设备之后能够搜索设备的serviceId和搜索在该serviceId下的characteristicId（serviceId目前使用的是第一个，如有需要使用其他的请自行修改)


目前请用安卓手机调试，IOS的接口貌似有些不一样，下个版本改进



Q群：54073007