---
activation_count: 4
arousal: 0.3
created: '2026-07-09T15:47:50'
domain:
- 硬件
- 编程
id: bcec6d8ce73a
importance: 9
last_active: '2026-07-24T15:10:26'
name: SVAKOM BLE控制协议
tags:
- SVAKOM
- 司沃康
- BLE协议
- Service UUID
- Characteristic UUID
- 指令格式
- 震动模式
- 预设模式
- Buttplug
- ble-mcp-server
- MCP
- BLE设备
- Bleak
- Python库
- 远程控制
- 分欣
- 技术
type: dynamic
valence: 0.5
---

SVAKOM(司沃康) BLE协议：Service UUID=0000FFE0-0000-1000-8000-00805f9b34fb，Characteristic UUID=0000FFE1-0000-1000-8000-00805f9b34fb。指令6字节格式：55 03 00 | kind | preset | intensity。kind=0x00普通震动/0x03预设模式。preset=0x00关/0x01-0x0B对应11种模式(Surge/Tempo/Speedy/Edging/Rushing/Stamina Training/The One/The Tease/Climax/The Shock/Seductive)。intensity=0x00关/0x01-0x0A对应10%-100%。Buttplug已支持SVAKOM全系协议。ble-mcp-server支持AI通过MCP直接控制BLE设备。分欣到后Mac Mini用Bleak(Python库)写入指令即可远程控制。