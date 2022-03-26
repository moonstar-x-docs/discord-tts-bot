# Amazon Provider (TTS Tool)

This provider uses the Text-to-Speech functionality available at [TTS Tool](https://ttstool.com). It uses the Amazon voices available from said service.

These voices appear to be some sort of demo of [Amazon Polly](https://aws.amazon.com/polly/) or potentially an older version of its service.

## ℹ️ Source Information

This provider uses a public API exposed by the [TTS Tool](https://ttstool.com) site. It is a web API which means that it is consumed with just an HTTP request. HTTP requests in this project are handled by [axios](https://www.npmjs.com/package/axios).

## 🌎 Language Support

The provider offers support for the following languages:

| Language                       | Language Code | Command                         |
|--------------------------------|---------------|---------------------------------|
| :flag_us: American English     | en            | `/amazon_set_my language en`    |
| :flag_au: Australian English   | en-au         | `/amazon_set_my language en-au` |
| :flag_br: Brazilian Portuguese | pt-br         | `/amazon_set_my language pt-br` |
| :flag_gb: British English      | en-gb         | `/amazon_set_my language en-gb` |
| :flag_ca: Canadian French      | fr-ca         | `/amazon_set_my language fr-ca` |
| :flag_dk: Danish               | da            | `/amazon_set_my language da`    |
| :flag_nl: Dutch                | nl            | `/amazon_set_my language nl`    |
| :flag_fr: French               | fr            | `/amazon_set_my language fr`    |
| :flag_de: German               | de            | `/amazon_set_my language de`    |
| :flag_is: Icelandic            | is            | `/amazon_set_my language is`    |
| :flag_in: Indian English       | en-in         | `/amazon_set_my language en-in` |
| :flag_it: Italian              | it            | `/amazon_set_my language it`    |
| :flag_mx: Mexican Spanish      | es-mx         | `/amazon_set_my language es-mx` |
| :flag_no: Norwegian            | nb            | `/amazon_set_my language nb`    |
| :flag_pl: Polish               | pl            | `/amazon_set_my language pl`    |
| :flag_pt: Portuguese           | pt            | `/amazon_set_my language pt`    |
| :flag_ro: Romanian             | ro            | `/amazon_set_my language ro`    |
| :flag_ru: Russian              | ru            | `/amazon_set_my language ru`    |
| :flag_es: Spanish              | es            | `/amazon_set_my language es`    |
| :flag_se: Swedish              | sv            | `/amazon_set_my language sv`    |
| :flag_tr: Turkish              | tr            | `/amazon_set_my language tr`    |
| :wales: Welsh                  | cy            | `/amazon_set_my language cy`    |

### 🗣 Available Voices

Here's a list of all the available voices for each language:

| Language                       | Voice Name        | Command                          |
|--------------------------------|-------------------|----------------------------------|
| :flag_us: American English     | :woman: Salli     | `/amazon_set_my voice Salli`     |
| :flag_us: American English     | :man: Joey        | `/amazon_set_my voice Joey`      |
| :flag_us: American English     | :woman: Kendra    | `/amazon_set_my voice Kendra`    |
| :flag_us: American English     | :woman: Kimberly  | `/amazon_set_my voice Kimberly`  |
| :flag_us: American English     | :woman: Ivy       | `/amazon_set_my voice Ivy`       |
| :flag_us: American English     | :man: Justin      | `/amazon_set_my voice Justin`    |
| :flag_au: Australian English   | :woman: Nicole    | `/amazon_set_my voice Nicole`    |
| :flag_au: Australian English   | :man: Russell     | `/amazon_set_my voice Russell`   |
| :flag_br: Brazilian Portuguese | :woman: Vitoria   | `/amazon_set_my voice Vitoria`   |
| :flag_br: Brazilian Portuguese | :man: Ricardo     | `/amazon_set_my voice Ricardo`   |
| :flag_gb: British English      | :woman: Amy       | `/amazon_set_my voice Amy`       |
| :flag_gb: British English      | :man: Brian       | `/amazon_set_my voice Brian`     |
| :flag_gb: British English      | :woman: Emma      | `/amazon_set_my voice Emma`      |
| :flag_ca: Canadian French      | :woman: Chantal   | `/amazon_set_my voice Chantal`   |
| :flag_dk: Danish               | :man: Mads        | `/amazon_set_my voice Mads`      |
| :flag_dk: Danish               | :woman: Naja      | `/amazon_set_my voice Naja`      |
| :flag_nl: Dutch                | :woman: Lotte     | `/amazon_set_my voice Lotte`     |
| :flag_nl: Dutch                | :man: Ruben       | `/amazon_set_my voice Ruben`     |
| :flag_fr: French               | :woman: Celine    | `/amazon_set_my voice Celine`    |
| :flag_fr: French               | :man: Mathieu     | `/amazon_set_my voice Mathieu`   |
| :flag_de: German               | :woman: Marlene   | `/amazon_set_my voice Marlene`   |
| :flag_de: German               | :man: Hans        | `/amazon_set_my voice Hans`      |
| :flag_is: Icelandic            | :woman: Dora      | `/amazon_set_my voice Dora`      |
| :flag_is: Icelandic            | :man: Karl        | `/amazon_set_my voice Karl`      |
| :flag_in: Indian English       | :woman: Raveena   | `/amazon_set_my voice Raveena`   |
| :flag_it: Italian              | :woman: Carla     | `/amazon_set_my voice Carla`     |
| :flag_it: Italian              | :man: Giorgio     | `/amazon_set_my voice Giorgio`   |
| :flag_mx: Mexican Spanish      | :woman: Penelope  | `/amazon_set_my voice Penelope`  |
| :flag_mx: Mexican Spanish      | :man: Miguel      | `/amazon_set_my voice Miguel`    |
| :flag_no: Norwegian            | :woman: Liv       | `/amazon_set_my voice Liv`       |
| :flag_pl: Polish               | :woman: Ewa       | `/amazon_set_my voice Ewa`       |
| :flag_pl: Polish               | :man: Jacek       | `/amazon_set_my voice Jacek`     |
| :flag_pl: Polish               | :woman: Maja      | `/amazon_set_my voice Maja`      |
| :flag_pl: Polish               | :man: Jan         | `/amazon_set_my voice Jan`       |
| :flag_pt: Portuguese           | :man: Cristiano   | `/amazon_set_my voice Cristiano` |
| :flag_pt: Portuguese           | :woman: Ines      | `/amazon_set_my voice Ines`      |
| :flag_ro: Romanian             | :woman: Carmen    | `/amazon_set_my voice Carmen`    |
| :flag_ru: Russian              | :woman: Tatyana   | `/amazon_set_my voice Tatyana`   |
| :flag_ru: Russian              | :man: Maxim       | `/amazon_set_my voice Maxim`     |
| :flag_es: Spanish              | :woman: Conchita  | `/amazon_set_my voice Conchita`  |
| :flag_es: Spanish              | :man: Enrique     | `/amazon_set_my voice Enrique`   |
| :flag_se: Swedish              | :woman: Astrid    | `/amazon_set_my voice Astrid`    |
| :flag_tr: Turkish              | :woman: Filiz     | `/amazon_set_my voice Filiz`     |
| :wales: Welsh                  | :woman: Gwyneth   | `/amazon_set_my voice Gwyneth`   |
| :wales: Welsh                  | :man: Geraint     | `/amazon_set_my voice Geraint`   |

## ⌨️ Source Code

If you're interested in seeing how this provider works, you can head over to the [AmazonProvider.js](https://github.com/moonstar-x/discord-tts-bot/blob/master/src/classes/tts/providers/AmazonProvider.js) file in the repo, or check this embed.

<script src="https://emgithub.com/embed.js?target=https%3A%2F%2Fgithub.com%2Fmoonstar-x%2Fdiscord-tts-bot%2Fblob%2Fmaster%2Fsrc%2Fclasses%2Ftts%2Fproviders%2FAmazonProvider.js&style=github-gist&showBorder=on&showLineNumbers=on&showFileMeta=on&showCopy=on&fetchFromJsDelivr=on"></script>
