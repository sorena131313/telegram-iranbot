
# import telebot
# from telebot import types

# TOKEN = "7565492628:AAGBCcRD_i6_s7xfrdNdvIz171E_CQTmxjw"  # توکن را با توکن واقعی خود جایگزین کنید
# bot = telebot.TeleBot(TOKEN)

# @bot.message_handler(commands=['start'])
# def start_command(message):
#     bot.send_message(message.chat.id, "درود! به این ربات خوش آمدید. برای عضویت روی /membership بزنید.")

# @bot.message_handler(commands=['membership'])
# def membership_command(message):
#     membership_keyboard = types.ReplyKeyboardMarkup(resize_keyboard=True)
#     membership_keyboard.add("پایتون چیست؟", "منبع یادگیری؟", "بعد از یادگیری؟")
#     bot.send_message(message.chat.id, "یکی از گزینه‌های زیر را انتخاب کنید:", reply_markup=membership_keyboard)

# @bot.message_handler(func=lambda message: message.text == "پایتون چیست؟")
# def python_info(message):
#     bot.send_message(message.chat.id, "پایتون یک زبان سطح بالا و تفسیری چندمنظوره است که مهندسین نرم‌افزار، مهندسین شبکه، هکرها، ریاضیدان‌ها و ... از آن استفاده می‌کنند.")

# @bot.message_handler(func=lambda message: message.text == "منبع یادگیری؟")
# def learning_resources(message):
#     bot.send_message(message.chat.id, "می‌توانیم از سایت‌ها و کتاب‌های مختلف پایتون را یاد بگیریم. ۲ سایت برتر برای یادگیری: W3Schools و دانشجویار. همچنین کتاب‌های پایتون نوشته سعید بشیری.")

# @bot.message_handler(func=lambda message: message.text == "بعد از یادگیری؟")
# def after_learning(message):
#     bot.send_message(message.chat.id, "بعد از یادگیری پایتون، می‌توانیم در شاخه‌های مختلف مانند هوش مصنوعی، یادگیری ماشین، ساخت بات تلگرامی، طراحی وب و توسعه بازی فعالیت کنیم.")

# bot.polling() 





