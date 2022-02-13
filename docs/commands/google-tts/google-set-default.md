# /google_set_default

## 📖 Description

Sets the settings to be used by the [/say](../all-tts/say.md) and [/google_say](./google-say.md) commands by default. Default settings are used for people who have not set their own settings for the [Google Translate Provider](../../text-to-speech-providers/google-translate.md).

If you're seeking to change your own settings for this provider, you should use [/google_set_my](./google-set-my.md).

## ❓ Can Be Used By

Can only be used by users with the `MANAGE_GUILD` permission.

## 🌎 Subcommand: `language`

### 🔨 Parameters

Running this command requires the following parameters:

* `<value>` - **Required**: The language code to use as the default [Google Translate Provider](../../text-to-speech-providers/google-translate.md) language.

### 🎈 Usage

You can run this command by typing:

```text
/google_set_default language <value>
```

For example:

![google-set-default-language-usage](../../assets/screenshots/google-set-default-language-usage.png)

## 🏃🏻 Subcommand: `speed`

### 🔨 Parameters

Running this command requires the following parameters:

* `<value>` - **Required**: The speed to use as the default [Google Translate Provider](../../text-to-speech-providers/google-translate.md) speed. You can choose any of the suggested values when running the command.

### 🎈 Usage

You can run this command by typing:

```text
/google_set_default speed <value>
```

For example:

![google-set-default-speed-usage](../../assets/screenshots/google-set-default-speed-usage.png)

## ℹ️ Other Information

Some extra information to take into account:

* [x] Can only be run from a server.
* [ ] Can only be run from a NSFW channel.
* [x] Saves data from the user.
    - [x] Saves the default settings for the [Google Translate Provider](../../text-to-speech-providers/google-translate.md) for the server.
