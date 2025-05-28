# 自定义聊天气泡配置说明

此文档介绍了Yuki自定义聊天气泡的配置参数及其作用。通过修改这些参数，您可以创建个性化的聊天气泡效果。

## 配置参数说明

| 参数名 | 说明 | 格式 |
|-------|------|------|
| `identifier` | 气泡的唯一标识符，用于区分不同的气泡样式 | 字符串 |
| `gradientColorStart` | 气泡渐变色的起始颜色 | RGBA十六进制 |
| `gradientColorEnd` | 气泡渐变色的结束颜色 | RGBA十六进制 |
| `ltIconURL` | 气泡左上角图标的URL地址 | 有效的图片URL |
| `rtIconURL` | 气泡右上角图标的URL地址 | 有效的图片URL |
| `lbIconURL` | 气泡左下角图标的URL地址 | 有效的图片URL |
| `rbIconURL` | 气泡右下角图标的URL地址 | 有效的图片URL |

## 颜色格式说明

颜色格式采用RGBA十六进制，例如：`70A94FF0`

- 前6位（`A94FF0`）：表示RGB颜色值
- 后2位（`70`）：表示透明度，`00`为完全透明，`FF`为完全不透明

## 使用示例

以下是一个配置示例：

```json
{
  "identifier": "YukiCustom",
  "gradientColorStart": "70A94FF0",
  "gradientColorEnd": "70683AF4",
  "ltIconURL": "https://example.com/icon.png",
  "rtIconURL": "https://example.com/icon.png",
  "lbIconURL": "https://example.com/icon.png",
  "rbIconURL": "https://example.com/icon.png"
}
```
