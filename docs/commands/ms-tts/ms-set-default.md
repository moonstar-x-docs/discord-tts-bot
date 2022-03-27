# /ms_set_default

## 📖 Description

Sets the settings to be used by the [/say](../all-tts/say.md) and [/ms_say](./ms-say.md) commands by default. Default settings are used for people who have not set their own settings for the [Microsoft Provider (TTS Tool)](../../text-to-speech-providers/microsoft-ttstool.md).

If you're seeking to change your own settings for this provider, you should use [/ms_set_my](./ms-set-my.md).

## ❓ Can Be Used By

Can only be used by users with the `MANAGE_GUILD` permission.

## 🌎 Subcommand: `language`

### 🔨 Parameters

Running this command requires the following parameters:

* `<value>` - **Required**: The language code to use as the default [Microsoft Provider (TTS Tool)](../../text-to-speech-providers/microsoft-ttstool.md) language.

### 🎈 Usage

You can run this command by typing:

```text
/ms_set_default language <value>
```

For example:

![ms-set-default-language-usage](../../assets/screenshots/ms-set-default-language-usage.png)

## 🗣 Subcommand: `voice`

### 🔨 Parameters

Running this command requires the following parameters:

* `<value>` - **Required**: The name of the voice to be used as the default [Microsoft Provider (TTS Tool)](../../text-to-speech-providers/microsoft-ttstool.md) voice.

### 🎈 Usage

You can run this command by typing:

```text
/ms_set_default voice <value>
```

For example:

![ms-set-default-voice-usage](../../assets/screenshots/ms-set-default-voice-usage.png)

## 🔊 Subcommand: `volume`

### 🔨 Parameters

Running this command requires the following parameters:

* `<value>` - **Required**: The volume to use as the default [Microsoft Provider (TTS Tool)](../../text-to-speech-providers/microsoft-ttstool.md) volume. You can choose any of the suggested values when running the command.

### 🎈 Usage

You can run this command by typing:

```text
/ms_set_default volume <value>
```

For example:

![ms-set-default-volume-usage](../../assets/screenshots/ms-set-default-volume-usage.png)

## 🏃🏻 Subcommand: `rate`

### 🔨 Parameters

Running this command requires the following parameters:

* `<value>` - **Required**: The rate to use as the default [Microsoft Provider (TTS Tool)](../../text-to-speech-providers/microsoft-ttstool.md) rate. You can choose any of the suggested values when running the command.

### 🎈 Usage

You can run this command by typing:

```text
/ms_set_default rate <value>
```

For example:

![ms-set-default-rate-usage](../../assets/screenshots/ms-set-default-rate-usage.png)

## 🥁 Subcommand: `pitch`

### 🔨 Parameters

Running this command requires the following parameters:

* `<value>` - **Required**: The pitch to use as the default [Microsoft Provider (TTS Tool)](../../text-to-speech-providers/microsoft-ttstool.md) pitch. You can choose any of the suggested values when running the command.

### 🎈 Usage

You can run this command by typing:

```text
/ms_set_default pitch <value>
```

For example:

![ms-set-default-pitch-usage](../../assets/screenshots/ms-set-default-pitch-usage.png)

## ℹ️ Other Information

Some extra information to take into account:

* [x] Can only be run from a server.
* [ ] Can only be run from a NSFW channel.
* [x] Saves data from the user.
    - [x] Saves the default settings for the [Microsoft Provider (TTS Tool)](../../text-to-speech-providers/microsoft-ttstool.md) for the server.
