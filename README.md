# game-ai
# 1.项目说明
基于大模型的文字冒险游戏设计与实现
# 2.温馨提示
1.完整体验项目请将self.api_config补充完整
```python
elf.api_config = {
            "url": "yourmodelurl", 
            "api_key": "yourapikey",  
            "model": "yourmodel",  
            "temperature": 0.7  # 控制生成文本的随机性
        }
```
本项目建议python3.10及以上版本运行
3.re-v1.0.0及一下版本需要tkinter、requests以及openai库
4.re-v2.0.0及以上版本需要增加pyttsx3、threading以及queue库
