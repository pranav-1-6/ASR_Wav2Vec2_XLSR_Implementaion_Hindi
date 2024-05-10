# ASR_Wav2Vec2_XLSR_Implementaion_Hindi
Speech2Text for Hindi Language

We have used multilingual pre-trained wav2vec 2.0 (XLSR) model for the ASR of Hindi Language:

Model | Architecture | Hours | Languages | Datasets | Model
|---|---|---|---|---|---
XLSR-53 | Large | 56k | 53 | MLS, CommonVoice, BABEL | [download](https://dl.fbaipublicfiles.com/fairseq/wav2vec/xlsr_53_56k.pt)

The XLSR model uses the following datasets for multilingual pretraining:

* **[MLS: Multilingual LibriSpeech](https://indico2.conference4me.psnc.pl/event/35/contributions/3585/attachments/1060/1101/Wed-2-6-10.pdf)** (8 languages, 50.7k hours): *Dutch, English, French, German, Italian, Polish, Portuguese, Spanish*

* **[CommonVoice](https://commonvoice.mozilla.org/en/languages)** (36 languages, 3.6k hours): *Arabic, Basque, Breton, Chinese (CN), Chinese (HK), Chinese (TW), Chuvash, Dhivehi, Dutch, English, Esperanto, Estonian, French, German, Hakh-Chin, Indonesian, Interlingua, Irish, Italian, Japanese, Kabyle, Kinyarwanda, Kyrgyz, Latvian, Mongolian, Persian, Portuguese, Russian, Sakha, Slovenian, Spanish, Swedish, Tamil, Tatar, Turkish, Welsh* (see also [finetuning splits]([https://dl.fbaipublicfiles.com/cpc_audio/common_voices_splits.tar.gz]) from [this paper](https://arxiv.org/abs/2002.02848)).

* **[Babel](https://catalog.ldc.upenn.edu/byyear)** (17 languages, 1.7k hours): *Assamese, Bengali, Cantonese, Cebuano, Georgian, Haitian, Kazakh, Kurmanji, Lao, Pashto, Swahili, Tagalog, Tamil, Tok, Turkish, Vietnamese, Zulu*
