# Syllable_Classification_system

 A deep neural network was built using [TensorFlow](https://www.tensorflow.org/) and Keras API.

 Under normal environment, audio signals from `74 children` were collected with each child reciting various syllable sounds. 

Sounds were segmented using [WaveSurfer](https://sourceforge.net/projects/wavesurfer/) app and their `MFCC features` were derived using [Librosa](https://librosa.org/doc/latest/index.html) which is a python package for audio analysis.

The various syllable sounds that were analysed are listed below:

| Root letter |       Sounds         |
|:------------| :----------------- |
|      B      | `ba` `baa` `bi` `bii` `bo` `boo` `bu` `buu` `bai` `bau`  
|      D      |`da` `daa` `di` `dii` `do` `doo` `du` `duu` `dai` `dau`
|      G      |`ga` `gaa` `gi` `gii` `go` `goo` `gu` `guu` `gai` `gau`
|      M      |`ma` `maa` `mi` `mii` `mo` `moo` `mu` `muu` `mai` `mau`

The dataframes for the features of the syllable sounds were created using [Pandas](https://pandas.pydata.org/docs/).

Data of 60 children was used for training and 14 children was used for testing.
