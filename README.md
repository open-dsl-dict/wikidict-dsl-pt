# wikidict-dsl-pt - Wikidata Bilingual DSL Dictionaries (Portuguese)

This repository makes available a collection of bilingual Portuguese dictionaries in DSL format derived from interwiki links (links between article titles in different languages) in Wikipedia. The data has been extracted from [Wikidata](https://www.wikidata.org/).

## Format

ABBYY Lingvo DSL is a flexible dictionary format that can be read by dictionary applications such as [Goldendict](https://github.com/goldendict/goldendict) and converted to other formats using tools such as [pyglossary](https://github.com/ilius/pyglossary). There are also a number of tools for creating DSL format dictionaries available in the [dsl-tools](https://github.com/dohliam/dsl-tools) project.

DSL files *must* be saved as UTF-16 to be usable by dictionary programs. The raw source files in this repository are saved in UTF-8 format, which is both significantly smaller in terms of file size, and also readable (and diffable) by git. However, there are fully encoded and compressed `.dsl.dz` dictionaries ready for use available in the [Releases](https://github.com/open-dsl-dict/wikidict-dsl-pt/releases) section.

You can also use the `rezip_dsl.rb` and `unzip_dsl.rb` [scripts](https://github.com/dohliam/dsl-tools/tree/master/zip_unzip) provided by the [dsl-tools](https://github.com/dohliam/dsl-tools) repo to encode/compress and decode/uncompress the dictionaries either individually or as a group.

## Data

The data directory contains the bilingual dictionaries in pairs according to [ISO language code](http://en.wikipedia.org/wiki/ISO_639-1).

The basic filename pattern is `[ISO]-pt_wikidict.dsl`, with `[ISO]` being the source language ISO code. A list of all language pairs is [below](#available-language-pairs).

## Available language pairs

Language codes | Language names
-------------- | --------------
`af-pt` | Afrikaans => Portuguese
`am-pt` | Amharic => Portuguese
`ang-pt` | Anglo-Saxon => Portuguese
`ar-pt` | Arabic => Portuguese
`arc-pt` | Aramaic => Portuguese
`bg-pt` | Bulgarian => Portuguese
`bi-pt` | Bislama => Portuguese
`bn-pt` | Bengali => Portuguese
`bo-pt` | Tibetan => Portuguese
`br-pt` | Breton => Portuguese
`bs-pt` | Bosnian => Portuguese
`ca-pt` | Catalan => Portuguese
`cdo-pt` | Min Dong => Portuguese
`chr-pt` | Cherokee => Portuguese
`chy-pt` | Cheyenne => Portuguese
`cr-pt` | Cree => Portuguese
`cs-pt` | Czech => Portuguese
`cy-pt` | Welsh => Portuguese
`da-pt` | Danish => Portuguese
`de-pt` | German => Portuguese
`el-pt` | Greek => Portuguese
`en-pt` | English => Portuguese
`eo-pt` | Esperanto => Portuguese
`es-pt` | Spanish => Portuguese
`et-pt` | Estonian => Portuguese
`eu-pt` | Basque => Portuguese
`fa-pt` | Persian => Portuguese
`ff-pt` | Fula => Portuguese
`fi-pt` | Finnish => Portuguese
`fr-pt` | French => Portuguese
`ga-pt` | Irish => Portuguese
`gan-pt` | Gan => Portuguese
`gd-pt` | Scottish Gaelic => Portuguese
`gu-pt` | Gujarati => Portuguese
`gv-pt` | Manx => Portuguese
`ha-pt` | Hausa => Portuguese
`hak-pt` | Hakka => Portuguese
`haw-pt` | Hawaiian => Portuguese
`he-pt` | Hebrew => Portuguese
`hi-pt` | Hindi => Portuguese
`hr-pt` | Croatian => Portuguese
`ht-pt` | Haitian => Portuguese
`hu-pt` | Hungarian => Portuguese
`hy-pt` | Armenian => Portuguese
`id-pt` | Indonesian => Portuguese
`ig-pt` | Igbo => Portuguese
`is-pt` | Icelandic => Portuguese
`it-pt` | Italian => Portuguese
`iu-pt` | Inuktitut => Portuguese
`ja-pt` | Japanese => Portuguese
`jbo-pt` | Lojban => Portuguese
`jv-pt` | Javanese => Portuguese
`ka-pt` | Georgian => Portuguese
`kg-pt` | Kongo => Portuguese
`ki-pt` | Kikuyu => Portuguese
`kl-pt` | Greenlandic => Portuguese
`km-pt` | Khmer => Portuguese
`ko-pt` | Korean => Portuguese
`la-pt` | Latin => Portuguese
`lg-pt` | Luganda => Portuguese
`lo-pt` | Lao => Portuguese
`lt-pt` | Lithuanian => Portuguese
`lv-pt` | Latvian => Portuguese
`mg-pt` | Malagasy => Portuguese
`mi-pt` | Maori => Portuguese
`mn-pt` | Mongolian => Portuguese
`ms-pt` | Malay => Portuguese
`mt-pt` | Maltese => Portuguese
`nah-pt` | Nahuatl => Portuguese
`ne-pt` | Nepali => Portuguese
`nl-pt` | Dutch => Portuguese
`nn-pt` | Norwegian (Nynorsk) => Portuguese
`no-pt` | Norwegian => Portuguese
`nv-pt` | Navajo => Portuguese
`ny-pt` | Chichewa => Portuguese
`oc-pt` | Occitan => Portuguese
`pa-pt` | Punjabi => Portuguese
`pi-pt` | Pali => Portuguese
`pl-pt` | Polish => Portuguese
`ps-pt` | Pashto => Portuguese
`qu-pt` | Quechua => Portuguese
`ro-pt` | Romanian => Portuguese
`ru-pt` | Russian => Portuguese
`sa-pt` | Sanskrit => Portuguese
`se-pt` | Northern Sami => Portuguese
`sh-pt` | Serbo-Croatian => Portuguese
`sk-pt` | Slovak => Portuguese
`sl-pt` | Slovenian => Portuguese
`sn-pt` | Shona => Portuguese
`so-pt` | Somali => Portuguese
`sq-pt` | Albanian => Portuguese
`sr-pt` | Serbian => Portuguese
`sv-pt` | Swedish => Portuguese
`sw-pt` | Kiswahili => Portuguese
`ta-pt` | Tamil => Portuguese
`te-pt` | Telugu => Portuguese
`th-pt` | Thai => Portuguese
`tl-pt` | Tagalog => Portuguese
`tpi-pt` | Tok Pisin => Portuguese
`tr-pt` | Turkish => Portuguese
`ug-pt` | Uyghur => Portuguese
`uk-pt` | Ukrainian => Portuguese
`ur-pt` | Urdu => Portuguese
`vi-pt` | Vietnamese => Portuguese
`wo-pt` | Wolof => Portuguese
`wuu-pt` | Wu => Portuguese
`xh-pt` | Xhosa => Portuguese
`yi-pt` | Yiddish => Portuguese
`yo-pt` | Yoruba => Portuguese
`za-pt` | Zhuang => Portuguese
`zh-pt` | Chinese (Mandarin) => Portuguese
`zh_classical-pt` | Classical Chinese => Portuguese
`zh_min_nan-pt` | Min Nan => Portuguese
`zh_yue-pt` | Cantonese => Portuguese
`zu-pt` | Zulu => Portuguese

## Statistics

### Dictionary size

Language pair | # of entries
------------- | ------------
`af-pt` | 21496
`am-pt` | 5404
`ang-pt` | 2282
`ar-pt` | 121060
`arc-pt` | 1237
`bg-pt` | 93083
`bi-pt` | 433
`bn-pt` | 18807
`bo-pt` | 2344
`br-pt` | 30722
`bs-pt` | 30597
`ca-pt` | 201062
`cdo-pt` | 1834
`chr-pt` | 445
`chy-pt` | 523
`cr-pt` | 86
`cs-pt` | 123001
`cy-pt` | 22594
`da-pt` | 84637
`de-pt` | 333096
`el-pt` | 51351
`en-pt` | 588595
`eo-pt` | 114782
`es-pt` | 386853
`et-pt` | 51177
`eu-pt` | 108810
`fa-pt` | 158743
`ff-pt` | 193
`fi-pt` | 144907
`fr-pt` | 399440
`ga-pt` | 18364
`gan-pt` | 4234
`gd-pt` | 10085
`gu-pt` | 2971
`gv-pt` | 3779
`ha-pt` | 369
`hak-pt` | 2202
`haw-pt` | 1856
`he-pt` | 81618
`hi-pt` | 21232
`hr-pt` | 63377
`ht-pt` | 24808
`hu-pt` | 117756
`hy-pt` | 44730
`id-pt` | 95916
`ig-pt` | 734
`is-pt` | 20390
`it-pt` | 382183
`iu-pt` | 341
`ja-pt` | 192018
`jbo-pt` | 1145
`jv-pt` | 14479
`ka-pt` | 52976
`kg-pt` | 781
`ki-pt` | 290
`kl-pt` | 1502
`km-pt` | 1498
`ko-pt` | 111176
`la-pt` | 81994
`lg-pt` | 151
`lo-pt` | 1032
`lt-pt` | 59927
`lv-pt` | 33218
`mg-pt` | 48098
`mi-pt` | 2043
`mn-pt` | 9098
`ms-pt` | 111674
`mt-pt` | 2195
`nah-pt` | 6824
`ne-pt` | 6214
`nl-pt` | 347955
`nn-pt` | 43222
`no-pt` | 137177
`nv-pt` | 1558
`ny-pt` | 94
`oc-pt` | 67884
`pa-pt` | 7239
`pi-pt` | 2170
`pl-pt` | 327432
`ps-pt` | 2367
`qu-pt` | 13015
`ro-pt` | 136903
`ru-pt` | 301955
`sa-pt` | 4060
`se-pt` | 4950
`sh-pt` | 123131
`sk-pt` | 111067
`sl-pt` | 49924
`sn-pt` | 1422
`so-pt` | 2238
`sq-pt` | 22930
`sr-pt` | 142880
`sv-pt` | 256003
`sw-pt` | 15716
`ta-pt` | 20361
`te-pt` | 6876
`th-pt` | 46036
`tl-pt` | 32426
`tpi-pt` | 1258
`tr-pt` | 102374
`ug-pt` | 1972
`uk-pt` | 205536
`ur-pt` | 29722
`vi-pt` | 203825
`wo-pt` | 886
`wuu-pt` | 1813
`xh-pt` | 256
`yi-pt` | 6617
`yo-pt` | 25086
`za-pt` | 586
`zh-pt` | 231426
`zh_classical-pt` | 1989
`zh_min_nan-pt` | 9342
`zh_yue-pt` | 15459
`zu-pt` | 557

### Top ten dictionaries by number of entries

Language pair | # of entries
------------- | ------------
`en-pt` | 588595
`fr-pt` | 399440
`es-pt` | 386853
`it-pt` | 382183
`nl-pt` | 347955
`de-pt` | 333096
`pl-pt` | 327432
`ru-pt` | 301955
`sv-pt` | 256003
`zh-pt` | 231426

## License

According to the Wikidata website:

> All structured data from the main and property namespace is available under the Creative Commons CC0 License

The data in this repository is therefore made available under the same [Creative Commons CC0 License](https://creativecommons.org/publicdomain/zero/1.0/) as that used by the Wikidata project. All of the data has been derived from the Wikidata JSON format [database dumps](https://dumps.wikimedia.org/wikidatawiki/entities/).
