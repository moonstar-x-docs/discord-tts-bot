# /google_set_channel

## 📖 Description

Sets the settings to be used by the message-only based TTS channel with the [Google Translate Provider](../../../text-to-speech-providers/google-translate.md).

Run this command inside the channel you wish to change the settings for. Make sure to have set the TTS channel provider to [Google Translate Provider](../../../text-to-speech-providers/google-translate.md) by running the [/set_channel_provider](../config/set-channel-provider.md) command inside the same channel.

Message-only based TTS bypasses the settings saved for the server or the user, it uses its own custom settings.

You can change the settings for any channel, just run this command inside that channel.

## ❓ Can Be Used By

Can only be used by users with the `MANAGE_CHANNELS` permission.

## 🌎 Subcommand: `language`

### 🔨 Parameters

Running this command requires the following parameters:

* `<value>` - **Required**: The language code to use as the [Google Translate Provider](../../../text-to-speech-providers/google-translate.md) language for the channel.

### 🎈 Usage

You can run this command by typing:

```text
/google_set_channel language <value>
```

For example:

![google-set-channel-language-usage](../../../assets/screenshots/google-set-channel-language-usage.png)

## 🏃🏻 Subcommand: `speed`

### 🔨 Parameters

Running this command requires the following parameters:

* `<value>` - **Required**: The speed to use as the [Google Translate Provider](../../../text-to-speech-providers/google-translate.md) speed for the channel. You can choose any of the suggested values when running the command.

### 🎈 Usage

You can run this command by typing:

```text
/google_set_channel speed <value>
```

For example:

![google-set-channel-speed-usage](../../../assets/screenshots/google-set-channel-speed-usage.png)

## ℹ️ Other Information

Some extra information to take into account:

* [x] Can only be run from a server.
* [ ] Can only be run from a NSFW channel.
* [x] Saves data from the user.
    - [x] Saves the settings for the [Google Translate Provider](../../../text-to-speech-providers/google-translate.md) for the channel where the command was run.
