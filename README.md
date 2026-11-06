# Installers
Installers for Cantokeys software keyboard

For best results, uninstall old version and reboot before installing new version

# Schema

Doudái ha̗i mè le̖i gʌ?

嶺拼到底係咩嚟㗎？

Cantokeys romanization is optimized for touch typing.  It's closest to Jyut6Ping3 but distinguishes high level from high falling tone like Yale and Sidney Lau.  It further differs from most Cantonese romanizations in distinguishing alveolars from alveolo-palatals

## Sibilants

| Alveolar | Pron| Example | Example | Pron | Alveolo-Palatal |
| -------- | -------- | -------- | -------- | -------- | -------- |
| c | cūk | 促 | 觸 | ȼūk | ȼ |
| j |jṟŋ | 漾 | 讓 | ɉṟŋ| ɉ |
| s | sàn | 新 | 身 | ꞩàn | ꞩ |
| z | zó | 左 | 阻 | ƶó | ƶ |

## Compression

### Digraphs

Cantokeys (conventionally) has no digraphs.  It uses the full keyboard for quicker typing and reading.

| Diphthong | Shorthand key | Allograph display | mnemonic |
| -------- | -------- | -------- | -------- |
| aa   | v   | ʌ   | looks like 'A' and 'V' |
| eo   | x   | ɔ   | 'open o' looks like 'e', 'o', and 'u' |
| ng   | q   | ŋ   | has a tail |
| oe   | r   | r   | sounds British |
| yu    | y  | y   | |

Allographs can be displayed (recommended) for legibility, or shorthands can hint the keyboard

### Tones

Tone diacritics visualize pitch and contour

| Diacritic | Tone Number | Tone Class | Description | Pitch-contour | Example honzi̱ | Pronunciation | Definition |
| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| ¯ | 1 | 上陰平，上陰入 | High level | ˥˥  | 紛 | fān | Scatter |
| ´ | 2 | 陰上 | High rising | ˧˥ | 粉 | fán | Powder |
|   | 3 | 陰去，下陰入 | Mid level | ˧˧ | 訓 | fan | Instruct |
| ˎ | 4 | 陽平 | Low falling | ˨˩ | 墳 | fa̖n | Tomb |
| ˏ | 5 | 陽上 | Low rising | ˨˧ | 憤 | fa̗n | Resent | 
| ˍ | 6 | 陽去，上陰入 | Low level | ˨˨ | 份 | fa̱n | Portion |
| ` | 7 | 下陰平 | High falling | ˥˧ | 婚 | fàn | Marriage |

## Optional

Tone changes can be represented by moving the () original tone (- for tone 3) to the end of the syllable

For example:

| 漢字 | Cantokeys |
| -------- | -------- |
| 時間 | ꞩi̖gʌn` |
| 哥哥 | go̖¯gō |

But I have yet to think of a meaningful disambiguation

# Troubleshooting

## I can't install Cantokeys!

No problem, you can still type Cantokeys Romanization!  The Shorthand<=>Allograph mappings make it clear, tones can be written as numbers, and alveolo-palatals can be distinguished with 'h' (Yale could've distinguished 'c' from 'ch')

e.g.

| 漢字 | Conventional | Keyboard-friendly | Sparse |
| -------- | -------- | -------- | -------- | 
| 人渣 | ɉa̖nƶʌ̀ | jhan4zhv7 | jhan4zhaa7 |
| 中彩 | ƶuŋcói | zhuq3coi2 | zhung3coi2 |
| 法律 | fʌtlɔ̱t | fvt3lxt6 | faat3leot6 |
| 船長 | ꞩy̖nƶŕŋ | shyn4zhrq2 | shyun4zhoeng2 |

The keyboard-friendly and sparse versions encode as much information, but less compactly.  Note are similar the sparse text is to standard Jyut6Ping3

Conventional display of allographs, tone diacritics, and alveolo-palatals is distinctive and compact.  It leverages familiar phonetics of English and Jyut6Ping3 with visualization of tone pitch and contour for a script that is recognizably unique.
Cantokeys avoids doubling up diacritics on the same side of a character like Chữ Quốc Ngữ or letters pulling double duty for tone and sound like Yale.
For example, the underlying flat files in Cantokeys are written with stroken consonants, but shorthand keys and tone numbers - but that is for speed and readability in de/serialization algorithms
