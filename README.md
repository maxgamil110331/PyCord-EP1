# ***使用PyCord製作Discord機械人 EP1 —— 基本設置***
Step 1:
>在終端機打上
```
pip uninstall discord discord.py -y
pip install pycord
pip install py-cord[voice]
```
-----------------------------
Step 2:
>建立一個Python檔案，並打上
```py
import discord
from discord.ext import commands


bot=commands.Bot(command_prefix="前綴", intents=discord.Intents.all()) #如不打算用文字指令，可直接把「command_prefix="前綴"」删掉


bot.run("TOKEN") #這裏放上token
```
-----------------------------
Step 3:
>運行檔案，機械人就上線了！
