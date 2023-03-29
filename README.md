# ParkinsonDataset
We searched for multiple Parkinson’s disease public datasets and divided them into three kinds: drawing, speech, and gait. 
The handdrawing dataset contains three subsets: [HandPD](http://wwwp.fc.unesp.br/~papa/pub/datasets/Handpd/), [NewHandPD](http://wwwp.fc.unesp.br/~papa/pub/datasets/Handpd/), [Kaggle](https://www.kaggle.com/datasets/kmader/parkinsons-drawings).

The voice dataset contains two subsets: [ItalianVoice](https://ieee-dataport.org/open-access/italian-parkinsons-voice-and-speech) and [MDVR-KCL](https://zenodo.org/record/2867216#.ZCPnJnbP1PY).

The gait data contains two subsets: [Ga](https://physionet.org/content/gaitpdb/1.0.0/) and [Ju](https://physionet.org/content/gaitpdb/1.0.0/).

For the handdrawing dataset, we used spirals and meanders graphs from all datasets to make sure the graph types are consistent, excluding circle images from NewHandPD and wave graphs from Kaggle.For ItalianVoice in the speech dataset, we excluded data from 15 healthy
young people and two older healthy people with murmurs. Then three tasks
with longer time were selected: reading speech-balanced text, sentences, and
words. For the MDVR-KCL dataset, we used data from all people, but the voice
recordings of the dataset contain white space and the voice of the staff, which

