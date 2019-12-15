<p align="center">
  <a href="https://t.me/alilendbot">
      <img src="https://avatars2.githubusercontent.com/u/51444903?s=400&u=1a0f8aeed59a74add6a83b1f3b57815aca7033ae&v=4" width="200">
  </a>
</p>

# Alilend Telegram bot

This is the code for the Telegram bot — [@alilendbot](https://t.me/alilendbot), that automated news feed about interesting and discount goods from Aliexpress.


# Installation and local launch

1. Clone this repo: `git clone https://github.com/Kiku-Reise/alilend`
2. Create `.env` with the environment variables listed below
3. Run `yarn install` in the root folder
4. Run `yarn develop`

And you should be good to go! Feel free to fork and submit pull requests. Thanks!

# Environment variables

- `TOKEN` — Telegram bot token
- `CHANNEL_HANDLE` — Handle of the Telegram ad channel
- `CHANNEL_ID` — ID of the Telegram ad channel

Bot should be admin at `CHANNEL_ID`.
Also, please, consider looking at `.env.sample`.

# License

MIT — use for any purpose. Would be great if you could leave a note about the original developers. Thanks!
