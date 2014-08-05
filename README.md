wp-languages
============

A collection of WordPress core translations for multilingual site development, testing, and production.

This project contains .po and .mo files for WordPress in (hopefully) all available languages.

## Installation

Copy the languages you need into the directory `wp-content/languages` on your server. If you installed WordPress in English, you'll need to create the `languages` folder inside `wp-content` first. Alternatively, clone this repository directly into that folder to get all languages and updates.

Open wp-config.php and find the following line:

	define ('WPLANG', '');

Change the second part to your locale. For example, to get WordPress in Japanese:

	define ('WPLANG', 'ja');

Note: the locale should be 2 lowercase letters for the language, optionally followed by an undercore and 2 uppercase letters for the region. For example, Portuguese (Brasil) would be pt_BR.

## Available Languages
* English – English ( en_US )
* English (Australia) - English ( en_AU )
* English (Canada) - English ( en_CA )
* English (UK) - English ( en_GB )
* Albanian - Shqip ( sq )
* Arabic – العربية ( ar )
* Armenian – Հայերեն ( hy )
* Azerbaijani - Azərbaycan dili ( az )
* Basque - Euskara ( eu )
* Bengali - বাংলা ( bn_BD )
* Bosnian - Bosanski ( bs_BA )
* Bulgarian – Български ( bg_BG )
* Catalan - Català ( ca )
* Central Kurdish - وۆردپرێس بەکوردی ( ckb )
* Chinese (China) - 简体中文 ( zh_CN )
* Chinese (Taiwan) - 正體中文 ( zh_TW )
* Croatian – Hrvatski ( hr )
* Czech - Čeština ( cs_CZ )
* Danish - Dansk ( da_DK )
* Dutch - Nederlands ( nl_NL )
* Esperanto - Esperanto ( eo )
* Estonian - Eesti ( et )
* Finnish – Suomi ( fi )
* French – Français ( fr_FR )
* Frisian - Frysk ( fy )
* Galician - Galego ( gl_ES )
* German – Deutsch ( de_DE )
* Greek - Ελληνικά ( el )
* Hebrew - עִבְרִית ( he_IL )
* Hungarian - Magyar ( hu_HU )
* Indonesian - Bahasa Indonesia ( id_ID )
* Islandic - Íslenska ( is_IS )
* Italian – Italiano ( it_IT )
* Japanese – 日本語 ( ja )
* Javanese - Jawa ( jv_ID )
* Kannada - ಕನ್ನಡ ( kn )
* Kazakh - Қазақша ( kk )
* Korean - 한국어 ( ko_KR )
* Kyrgyz - Кыргызча ( ky_KY )
* Latvian - Latviešu valodā ( lv )
* Macedonian - Македонски ( mk_MK )
* Malay - Bahasa Melayu ( ms_MY )
* Montenegrin - Crnogorski ( me_ME )
* Norwegian Bokmål - Norsk bokmål ( nb_NO )
* Norwegian Nynorsk - Norsk nynorsk ( nn_NO )
* Ossetian - Ирон ( os )
* Persian - فارسی ( fa_IR )
* Polish – Polski ( pl_PL )
* Portuguese (Brazil) – Português do Brasil ( pt_BR )
* Portuguese (Portugal) – Português ( pt_PT )
* Romanian - Română ( ro_RO )
* Russian - Русский ( ru_RU )
* Scottish Gaelic - Gàidhlig ( gd )
* Serbian - Српски ( sr_RS )
* Sinhala - සිංහල ( si_LK )
* Slovak - Slovenský jazyk ( sk_SK )
* Slovenian – Slovenija ( sl_SI )
* Spanish – Español ( es_ES )
* Spanish (Chile) – Español ( es_CL )
* Spanish (México) – Español ( es_MX )
* Spanish (Perú) – Español ( es_PE )
* Spanish (Venezuela) – Español ( es_VE )
* Sundanese - Basa Sunda ( su_ID )
* Swahili - Kiswahili ( sw )
* Swedish – Svenska ( sv_SE )
* Tagalog - Tagalog ( tl )
* Telugu - తెలుగు ( te )
* Thai - ภาษาไทย ( th )
* Turkish - Türkçe ( tr_TR )
* Ukrainian - Україна ( uk )
* Urdu - اردو ( ur )
* Vietnamese - tiếng Việt ( vi )
* Welsh - Cymraeg ( cy )

Visit http://i18n.svn.wordpress.org/ for the latest official translations of WordPress.