# ACV-003
public Peking opera singing voice dataset

# Dataset Info:
## Format and Specs:
The dataset is manually labeled with the [ArchiVoice Chinese system](https://github.com/Archivoice/AV-diffsinger-Chinese-support)

The dataset's labels are generated via [WFL](https://github.com/MLo7Ghinsan/WFL-ASR) and manually corrected.

The dataset is recorded at 16 bit 44.1k Hz in wav format and labeled in HTK label format (.lab).\
Audio has been dereverbed and denoised for more even consistency.

The dataset is released with two versions, full length and segmented.\
The full length dataset only includes wav and lab files, whereas the segmented dataset includes ds files and a transcription.csv for [diffsinger](https://github.com/openvpi/DiffSinger) usage.\
The ds contains f0 and note slur data.

## Additional Info:
The dataset includes the following global phonemes: [`exh`,`vf`], `exh` for exhales and `vf` for vocal fry

## Song List:
See [song list](/song_list.txt)

# Credits:
Voice provided by Jonathan Huang 黃奕晨, owner of ArchiVoice, [X/Twitter](https://x.com/NekroTheCorpse)

# License:
<a href="https://github.com/Archivoice/ACV-003">ACV-003</a> © 2026 by <a href="https://github.com/Archivoice">YiChen Huang</a> is licensed under <a href="https://creativecommons.org/licenses/by-sa/4.0/">CC BY-SA 4.0</a><img src="https://mirrors.creativecommons.org/presskit/icons/cc.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/by.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/sa.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;">

The license only applies to direct use of the dataset and models mainly featuring the voice of ACV-003, and does not apply to models trained via parallel training.\
Models trained using ACV-003 as supplementary data can follow its own license.
