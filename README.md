# <p align="center"><a href="https://github.com/Teamultroid/xYamiEXTRA"><img src="https://github-readme-stats.vercel.app/api/pin?username=TeamUltroid&show_icons=true&theme=dracula&hide_border=true&repo=xYamiExtra"></a></p>
<p align="center">

# UltroidAddons
Plugins repository for [@TheUltroid](https://github.com/TeamUltroid/xYAMIxSxUBOT).


# Contributing
If you want to contribute to this repository (adding your plugins/porting from other bots), use the format given below and create a pull request.   
⚠️ First check whether the stuff you push works. Also, if the pull request doesn't follow the below format, it will be closed without prior notice.

```python
# Credits @MYALTAW (creator of plugin and who ported)   
   
# Ported from (if ported else skip)   
   
# Ported for YAMI < https://github.com/TeamUltroid/xYAMIsUBOTx >   
```
   
Kindly do not **steal** others works without credits.<br>

# Example Plugin
   Required Import are Automatically Done.

<kbd>This Example Works Everywhere. (e.g. Groups, Personal Chats ...)</kbd>
```python
@ultroid_cmd(pattern="qiw")
async def hello_world_example(event):
    # As telethon is an asyncio based lib, you will have to use `async`/`await` Syntax.
    await event.reply("naonsia!? GELUD? **World**.")
```

<kbd>This Example Works Only In Groups.</kbd>
```python
@ultroid_cmd(pattern="hai", groups_only=True,)
async def hello_world_example(event):
    await event.reply("Naonsia? **World**.")
```

If Your plugin need any additional requirements, it can be added to <a href="https://github.com/TeamUltroid/UltroidAddons/blob/main/addons.txt">addons.txt</a><br><br>

<br>

> For More Information See [The Pypi Page](https://pypi.org/project/py-Ultroid).

> Made with 🤯 by [@ademaunanyabang](https://t.me/MYALTERARTWORK).
