# BanglaLM: Bangla Corpus For Language Model Research ![size: 40GB](https://img.shields.io/badge/size-40.0GB-green.svg)

This dataset consists of three parts:
* Raw data
* Preprocessed V1
* Preprocessed V2

## Link of the dataset

> Kaggle: [BanglaLM: Bangla Corpus For Language Model Research](https:/www.kaggle.com/gakowsher/bangla-language-model-dataset)

## Details of the dataset
We have collected text data which is a string of various lengths. The total volume of the data is 14 Gigabytes. We have collected data from various websites, including newspapers, social networks, blog sites, Wikipedia, etc. The newspaper websites include Prothom Alo, BD news, Jugantor, Jaijaidin, and so on. We have collected raw data using python script and done necessary preprocessing at the time of saving the data into local memory. Then we have gone through some more preprocessing steps that have been described later in the preprocessing section of this article. We have, in the meantime, started to build some models based on
this data and the primary findings are satisfactory, and it ensures the quality of the dataset.There are a total of 19132010 observations in our dataset. We are releasing three versions of this dataset including, (i) Raw data, (ii) Preprocessed V1, and (iii) Preprocessed V2. The raw data can be preprocessed according to the demand of any particular project, and Preprocessed V1 is for LSTM based machine learning model, and Preprocessed V2 is better suitable for a statistical model. This dataset can also be manually labeled to be used for supervised learning. `Fig.1`
below shows the screen copy of the dataset view using pandas data frame. We can see the index and text from the table. Each of the indexes indicates a particular entry, and in the right column, we can read the value of the text. We can see the raw data along with  Preprocessed V2 word count in `Fig.2`, `Fig.3` correspondingly.
<p float='left'>
    <img src='./assets/screen_copy.png' alt='this is screen copy of data' width=100% >
    <img src='./assets/raw.png' alt='this is the raw data summary' width=50% align=left/>
</p>
<p>
Here is he Summary of Preprocessed Data V2:
<img src='./assets/SUMMARY OF PREPROCESSED DATA V2.png' alt = 'this is summary of preprocessed data v2' width = '50%' align=left/>

<br>
The workflow of the data collection procedure is shown below in Fig. 5.
<img src='./assets/flowchart.png' alt = 'this is summary of preprocessed data v2' width = '50%' align=left/>
</p>



## Get the data
You can use direct links to download the dataset. 
| Name | Size | Link (Compressed ZIP) |
| --- | --- | --- |
| `Raw data` | 13.27 GB | [Download](https://cutt.ly/vmR1pbA) |
| `Preprocessed V1` | 13.22 GB | [Download](https://cutt.ly/ZmR1P1v) |
| `Preprocessed V2` | 12.89 GB | [Download](https://cutt.ly/VmR1D2V) |


# Usage
You can us this dataset to train model using our [Bangla FastText Model & Toolkit](https://pypi.org/project/BanglaFastText/)

To install the latest release, you have to do:
```bash
!pip install BanglaFastText
```
For further information and introduction you can visit this Github repo: [Bangla FastText Model & Toolkit](https://github.com/Kowsher/Bangla-Fasttext)



