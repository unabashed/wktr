# wktr

> Translate at the command line using Wiktionary's translations.

## What does it do?
Wiktionary normally has a table of translation of a word or expression in other languages. This script looks this up for you. 

## Usage
`wktr [lang_origin] [lang_destination] terms`

## Examples
Try this for English-to-Estonian translations:
`wktr en et apple keyboard "thank you"`

```bash
[en] apple        [et] õun
[en] keyboard     [et] klaviatuur
[en] thank you    [et] aitäh ·· aitüma ·· tänan ·· täname
```

Try this for English-to-Japanese translations:
`wktr en ja melon ice sushi`

```bash
[en] melon    [ja] メロン
[en] ice      [ja] 氷 ·· アイス ·· ドライアイス ·· アイス ·· アイス ·· 凍る
[en] sushi    [ja] 鮨 ·· 鮓 ·· 寿司 ·· すし
```

## Limitations
Doesn't behave well with some languages with different dialects, like Chinese.

## Dependencies
Must have `curl` and `xsel` installed. Try:
`sudo apt-get install curl xsel`

