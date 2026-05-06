import asyncio
from aiogram import Bot, Dispatcher, types, F


TOKEN = "8540269202:AAEt7Y-GrrvSphJPWHGoy5H9IgHKnUoEFqM"
CHANNEL_ID = -1003989646004

bot = Bot(token=TOKEN)
dp = Dispatcher()


@dp.message(F.photo)
async def forward_photo(message: types.Message):

    photo = message.photo[-1].file_id
    caption = message.caption if message.caption else ""

    await bot.send_photo(chat_id=CHANNEL_ID, photo=photo, caption=caption)
    await message.reply("Фото отправлено в канал Егора!")


@dp.message(F.video)
async def forward_video(message: types.Message):

    video = message.video.file_id
    caption = message.caption if message.caption else ""

    await bot.send_video(chat_id=CHANNEL_ID, video=video, caption=caption)
    await message.reply("Видео отправлено в канал Егора!")


async def main():
    await dp.start_polling(bot)


if __name__ == '__main__':
    asyncio.run(main())