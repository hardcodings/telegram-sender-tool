# telegram-sender-tool
This bot is meant for sending mass messages to bulk telegram users. Developer: https://t.me/pysmart

developer: https://t.me/pysmart

![tgm](https://github.com/user-attachments/assets/65b50427-3b11-4260-a522-8c784599e0e0)


# STEPS TO FOLLOW CORRECTLY
- Set Up Telegram API Credentials from telegram API URL
- You'll need an API Credentials from my.telegram.org.
 
<b>ALSO AVAILABLE FOR TELEGRAM MASS DMs</b>

developer: https://t.me/pysmart

- Go to my.telegram.org.
- Log in with your phone number.
- Click on API development tools.
- Copy your API ID and API Hash.

<b>ALSO AVAILABLE FOR TELEGRAM MASS DMs</b>

developer: https://t.me/pysmart

# How It Works:
- Session Saving: The TelegramClient('session_name', api_id, api_hash) automatically saves the session into a file named session_name.session.
- When you run the script again, it won't ask you to log in if the session is still valid.
- Login: The script starts by logging in using your phone number. If the session is already saved, it skips this step.
- Sending Messages: It reads a file (users.txt) containing usernames or phone numbers and sends a message to each one.

<b>ALSO AVAILABLE FOR TELEGRAM MASS DMs</b>

developer: https://t.me/pysmart

# Notes
Ensure that the users.txt file is in the same directory as the script or provide an absolute path.
For sending messages to phone numbers, ensure they are in your Telegram contacts. 

sending automated messages to telegram users after scraping the users from bulk group or channel.

TELEGRAM SENDER TOOL
