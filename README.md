## Audio Visual Eyetracking (AVE)

AVE is an effort to provide a large corpus of Audio visual eyetracing data to be used for a range of studies.
This enables us to employ data intensive techniques to explore the relationship between audio and video in attention deoployment and/or learn saliency models from such data. 

### Data

The current version puts together data from various existing databases in order to provide a relatively large scale, diverse set of videos acompained with eye tracking. The original data should be downloaded from the original sources as linked bellow. We provide the splits of train, validation, and test that are used in conjunction with our baseline deep model provided in [DAVE: A Deep Audio-Visual Embedding for Dynamic Saliency Prediction](https://arxiv.org/abs/1905.10693).

The current data contains stimuli and eyetracking from the following databases:

- [Antonie coutrot Database 1 \& Database 2] (http://antoinecoutrot.magix.net/public/databases.html)
- A subset of 76 sequences of [DIEM] (http://jhenderson.org/vclab/DIEM.html)

This data accounts for 150 video sequences summing to 267109 frames of approximately 2 hours and 33 minutes length. This data is grouped into 'Nature', 'Social events', and 'Miscellaneous' categories. The following table shows the number of videos in each category and train/val/test fold:

|Video type | Train | Validation | Test|
'--------------------------------------'
'Nature' 37 ' 6 ' 10 '
'--------------------------------------'
'Social Events' 18 ' 16 ' 11 '
'--------------------------------------'
'Miscellaneous' 37 ' 7 ' 7 '
'--------------------------------------'
'Total (150) '  92 ' 29 ' 29 '

Please read [DAVE](https://arxiv.org/abs/1905.10693) for more details.

### Helper Scripts

The current version contains data from several sources. We, thus, provide some helper scripts to transform the data into a uniform format to ease using them.

### Preprocessed data

The preprocessed data as used in [DAVE](https://arxiv.org/abs/1905.10693) is available at [Download]()


### Referencing

In using this data, we kindly ask you to cite all the following publications:


'''
@article{Tavakoli2019,
  author    = {Hamed R. Tavakoli and Ali Borji and Esa Rahtu and Juho Kannala},
  title     = {{DAVE:} {A} Deep Audio-Visual Embedding for Dynamic Saliency Prediction},
  journal   = {CoRR},
  volume    = {abs/1905.10693},
  year      = {2019},
  url       = {http://arxiv.org/abs/1905.10693},
}
'''

'''
@article{Coutrot2014,
    author = {Antoine Coutrot and Nathalie Guyader},
    title = "{How saliency, faces, and sound influence gaze in dynamic social scenesShort Title??}",
    journal = {Journal of Vision},
    volume = {14},
    number = {8},
    pages = {5-5},
    year = {2014},
}
'''

'''
@INPROCEEDINGS{7362640,
author={Antoine Coutrot and Nathalie Guyader},
booktitle={2015 23rd European Signal Processing Conference (EUSIPCO)},
title={An efficient audiovisual saliency model to predict eye positions when looking at conversations},
year={2015}
'''

'''
@INPROCEEDINGS{7362640,
author={Antoine Coutrot and Nathalie Guyader},
booktitle={2015 23rd European Signal Processing Conference (EUSIPCO)},
title={An efficient audiovisual saliency model to predict eye positions when looking at conversations},
year={2015}
'''




### Where to download the data
