from PURVIMUSIC import app
from pyrogram import Client, enums
from pyrogram.handlers import EditedMessageHandler
import asyncio

@app.on_edited_message()
async def edited_message(client: Client, message): 
    await message.delete(); warning =    await message.reply(f"⚠️ {message.from_user.mention}, edited messages not allowed!"); await asyncio.sleep(3); await warning.delete()
