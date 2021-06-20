# Home Control Discord Bot
This Discord bot can control your home!

_I'm still working on the Docs! Here's the main code though:_

```
import discord
import requests
from discord.ext import commands

bot = commands.Bot(command_prefix='!')


@bot.command()
async def COMMAND-NAME(ctx):
    requests.post('https://maker.ifttt.com/trigger/fan/with/key/YOUR_KEY')
    print('CONSOLE OUTPUT')
    await ctx.send('MESSAGE TO SEND')


@bot.command()
async def COMMAND-NAME(ctx):
    requests.post('https://maker.ifttt.com/trigger/fan/with/key/YOUR_KEY')
    print('CONSOLE OUTPUT')
    await ctx.send('MESSAGE TO SEND')
    
bot.run('YOUR_TOKEN')

```

