# /amazon_set_channel

## 📖 Description

Sets the settings to be used by the message-only based TTS channel with the [Amazon Provider (TTS Tool)](../../../text-to-speech-providers/amazon-ttstool.md).

Run this command inside the channel you wish to change the settings for. Make sure to have set the TTS channel provider to [Amazon Provider (TTS Tool)](../../../text-to-speech-providers/amazon-ttstool.md) by running the [/set_channel_provider](../config/set-channel-provider.md) command inside the same channel.

Message-only based TTS bypasses the settings saved for the server or the user, it uses its own custom settings.

You can change the settings for any channel, just run this command inside that channel.

## ❓ Can Be Used By

Can only be used by users with the `MANAGE_CHANNELS` permission.

## 🌎 Subcommand: `language`

### 🔨 Parameters

Running this command requires the following parameters:

* `<value>` - **Required**: The language code to use as the [Amazon Provider (TTS Tool)](../../../text-to-speech-providers/amazon-ttstool.md) language for the channel.

### 🎈 Usage

You can run this command by typing:

```text
/amazon_set_channel language <value>
```

For example:

![amazon-set-channel-language-usage](../../../assets/screenshots/amazon-set-channel-language-usage.png)

## 🗣 Subcommand: `voice`

### 🔨 Parameters

Running this command requires the following parameters:

* `<value>` - **Required**: The name of the voice to be used as the [Amazon Provider (TTS Tool)](../../../text-to-speech-providers/amazon-ttstool.md) voice for the channel.

### 🎈 Usage

You can run this command by typing:

```text
/amazon_set_channel voice <value>
```

For example:

![amazon-set-channel-voice-usage](../../../assets/screenshots/amazon-set-channel-voice-usage.png)

## 🔊 Subcommand: `volume`

### 🔨 Parameters

Running this command requires the following parameters:

* `<value>` - **Required**: The volume to use as the [Amazon Provider (TTS Tool)](../../../text-to-speech-providers/amazon-ttstool.md) volume for the channel. You can choose any of the suggested values when running the command.

### 🎈 Usage

You can run this command by typing:

```text
/amazon_set_channel volume <value>
```

For example:

![amazon-set-channel-volume-usage](../../../assets/screenshots/amazon-set-channel-volume-usage.png)

## 🏃🏻 Subcommand: `rate`

### 🔨 Parameters

Running this command requires the following parameters:

* `<value>` - **Required**: The rate to use as the [Amazon Provider (TTS Tool)](../../../text-to-speech-providers/amazon-ttstool.md) rate for the channel. You can choose any of the suggested values when running the command.

### 🎈 Usage

You can run this command by typing:

```text
/amazon_set_channel rate <value>
```

For example:

![amazon-set-channel-rate-usage](../../../assets/screenshots/amazon-set-channel-rate-usage.png)

## 🥁 Subcommand: `pitch`

### 🔨 Parameters

Running this command requires the following parameters:

* `<value>` - **Required**: The pitch to use as the [Amazon Provider (TTS Tool)](../../../text-to-speech-providers/amazon-ttstool.md) pitch for the channel. You can choose any of the suggested values when running the command.

### 🎈 Usage

You can run this command by typing:

```text
/amazon_set_channel pitch <value>
```

For example:

![amazon-set-channel-pitch-usage](../../../assets/screenshots/amazon-set-channel-pitch-usage.png)

## ℹ️ Other Information

Some extra information to take into account:

* [x] Can only be run from a server.
* [ ] Can only be run from a NSFW channel.
* [x] Saves data from the user.
    - [x] Saves the settings for the [Amazon Provider (TTS Tool)](../../../text-to-speech-providers/amazon-ttstool.md) for the channel where the command was run.
