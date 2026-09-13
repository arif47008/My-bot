import telebot

TOKEN = "8851392195:AAHMewK-mgjrxMEhzPkVt-Ixo8uC1wK4BKg"
bot = telebot.TeleBot(TOKEN)

@bot.message_handler(commands=['start'])
def start(message):
    user_name = message.from_user.first_name
    bot.send_message(message.chat.id, f"হ্যালো {user_name}! 👋\nআমাদের রিওয়ার্ড বটে স্বাগতম।")

print("Bot is running...")
bot.infinity_polling()
