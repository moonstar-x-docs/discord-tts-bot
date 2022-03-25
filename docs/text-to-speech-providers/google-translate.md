# Google Translate Provider

This provider uses the Text-to-Speech functionality from Google Translate. Not to be confused with [Cloud Text-to-Speech](https://cloud.google.com/text-to-speech) from Google Cloud.

## ℹ️ Source Information

This provider uses the library [google-tts](https://www.npmjs.com/package/google-tts-api) which creates the Google Translate URLs with the TTS stream based on the message. This library is unofficial.

## 🌎 Language Support

This provider offers support for the following languages:

| Language              | Language Code | Command                       |
|-----------------------|---------------|-------------------------------|
| :flag_za: Afrikaans   | af            | `/google_set_my language af`  |
| :flag_sa: Arabic      | ar            | `/google_set_my language ar`  |
| :flag_am: Armenian    | hy            | `/google_set_my language hy`  |
| :flag_bd: Bengali     | bn            | `/google_set_my language bn`  |
| :flag_es: Catalan     | ca            | `/google_set_my language ca`  |
| :flag_cn: Chinese     | cmn           | `/google_set_my language cmn` |
| :flag_hr: Croatian    | hr            | `/google_set_my language hr`  |
| :flag_cz: Czech       | cs            | `/google_set_my language cs`  |
| :flag_dk: Danish      | da            | `/google_set_my language da`  |
| :flag_nl: Dutch       | nl            | `/google_set_my language nl`  |
| :flag_us: English     | en            | `/google_set_my language en`  |
| :flag_ph: Filipino    | fil           | `/google_set_my language fil` |
| :flag_fi: Finnish     | fi            | `/google_set_my language fi`  |
| :flag_fr: French      | fr            | `/google_set_my language fr`  |
| :flag_de: German      | de            | `/google_set_my language de`  |
| :flag_gr: Greek       | el            | `/google_set_my language el`  |
| :flag_id: Hindi       | hi            | `/google_set_my language hi`  |
| :flag_hu: Hungarian   | hu            | `/google_set_my language hu`  |
| :flag_is: Icelandic   | is            | `/google_set_my language is`  |
| :flag_id: Indonesian  | id            | `/google_set_my language id`  |
| :flag_it: Italian     | it            | `/google_set_my language it`  |
| :flag_jp: Japanese    | ja            | `/google_set_my language ja`  |
| :flag_id: Javanese    | jv            | `/google_set_my language jv`  |
| :flag_kh: Khmer       | km            | `/google_set_my language km`  |
| :flag_kr: Korean      | ko            | `/google_set_my language ko`  |
| :flag_lv: Latvian     | lv            | `/google_set_my language lv`  |
| :flag_my: Malayalam   | ml            | `/google_set_my language ml`  |
| :flag_in: Marathi     | mr            | `/google_set_my language mr`  |
| :flag_np: Nepali      | ne            | `/google_set_my language ne`  |
| :flag_no: Norwegian   | nb            | `/google_set_my language nb`  |
| :flag_pl: Polish      | pl            | `/google_set_my language pl`  |
| :flag_pt: Portuguese  | pt            | `/google_set_my language pt`  |
| :flag_ro: Romanian    | ro            | `/google_set_my language ro`  |
| :flag_ru: Russian     | ru            | `/google_set_my language ru`  |
| :flag_rs: Serbian     | sr            | `/google_set_my language sr`  |
| :flag_lk: Sinhala     | si            | `/google_set_my language si`  |
| :flag_sk: Slovak      | sk            | `/google_set_my language sk`  |
| :flag_es: Spanish     | es            | `/google_set_my language es`  |
| :flag_id: Sundanese   | su            | `/google_set_my language su`  |
| :flag_tz: Swahili     | sw            | `/google_set_my language sw`  |
| :flag_se: Swedish     | sv            | `/google_set_my language sv`  |
| :flag_in: Tamil       | ta            | `/google_set_my language ta`  |
| :flag_in: Telugu      | te            | `/google_set_my language te`  |
| :flag_th: Thai        | th            | `/google_set_my language th`  |
| :flag_tr: Turkish     | tr            | `/google_set_my language tr`  |
| :flag_ua: Ukranian    | uk            | `/google_set_my language uk`  |
| :flag_vn: Vietnamese  | vi            | `/google_set_my language vi`  |

## ⌨️ Source Code

If you're interested in seeing how this provider works, you can head over to the [GoogleProvider.js](https://github.com/moonstar-x/discord-tts-bot/blob/master/src/classes/tts/providers/GoogleProvider.js) file in the repo, or check this embed.

<script src="https://emgithub.com/embed.js?target=https%3A%2F%2Fgithub.com%2Fmoonstar-x%2Fdiscord-tts-bot%2Fblob%2Fmaster%2Fsrc%2Fclasses%2Ftts%2Fproviders%2FGoogleProvider.js&style=github-gist&showBorder=on&showLineNumbers=on&showFileMeta=on&showCopy=on&fetchFromJsDelivr=on"></script>
