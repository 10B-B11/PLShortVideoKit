# PLShortVideoKit

PLShortVideoKit 是七牛推出的一款适用于 iOS 平台的短视频 SDK，提供了包括美颜、滤镜、水印、断点录制、分段回删、视频编辑、混音特效、本地/云端存储在内的多种功能，支持高度定制以及二次开发。

# 1 功能列表
短视频 SDK 的功能，主要分为 4 大块：拍摄、编辑、转码、上传。

## 1.1 视频拍摄
| 功能点                 | 版本       |
| ------------------- | -------- |
| 摄像头采集               | 1.0.0(+) |
| 麦克风采集               | 1.0.0(+) |
| 静音功能                | 1.0.0(+) |
| 实时美颜                | 1.0.0(+) |
| 贴纸特效                | 1.0.0(+) |
| 大眼/瘦脸               | 1.0.0(+) |
| 闪光灯开关               | 1.0.0(+) |
| 第三方美颜接口             | 1.0.0(+) |
| 第三方滤镜接口             | 1.0.0(+) |
| 自定义拍摄时长             | 1.0.0(+) |
| 自定义分辨率              | 1.0.0(+) |
| 自定义视频帧率             | 1.0.0(+) |
| 自定义视频码率             | 1.0.0(+) |
| 支持 1:1 正方形录制        | 1.0.0(+) |
| 断点拍摄（多段录制）          | 1.0.0(+) |
| 回删视频                | 1.0.0(+) |
| H.264 硬编            | 1.0.0(+) |
| AAC 硬编              | 1.0.0(+) |
| 输出 mp4 文件           | 1.0.0(+) |
| 支持 ARM7, ARM64 及模拟器 | 1.0.0(+) |
| 实时滤镜                | 1.0.0(+) |
| 实时水印                | 1.0.0(+) |
| 手动对焦                | 1.0.0(+) |
| 自动对焦                | 1.0.0(+) |
| 曝光调节                | 1.0.0(+) |
| 横屏拍摄                | 1.3.0(+) |

### 1.1.1 录屏
| 功能点                 | 版本       |
| --------------------- | --------- |
| 外部导入音视频数据       | 1.2.0(+) |

## 1.2 视频编辑
### 1.2.1 视频剪辑
| 功能点    | 版本       |
| ------ | -------- |
| 关键帧预览  | 1.0.2(+) |
| 剪辑指定区间 | 1.0.2(+) |
| 截取封面   | 1.0.2(+) |

### 1.2.2 视频特效
| 功能点   | 版本       | 备注 |
| ----- | -------- |-------- |
| 滤镜    | 1.0.0(+) | 无 |
| 水印    | 1.0.0(+) | 无 |
| 贴纸特效  | 1.0.0(+) | 基于面部识别，需要额外付费 |
| 大眼/瘦脸 | 1.0.0(+) | 基于面部识别，需要额外付费 |

### 1.2.3 音频特效
| 功能点        | 版本       |
| ---------- | -------- |
| 音频混合       | 1.0.3(+) |
| 截取音频片段     | 1.0.3(+) |
| 调节原声/背景声音量 | 1.0.3(+) |

### 1.2.4 视频合成
| 功能点     | 版本   |
| ------- | ---- |
| 片头片尾 MV | 暂不支持 |
| 图像/视频合成  | 暂不支持 |
| 制作 GIF 动图  | 1.3.0(+) |

### 1.2.5 视频转码
| 功能点  | 版本       |
| ---- | -------- |
| 画面剪裁 | 1.1.0(+) |
| 码率变换 | 1.1.0(+) |

## 1.3 视频上传
| 功能点  | 版本       |
| ---- | -------- |
| 上传云端 | 1.0.4(+) |
| 断点续传 | 1.1.0(+) |

## 2. 设备以及系统要求

- 设备要求：搭载 iOS 系统的设备
- 系统要求：iOS 8.0 及其以上

## 3. 安装方法

[CocoaPods](https://cocoapods.org/) 是针对 Objective-C 的依赖管理工具，它能够将使用类似 PLShortVideoKit 的第三方库的安装过程变得非常简单和自动化，你能够用下面的命令来安装它：

```bash
$ sudo gem install cocoapods
```

### Podfile

为了使用 CoacoaPods 集成 PLShortVideoKit 到你的 Xcode 工程当中，你需要编写你的 `Podfile`

```ruby
target 'TargetName' do
pod 'PLShortVideoKit'
end
```

然后，运行如下的命令：

```bash
$ pod install
```

## 4. PLShortVideoKit 文档

请参考开发者中心文档：[PLShortVideoKit 文档](https://developer.qiniu.com/pili/sdk/3733/short-video-ios-sdk)

## 5. 声明

本短视频 SDK 需授权方可使用，可通过 400-808-9176 转 2 号线联系七牛商务咨询，或者 [通过工单](https://support.qiniu.com/?ref=developer.qiniu.com) 联系七牛的技术支持。

## 6. 反馈及意见

当你遇到任何问题时，可以通过在 GitHub 的 repo 提交 issues 来反馈问题，请尽可能的描述清楚遇到的问题，如果有错误信息也一同附带，并且在 Labels 中指明类型为 bug 或者其他。

[通过这里查看已有的 issues 和提交 Bug](https://github.com/pili-engineering/PLShortVideoKit/issues)







