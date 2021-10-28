# A Benchmark Dataset for Learning to Intervene in Online Hate Speech

In order to encourage strategies of countering online hate speech, we introduce a novel task of generative hate speech intervention along with two fully-labeled datasets collected from Gab and Reddit. Distinct from existing hate speech datasets, our datasets retain their conversational context and introduce human-written intervention responses. Due to our data collecting strategy, all the posts in our datasets are manually labeled as hate or non-hate speech by Mechanical Turk workers, so they can also be used for the hate speech detection task.

There are two CSV files under the data directory: gab.csv and reddit.csv, These datasets provide conversation segments, hate speech labels, as well as intervention responses written by  Mechanical Turk workers.

Two data files have the same data structure:

|Field|Description|
|-------|-------------|
|id|the ids of the post in a conversation segment|
|text|the text of the posts in a conversation segment|
|hate_speech_idx|a list of the indexes of the hateful posts in this conversation|
|response|a list of human-written responses|

Please refer to the paper "A Benchmark Dataset for Learning to Intervene in Online Hate Speech" (EMNLP 2019) for the detailed information about the dataset.

# Data Processing
Other meta data of the Reddit post can be retrieved using Reddit API and the ids of the posts. 

Other meta data of the Gab post can be retrieved from the dataset https://files.pushshift.io/gab/GABPOSTS_2018-10.xz using the ids of the posts.

# License
The dataset is licensed under the Creative Commons Attribution-NonCommercial 4.0 International Public License. To view a copy of this license, visit https://creativecommons.org/licenses/by-nc/4.0/ or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA. 
