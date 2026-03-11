openclaw安装
官网 https://github.com/openclaw/openclaw

首先安装npm
sudo apt install npm
升级node 22
curl -fsSL https://deb.nodesource.com/setup_22.x | sudo -E bash -
sudo apt install nodejs -y 
或者
sudo apt install nsolid -y


推荐
sudo npm install -g openclaw@latest
openclaw onboard --install-daemon

#Quick start (TL;DR)
Runtime: Node ≥22.

openclaw onboard --install-daemon
//配置大量api--创建飞书app ID， key等


openclaw gateway --port 18789 --verbose

# Send a message
openclaw message send --to +1234567890 --message "Hello from OpenClaw"

# Talk to the assistant (optionally deliver back to any connected channel: WhatsApp/Telegram/Slack/Discord/Google Chat/Signal/iMessage/BlueBubbles/IRC/Microsoft Teams/Matrix/Feishu/LINE/Mattermost/Nextcloud Talk/Nostr/Synology Chat/Tlon/Twitch/Zalo/Zalo Personal/WebChat)
openclaw agent --message "Ship checklist" --thinking high


飞书配置参考
docs.openclaw.ai/zh-CN/channels/feishu
