# Introduction

This section contains a list of all TTS channel commands.

These commands will be registered only if:

* `enable_tts_channels` is set to `true` in the `settings.json` file.

Or,

* `DISCORD_ENABLE_TTS_CHANNELS` is set to `true` in the environment variables.

!!! warning "Keep in Mind"
    In the official bot instance, these commands are not available. This is due to the fact that those commands require the `GUILD_MESSAGES` privileged intent, which is easily available to unverified bots. For verified bots (which is the case of the official bot), an application is necessary to justify the need to access this privileged intent.
