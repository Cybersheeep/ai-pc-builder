# API

> **注意**
> 所有配件都有一个 `price` 属性，对应配件的价格（单位：美元）。

- [cpu](#cpu)
- [cpu-cooler](#cpu-cooler)
- [motherboard](#motherboard)
- [memory](#memory)
- [internal-hard-drive](#internal-hard-drive)
- [video-card](#video-card)
- [case](#case)
- [power-supply](#power-supply)
- [os](#os)
- [monitor](#monitor)
- [sound-card](#sound-card)
- [wired-network-card](#wired-network-card)
- [wireless-network-card](#wireless-network-card)
- [headphones](#headphones)
- [keyboard](#keyboard)
- [mouse](#mouse)
- [speakers](#speakers)
- [webcam](#webcam)
- [case-accessory](#case-accessory)
- [case-fan](#case-fan)
- [fan-controller](#fan-controller)
- [thermal-paste](#thermal-paste)
- [external-hard-drive](#external-hard-drive)
- [optical-drive](#optical-drive)
- [ups](#ups)

## `cpu`

| 属性            | 描述                 | 单位（如果适用） |
| ------------------- | --------------------------- | -------------------- |
| `core_count`        | 核心数             |                      |
| `core_clock`        | 核心频率                  | GHz                  |
| `boost_clock`       | 加速频率                 | GHz                  |
| `microarchitecture` | 微架构           |
| `tdp`               | 热设计功耗                         | W                    |
| `graphics`          | 集成显卡（如有） |                      |
| `smt`               | 同步多线程支持                 |                      |

## `cpu-cooler`

| 属性          | 描述                                                                                   | 单位（如果适用） |
| ------------- | -------------------------------------------------------------------------------------- | -------------------- |
| `rpm`         | 风扇转速                                                                               | RPM                  |
| `noise_level` | 噪音水平。可能是一个范围。在这种情况下，其类型为 `[number, number]`，分别对应最小和最大 dB | dB                   |
| `color`       | 颜色                                                                                   |                      |
| `size`        | 散热器尺寸                                                                             | mm                   |

## `motherboard`

| 属性            | 描述            | 单位（如果适用） |
| -------------- | ---------------------- | -------------------- |
| `socket`       | 插槽                |                      |
| `form_factor`  | 外形尺寸            |                      |
| `max_memory`   | 最大内存            | GB                   |
| `memory_slots` | 内存插槽数量         |                      |
| `color`        | 颜色                |                      |

## `memory`

| 属性             | 描述                                                                                         | 单位（如果适用） |
| -------------------- | ---------------------------------------------------------------------------------------- | -------------------- |
| `speed`              | `[number, number]`，分别对应 DDR 版本和 RAM 速度                     | MHz (`[1]`)        |
| `modules`            | `[number, number]`，分别对应模块数量和每个模块的大小 | GB (`[1]`)                          |
| `price_per_gb`       | 每GB价格                                                                                 | USD                  |
| `color`              | 颜色                                                                                     |                      |
| `first_word_latency` | 首字延迟                                                                                 | ns                   |
| `cas_latency`        | CAS 延迟                                                                                 |                      |

## `internal-hard-drive`

| 属性       | 描述                                                                  | 单位（如果适用）   |
| -------------- | ---------------------------------------------------------------------------- | ---------------------- |
| `capacity`     | 容量                                                                     | GB                     |
| `price_per_gb` | 每GB价格                                                                   | USD                    |
| `type`         | 如果是 SSD 则为 `SSD`，否则为 HDD 的速度                 | 如果是 HDD 则为 RPM    |
| `cache`        | 缓存                                                                        | MB                     |
| `form_factor`  | 如果是 M.2 则为 `M.2-xxxx`，否则为 HDD 的尺寸（英寸） | 如果是 HDD 则为 inches |
| `interface`    | PCIe/SATA 接口信息                                              |                        |

## `video-card`

| 属性      | 描述 | 单位（如果适用） |
| ------------- | ----------- | -------------------- |
| `chipset`     | 芯片组     |                      |
| `memory`      | 显存      | GB                   |
| `core_clock`  | 核心频率  | MHz                  |
| `boost_clock` | 加速频率 | MHz                  |
| `color`       | 颜色       |                      |
| `length`      | 长度      | mm                   |

## `case`

| 属性           | 描述                              | 单位（如果适用） |
| ------------------ | ---------------------------------------- | -------------------- |
| `type`             | 类型（ATX/mATX等）                     |                      |
| `color`            | 颜色                                    |                      |
| `psu`              | 包含电源的功率（如有） | W                    |
| `side_panel`       | 侧面板材质信息          |                      |
| `external_volume`  | 外部体积                          | L                    |
| `internal_35_bays` | 内部 3.5" 托架数量             |                      |

## `power-supply`

| 属性     | 描述                                 | 单位（如果适用） |
| ------------ | ------------------------------------------- | -------------------- |
| `type`       | 类型（ATX/SFX等）                         |                      |
| `efficiency` | 效率评级（plus/bronze/silver等） |                      |
| `wattage`    | 功率                                     | W                    |
| `modular`    | 模块化（Full/Semi/`false`)              |                      |
| `color`      | 颜色                                       |                      |

## `os`

| 属性     | 描述                                                                    | 单位（如果适用） |
| ------------ | ------------------------------------------------------------------------------ | -------------------- |
| `mode`       | `number` 或 `[number, number]`，对应 32 位、64 位或两者 |                      |
| `max_memory` | 最大内存                                                                 |                      |

## `monitor`

| 属性        | 描述                                                        | 单位（如果适用） |
| --------------- | ------------------------------------------------------------------ | -------------------- |
| `screen_size`   | 屏幕尺寸（对角线长度）                                   | in                   |
| `resolution`    | `[number, number]`，分别对应宽度和高度 | pixels               |
| `refresh_rate`  | 刷新率                                                       | Hz                   |
| `response_time` | 响应时间                                                      | ms                   |
| `panel_type`    | 面板类型（IPS/TN等）                                           |                      |
| `aspect_ratio`  | 宽高比（例如 16:9）                                           |                      |

## `sound-card`

| 属性        | 描述                            | 单位（如果适用） |
| --------------- | -------------------------------------- | -------------------- |
| `channels`      | 声道                               |                      |
| `digital_audio` | 数字音频单元（64, 32, 24 等） |                      |
| `snr`           | 信噪比 (signal-to-noise ratio)            | dB                   |
| `sample_rate`   | 采样率                            | kHz                  |
| `chipset`       | 芯片组                                |                      |
| `interface`     | 接口（例如 PCI/PCIe x1）           |                      |

## `wired-network-card`

| 属性    | 描述                    | 单位（如果适用） |
| ----------- | ------------------------------ | -------------------- |
| `interface` | 接口（例如 PCIe x8/x4/x1） |                      |
| `color`     | 颜色                          |                      |

## `wireless-network-card`

| 属性    | 描述                    | 单位（如果适用） |
| ----------- | ------------------------------ | -------------------- |
| `protocol`  | 协议（例如 Wi-Fi 6E/6/5）   |                      |
| `interface` | 接口（例如 PCIe x8/x4/x1） |                      |
| `color`     | 颜色                          |                      |

## `headphones`

| 属性             | 描述                                                                                  | 单位（如果适用） |
| -------------------- | -------------------------------------------------------------------------------------------- | -------------------- |
| `type`               | 类型（例如 Circumaural/Earbud等）                                                          |                      |
| `frequency_response` | `[number, number]`，分别对应频率响应范围（最小和最大） | kHz                  |
| `microphone`         | 是否有麦克风                                                                  |                      |
| `wireless`           | 是否为无线                                                                       |                      |
| `enclosure_type`     | 封装类型（例如 Closed/Open）                                                            |                      |
| `color`              | 颜色                                                                                        |                      |

## `keyboard`

| 属性          | 描述                                      | 单位（如果适用） |
| ----------------- | ------------------------------------------------ | -------------------- |
| `style`           | 风格（例如 Gaming/Mini）                         |                      |
| `switches`        | 开关类型（例如 Cherry Viola/Logitech GL） |                      |
| `backlit`         | 背光颜色（例如 RGB/多色/纯色）  |                      |
| `tenkeyless`      | 是否为无小键盘设计                         |                      |
| `connection_type` | 连接类型（有线、无线或多种）   |                      |
| `color`           | 颜色                                            |                      |

## `mouse`

| 属性           | 描述                                    | 单位（如果适用） |
| ------------------ | ---------------------------------------------- | -------------------- |
| `tracking_method`  | 追踪方式（例如 光学/激光）           |                      |
| `connection_type`  | 连接类型（有线、无线或多种） |                      |
| `max_dpi`          | 最大 DPI                                    | dpi                  |
| `hand_orientation` | 手型偏向（左手/右手/双手）             |                      |
| `color`            | 颜色                                          |                      |

## `speakers`

| 属性             | 描述                                                                               | 单位（如果适用） |
| -------------------- | ----------------------------------------------------------------------------------------- | -------------------- |
| `configuration`      | 声道配置                                                                     |                      |
| `wattage`            | 功率                                                                                   | W                    |
| `frequency_response` | `[number, number]`，分别对应低频和高频响应 | kHz                  |
| `color`              | 颜色                                                                                     |                      |

## `webcam`

| 属性      | 描述                                                      | 单位（如果适用） |
| ------------- | ---------------------------------------------------------------- | -------------------- |
| `resolutions` | 支持的分辨率列表（例如 `["4k", "1080p", "720p"]`)    |                      |
| `connection`  | 连接类型                                               |                      |
| `focus_type`  | 对焦类型（自动/手动/固定）                                   |                      |
| `os`          | 支持的操作系统列表（例如 `["Windows", "OS X"]`) |                      |
| `fov`         | 视角                                                        | degrees (°)      |

## `case-accessory`

| 属性      | 描述                                                                                                      | 单位（如果适用） |
| ------------- | ---------------------------------------------------------------------------------------------------------------- | -------------------- |
| `type`        | 类型（LED 控制器/读卡器）                                                                                |                      |
| `form_factor` | 外形尺寸（例如 `2.5`）。可能是 `[number, number]`，这种情况下 `[0]` 是数量，`[1]` 是尺寸 | in （如果是数组则 `[1]`）  |

## `case-fan`

| 属性      | 描述                                                                                          | 单位（如果适用） |
| ------------- | ---------------------------------------------------------------------------------------------------- | -------------------- |
| `size`        | 尺寸                                                                                                 | mm                   |
| `color`       | 颜色                                                                                                |                      |
| `rpm`         | `number` 或 `[number, number]`，分别对应最小和最大 RPM 值         | RPM                  |
| `airflow`     | `number` 或 `[number, number]`，分别对应最小和最大气流 CFM 值 | CFM                  |
| `noise_level` | `number` 或 `[number, number]`，分别对应最小和最大噪音水平值 | dB                   |
| `pwm`         | 是否为 PWM                                                                                    |                      |

## `fan-controller`

| 属性          | 描述               | 单位（如果适用） |
| ----------------- | ------------------------- | -------------------- |
| `channels`        | 通道数量        |                      |
| `channel_wattage` | 通道功率           | W                    |
| `pwm`             | 是否为 PWM         |                      |
| `form_factor`     | 外形尺寸（例如 `5.25`) | in                   |
| `color`           | 颜色                     |                      |

## `thermal-paste`

| 属性 | 描述 | 单位（如果适用） |
| -------- | ----------- | -------------------- |
| `amount` | 用量      | g                    |

## `external-hard-drive`

| 属性       | 描述             | 单位（如果适用） |
| -------------- | ----------------------- | -------------------- |
| `type`         | 类型（台式机/便携式） |                      |
| `interface`    | 接口               |                      |
| `capacity`     | 容量                | GB                   |
| `price_per_gb` | 每GB价格              | USD                  |
| `color`        | 颜色                   |                      |

## `optical-drive`

| 属性    | 描述                                | 单位（如果适用） |
| ----------- | ------------------------------------------ | -------------------- |
| `bd`        | BD 读取速度                              |                      |
| `dvd`       | DVD 读取速度                             |                      |
| `cd`        | CD 读取速度                              |                      |
| `bd_write`  | BD 写入速度（例如 `14/12/2/2`)        |                      |
| `dvd_write` | DVD 写入速度（例如 `16/8/8/6/12/8/5`) |                      |
| `cd_write`  | CD 写入速度（例如 `48/32`)            |                      |

## `ups`

| 属性      | 描述             | 单位（如果适用） |
| ------------- | ----------------------- | -------------------- |
| `capacity_w`  | 容量                | W                    |
| `capacity_va` | 容量（伏安） | VA                   |