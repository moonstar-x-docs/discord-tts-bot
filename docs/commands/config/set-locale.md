# /set_locale

## 📖 Description

Sets the locale to be used by the bot on the server.

!!! note
    A locale means the language that the bot will use to write text (message replies). Not everything can be translated due to technical limitations.

### 🌎 Supported Locales

Here's a list of the locales supported by the bot:

* English
* Spanish (Español)
* French (Français)

## ❓ Can Be Used By

Can only be used by users with the `MANAGE_GUILD` permission.

## 🔨 Parameters

Running this command requires the following parameters:

* `<locale>` - **Required**: The name of the locale to use for the server. You can choose any of the suggested values when running the command.

## 🎈 Usage

You can run this command by typing:

```text
/set_locale <locale>
```

For example:

![set-locale-usage](../../assets/screenshots/set-locale-usage.png)

## ℹ️ Other Information

Some extra information to take into account:

* [x] Can only be run from a server.
* [ ] Can only be run from a NSFW channel.
* [x] Saves data from the user.
    * [x] Saves the locale to be used for the server.
