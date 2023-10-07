cpp
   #include <iostream>
   #include <tgbot/tgbot.h>

   int main() {
       TgBot::Bot bot("6673254341:AAHpP7u_J-OsWDZatVSazLT818CIKAHbF4M");
       bot.getApi().sendMessage("@your_channel", "Hello from Telegram bot!");

       return 0;
   }
