> [!WARNING]
> The author is not responsible for any illegal, unauthorized, or malicious use of this software, including spying, privacy violations, or leaks of personal information. Use entirely at your own risk and responsibility, subject to applicable law.
> 
# Hidden Recorder [Telegram]
A screen-recording script using **FFmpeg** to record and send videos to Telegram via **cURL** and your bot.
- 60-second recording intervals (50 MB upload limit).
- Basic video compression to reduce file size.
- Automatic Telegram delivery.

# Installation
## Telegram Bot
1. **Create** a bot and get his token with [@BotFather](https://t.me/BotFather)
2. **Add** to your channel/group & **send** a massage
3. **Open** the URL and replace `YOUR_BOT_TOKEN` with your bot's token:

   ```text
   https://api.telegram.org/bot<YOUR_BOT_TOKEN>/getUpdates
   ```

4. **Find** your group ID under `message` → `chat` → `id`:

   ```json
   "chat": {
     "id": -1001234567890,
     "title": "Your Group"
   }
   ```

5. **Copy** the `id` value and use it as your `CHAT_ID`.

> Never share your bot token, Anyone with access to it can control your bot.

**Troubleshooting:** If `getUpdates` returns no messages, check whether a webhook is configured or the bot is receiving updates.
## Recorder
1. **Download** and **extract** to any folder
2. **Edit** `BOT_TOKEN` and `CHAT_ID` inside `run.bat`
3. **Run** `run.vbs`





