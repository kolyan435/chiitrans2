# Introduction #

Is the continued development of ChiiTrans (http://code.google.com/p/chiitrans/).

ChiiTrans2 is a software tool that automatically captures text from the game in Japanese and translates it using online services such as Google Translate. Text is captured via AGTH. ChiiTrans2 requires .NET Framework version 3.5.


# Features #

  * Supported online translation services:
    * Google Translate
    * OCN
    * Babylon
    * SysTran
    * Excite
  * Japanese text transliteration support (romaji) via Google Translate.
  * Using WWWJDIC and EDICT to separate and translate individual words.
  * Optional Atlas support. Available if installation of Atlas is detected. Versions V13 and V14 are supported.
  * Optional MeCab support. MeCab is a mophological analyzer for Japanese language. Download link: http://sourceforge.net/projects/mecab/files/.
  * Ability to display furigana (word readings) as hiragana or romaji.
  * Can translate to English, Russian and other languages.
  * Automatic text formatting before translation:
  * Smart remove of duplicate characters (number of characters is detected automatically, executed only if all characters are duplicating).
    * Smart extraction of repeating phrases.
    * User-defined replacement words list with regular expressions syntax support.
    * AGTH: direct text capturing (clipboard is not used). Can monitor multiple contexts.
  * Caching of translation results.
  * Option to enable semi-transparent background (transparent mode) and switch to fullscreen mode for comfortable play.