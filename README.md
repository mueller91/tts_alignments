## About
This repository collects time alignments for popular TTS datasets, removing leading and trailing pauses.
Additionally, a sentence is split when a pause is > 0.3 seconds.

We use the https://montreal-forced-aligner.readthedocs.io/en/latest/ (MFA) and extract, for each file, the following information:

`path|text|speaker|start|end`

where `start` and `end` are given in seconds. For example:

`VCTK-Corpus/wav48/p295/p295_138.wav|I haven't had a lesson in four years.|VCTK_p295|0.6898185941043085|2.569818594104308`

Removing leading and trailing silences is standard practice in text-to-speech synthesis, and these files should help.

## Datasets
Currently, we supply alignments for
- VCTK
- LibriTTS
- Blizzard

## How to contribute
If you want to contribute, please submit a PR.

## Say hello!
If you found my alignments useful, built something cool or have any questions, 
please drop me a line or submit an issue!