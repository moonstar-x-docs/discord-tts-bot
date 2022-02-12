# /set_my_provider

## 📖 Description

Sets the provider to be used for yourself. This is used by the [/say](../all-tts/say.md) command.

If you're looking to configure the default TTS provider to be used by the server, use [/set_default_provider](./set-default-provider.md).

## ❓ Can Be Used By

Can be used by anyone in the server.

## 🔨 Parameters

Running this command requires the following parameters:

* `<provider>` - **Required**: The name of the provider to use. You can choose any of the suggested values when running the command.

## 🎈 Usage

You can run this command by typing:

```text
/set_my_provider <provider>
```

For example:

![set-my-provider-usage](../../assets/screenshots/set-my-provider-usage.png)

## ℹ️ Other Information

Some extra information to take into account:

* [x] Can only be run from a server.
* [ ] Can only be run from a NSFW channel.
* [x] Saves data from the user.
    * [x] Saves the provider to be used for the user.
