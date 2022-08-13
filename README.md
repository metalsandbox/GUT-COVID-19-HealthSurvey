# GUT-COVID-19-HealthSurvey
iOS / iPadOS 适用的桂林理工大学健康打卡快捷指令
# 可以实现的功能
- [x] 快速跳转到钉钉打卡页面
- [x] 通过快捷指令 App 可以实现半自动化
# 概述
快捷指令 App 可以轻易通过 scheme 链接跳转到本地 App 的指定页面。桂林理工大学使用钉钉智能填表作为打卡工具，通过上述手段可直接跳转至信息填写页面，节省打卡时间。
# 实现方式
通过 Web 版钉钉获取打卡页面 scheme 链接，将链接中的时间戳替换为实时数据即即可实现。
# 声明
本方式仅可实现半自动化打卡。通过本方式上报的信息由使用者完全控制，本人不收集、篡改、使用任何个人信息。
# 许可
MIT License

Copyright (c) 2022 ORAKUSA

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
