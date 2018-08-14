<h1 align="center">
  <br>
  <a href="https://github.com/ChaoticWeg/discord.sh"><img src="https://i.imgur.com/xZ8r3N0.png" alt="discord.sh"></a>
  <br>
  <code>discord.sh</code>
  <br>
  <br>
</h1>

Write-only command-line integration for Discord webhooks, written in 100% Bash script. Influenced heavily by [slack-cli][slack].

[![Travis (.org) branch](https://img.shields.io/travis/ChaoticWeg/discord.sh/master.svg)](https://travis-ci.org/ChaoticWeg/discord.sh)

### Dependencies

- [curl]() (http requests)
- [bats]() (tests)

### Usage

1. [Set up a webhook][webhook] in the desired Discord text channel
2. Download (or clone) a copy of `discord.sh`
3. Create a file called `.webhook` in the same directory as `discord.sh` *
4. Copy and paste the webhook URL from Discord into `.webhook`
5. Go nuts.

\* Or you can pass the webhook URL via `--webhook-url`.

^ Subject to change through the course of development.

[slack]: https://github.com/rockymadden/slack-cli/
[curl]: https://curl.haxx.se/
[bats]: https://github.com/sstephenson/bats
[webhook]: https://support.discordapp.com/hc/en-us/articles/228383668-Intro-to-Webhooks
