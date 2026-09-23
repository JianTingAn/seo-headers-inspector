# SEO 响应头检查器

检查网页响应头中的内容类型、缓存、压缩和 X-Robots-Tag，帮助百度蜘蛛稳定理解页面和抓取策略。

## 核心功能
- 检查 X-Robots-Tag 与缓存头
- 识别错误 Content-Type
- 观察压缩和响应性能信号
- 输出适合部署前审查的结果

## 使用
```powershell
python tool.py --demo
python tool.py --input sample.csv --json
```
调整响应头前应在测试环境验证，避免误设置 noindex、nosnippet 或禁止抓取指令。

官网：https://jta.mobi  
QQ群：1039545483

## 许可证
MIT License
