# <p align="center"><a href="https://github.com/Teamultroid/Ultroid"><img src="https://github-readme-stats.vercel.app/api/pin?username=TeamUltroid&show_icons=true&theme=dracula&hide_border=true&repo=ultroid"></a></p>
<p align="center">

# UltroidAddons
Plugins repository for [@xYAMIxSxUBOT](https://github.com/TeamUltroid/Ultroid).


# Contributing
If you want to contribute to this repository (adding your plugins/porting from other bots), use the format given below and create a pull request.   
⚠️ First check whether the stuff you push works. Also, if the pull request doesn't follow the below format, it will be closed without prior notice.

```python
# Credits @ademaunanyabang (creator of plugin and who ported)   
   
# Ported from @TheUltroid < https://github.com/TeamUltroid/ULTROIDADDONS >
   
# Ported for @xYAMIxSxUBOT < https://github.com/Upilkimpul/xYamiXTRA >   
```
   
Kindly do not **steal** others works without credits.<br>

# Example Plugin
   Required Import are Automatically Done.

<kbd>This Example Works Everywhere. (e.g. Groups, Personal Chats ...)</kbd>
```python
@ultroid_cmd(pattern="Qiw")
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

> Made with 🤯 by [@ademaunanyabang](https://t.me/MYALTERARTWORK)
> Support by 🚬 [ @TheUltroid ](https://t.me/theUltroid) 
