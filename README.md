# flod
Telegram bot, which for a time activates offtop mode in chat.
# Flod

This is the code for the Telegram bot — [@flodbot](https://t.me/flodbot), which for a time activates offtop mode in chat.

# Installation and local launch

1. Clone this repo: `git clone https://github.com/kiku-git/flod`
2. Create `.env` with the environment variables listed below
3. Run `yarn install` in the root folder
4. Run `yarn distribute`

And you should be good to go! Feel free to fork and submit pull requests. Thanks!

# Environment variables

- `USERNAME` — Telegram bot username
- `TOKEN` — Telegram bot token
- `CHANNEL_HANDLE` — Handle of the Telegram ad channel
- `CHANNEL_ID` — ID of the Telegram ad channel

Bot should be admin at `CHANNEL_ID`.
Also, please, consider looking at `.env.sample`.

# License

MIT — use for any purpose. Would be great if you could leave a note about the original developers. Thanks!
