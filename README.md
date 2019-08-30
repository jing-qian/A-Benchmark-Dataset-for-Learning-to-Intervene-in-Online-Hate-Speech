# A Benchmark Dataset for Learning to Intervene in Online Hate Speech

There are two CSV files under the data directory: gab.csv and reddit.csv, containing the data collected from Gab and Reddit together with the crowd-sourced labels separately.
Two data files have the same data structure:

|Field|Description|
|-------|-------------|
|id|the ids of the post in a conversation segment|
|hate_speech_idx|a list of the indexes of the hateful posts in this conversation|
|response|a list of human-written responses|

Please refer to the paper "A Benchmark Dataset for Learning to Intervene in Online Hate Speech" (EMNLP 2019) for the detailed information about the dataset.

# Data Processing
The code for parsing the data will be released soon.