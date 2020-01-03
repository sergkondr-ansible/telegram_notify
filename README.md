# telegram_notify

### Example
```
telegram_chat_id: "1234567890"
telegram_bot_token: "987654321:ABCDEF...."
telegram_notification_message: "Eve is still working, $(uptime -p)"
telegram_startup_message: "Eve is started up with $(nproc) CPUs and $(free -h | grep Mem | awk '{print $2}') Mem"
```

### How to find out chat id:
1. Add bot to group
2. Write: `/test @bot_name`
3. `curl https://api.telegram.org/bot987654321:ABCDEF..../getUpdates`
