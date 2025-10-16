import telebot
import os

# Render uchun tokenni muhitdan olamiz
TOKEN = os.getenv("BOT_TOKEN")
bot = telebot.TeleBot(TOKEN)

@bot.message_handler(commands=['start'])
def start(message):
    bot.reply_to(message, "Salom! 👋 Bot ishlayapti ✅")

bot.polling()
