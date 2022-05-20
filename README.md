# 川叶的 Rime 输入法私房菜

这个配置文件以 Rime 的默认配置为基础，以拼音输入方案作为优化方向，支持全拼和双拼。

## 直接支持的输入法前端

* Windows - Weasel/小狼毫
* Linux - ibus-rime

## 注意事项

* Rime 的默认基础是**繁体**字（传承字）
  * 词库都是以繁体为基础存储的
  * 这样才能正确保留繁-简多对一转换关系
* 这个配置默认打开了CJK常用字过滤
  * Unicode 0x4E00~0x9FFF
  * 这样避免大多数平台上罕见字显示方块的问题
* 默认启用了 emoji
  * Windows 下目前 Weasel 还只能显示黑白 emoji

## 特性

* 支持用户自定义短语
* 更好的标点符号输入，符合当前流行输入法配置
* 支持CJK常用字过滤，可开关
* 支持emoji，可开关
* 开启「八股文」语法模型，输入长句时更准确

默认只开启了小鹤双拼[配置文件](double_pinyin_flypy.custom.yaml)，其它双拼或全拼方案可以参照设置。