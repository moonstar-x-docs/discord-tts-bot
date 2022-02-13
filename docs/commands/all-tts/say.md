# /say

!!! info "Aliases"
    You can also use the following as an alias for this command:

    * `/s`

## 📖 Description

Send a Text-to-Speech message in your voice channel with your own settings or the ones saved for this server.

You can configure your own TTS provider by using the [/set_my_provider](../config/set-my-provider.md) command and change its settings (if applies) with the appropriate command. For example, for the [Google Translate Provider](../../text-to-speech-providers/google-translate.md) you may run [/google_set_my](../google-tts/google-set-my.md), some providers may not have settings associated to them.

Similarly, if you wish to set the TTS provider to be used by default on your server (for people who have not set their own settings before), you may use the [/set_default_provider](../config/set-default-provider.md) command and follow the same logic with the *set_default* kind of command for the respective TTS provider.

If you insert a mention to a user, channel or role, the bot will read-out the name of the mentioned entity. Also, when using a custom emoji, the bot will read its name.

!!! warning "Keep in Mind"
    Regular emojis may be read differently depending on the TTS provider. Some providers may not support emojis altogether such as the [Aeiou Provider](../../text-to-speech-providers/aeiou.md).

## ❓ Can Be Used By

Can be used by anyone in the server. You need to be inside a voice channel before to be able to *say* something.

Make sure that the bot has enough permissions to connect and speak in your voice channel.

## 🔨 Parameters

Running this command requires the following parameters:

* `<message>` - **Required**: The message to *say* in your voice channel.

## 🎈 Usage

You can run this command by typing:

```text
/say <message>
```

For example:

![say-usage](../../assets/screenshots/say-usage.png)

## ℹ️ Other Information

Some extra information to take into account:

* [x] Can only be run from a server.
* [ ] Can only be run from a NSFW channel.
* [ ] Saves data from the user.
