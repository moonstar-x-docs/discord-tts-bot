---
hide:
  - navigation
  - toc
---

# Home

!!! info
    This site is still under development and may contain incomplete information.

<center>

![banner](https://i.imgur.com/HT7Wmv1.jpg)

[![discord](https://img.shields.io/discord/730998659008823296.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://discord.gg/mhj3Zsv)
[![ci-build-status](https://img.shields.io/github/workflow/status/moonstar-x/discord-tts-bot/CI?logo=github)](https://github.com/moonstar-x/discord-tts-bot)
[![open-issues-count](https://img.shields.io/github/issues-raw/moonstar-x/discord-tts-bot?logo=github)](https://github.com/moonstar-x/discord-tts-bot)
[![docker-image-size](https://img.shields.io/docker/image-size/moonstarx/discord-tts-bot?logo=docker)](https://hub.docker.com/repository/docker/moonstarx/discord-tts-bot)
[![docker-pulls](https://img.shields.io/docker/pulls/moonstarx/discord-tts-bot?logo=docker)](https://hub.docker.com/repository/docker/moonstarx/discord-tts-bot)
[![ko-fi](https://img.shields.io/badge/buy%20me%20a%20coffee-%E2%98%95%20%20-%23ff5f5f)](https://ko-fi.com/moonstar_x)

</center>

## About

[discord-tts-bot](https://github.com/moonstar-x/discord-tts-bot) is a simple Text-to-Speech bot for Discord with support for multiple languages and Text-to-Speech engines.

This bot was made with utility and fun in mind. It serves as a way for people that either have no mic, or cannot use one, to communicate to everyone else on a voice channel. It also serves as an entertainment tool.

It is better to use this bot instead of the built-in `/tts` command on Discord because:

1. `/tts` may be disabled for certain users, which means that your message may or may not be heard by everyone in the channel.
2. `/tts` requires everyone to have the text channel where the TTS message was sent, to be open, which means once again that your message may not be heard by everyone.
3. You have no control over how `/tts` sounds. The settings `/tts` uses depends on each user, and everyone may hear something completely different depending on their operating system and current settings.

This serves as a way to make sure your TTS message is heard by everyone in the way YOU want.

## Features

* Supports 46 different languages through the `Google Translate Provider`.
* Supports DECTalk (Moonbase Alpha), a voice that sounds similar to how [Stephen Hawking sounded](https://www.youtube.com/watch?v=b-2GV0T5Zpc) through the `Aeiou Provider`.
* Saves the settings for each user so that everyone can have *their own voice* when running the same `/say` command.
* The bot is localized to English, Spanish and French. You can set the preferred language for the bot to use with the `/set_locale` command.
* Supports the definition of *TTS Channels* which will make the bot read out loud any message being sent to the specified *TTS Channel* without the need of using the `/say` command to streamline the usage process.

## Wanna Try it?

[![Invite this bot to your server](https://i.imgur.com/4krikIF.jpg)](https://discord.com/api/oauth2/authorize?client_id=519207945318170654&permissions=3148800&scope=bot%20applications.commands)

## Language Support

This bot supports multiple languages offered by the following Text-to-Speech engines.

### Google Translate Provider

The `Google Translate Provider` offers support for the following languages:

* Afrikaans
* Arabic
* Armenian
* Bengali
* Catalan
* Chinese
* Croatian
* Czech
* Danish
* Dutch
* English
* Filipino
* Finnish
* French
* German
* Greek
* Hindi
* Hungarian
* Icelandic
* Indonesian
* Italian
* Japanese
* Javanese
* Khmer
* Korean
* Latvian
* Malayalam
* Marathi
* Nepali
* Norwegian
* Polish
* Portuguese
* Romanian
* Russian
* Serbian
* Sinhala
* Slovak
* Spanish
* Sundanese
* Swahili
* Swedish
* Tamil
* Telugu
* Thai
* Turkish
* Ukranian
* Vietnamese
