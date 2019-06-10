# DSTC8-AVSD
DSTC8-AVSD: Sentence generation task for Audio Visual Scene-aware Dialog 

## - Track Description
Welcome to the follow-up challenge for Audio Visual Scene-Aware Dialog (AVSD) using Natural Langauge Generation (NLG) technologies. This challenge is one of the track for the **8th Dialog System Technology Challenges (DSTC8) workshop.**
The task is to build a system that generates responses in a dialog about an input **video**.

### - Tasks

In this challenge, systems are reuiqred to generate responses to a user input in the context of a given dialog.  
This context consists of a dialog history (previous utterances between both user and system) in addition to video and audio information that comprise the scene. 
The quality of a system response automatically generated is evaluated using objective measures to see how good the generated responses are in terms of the naturalness and informativeness.

#### 1. Task 1: Video and Text 
    a. Use the video and text training data provided but no external data sources, 
       other than publicly available pre-trained feature extraction models.

       There are two options: with or without using the summary generated by the questioners after holding 10 QAs.

    b. External data may also be used for training.

#### 2. Task 2: Text Only 
    a. Do not use the input videos for training or testing. 
       Use only the text training data (dialogs and video descriptions) provided. 
    b. Any publicly available text data may also be used for training.
    
    
#### Validation data set:

Please train models using the training data set only.
You con tune the parameters ugint he validation set and confirm the performance of your systems using the DSTC7 test sets.
Notes: The official challenge doesn't allow you to use the DSTC7 test set to tune your models.

|               |    Training    |  Validation   |   DSTC7 Test  |
| ------------- | -------------- | ------------- | ------------- |
| # of Dialogs  |       7,659    |      1,787    |      1,710    |   
| # of Turns    |     153,180    |     35,740    |     13,490    |
| # of Words    |   1,450,754    |    339,006    |    110,252    |

*The number of tunrs for the test set is smaller than the validation
because they are not always full dialogs.

You can donwload the full oficial data set and the refereces for AVSD@DSTC7 from here:
https://drive.google.com/drive/folders/1SlZTySJAk_2tiMG5F8ivxCfOl_OWwd_Q?usp=sharing


### - Contact Information
chori@merl.com
