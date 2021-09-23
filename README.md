<img align="center" alt="banglaLM" src="./assets/data-original.png" width="100%" /> 

# BanglaLM: Bangla Corpus For Language Model Research ![size: 40GB](https://img.shields.io/badge/size-40.0GB-green.svg)


This dataset consists of three parts:
* Raw data
* Preprocessed V1
* Preprocessed V2

## Link of the dataset

> Kaggle: [BanglaLM: Bangla Corpus For Language Model Research](https:/www.kaggle.com/gakowsher/bangla-language-model-dataset)

## Details of the dataset
We have collected text data which is a string of various  lengths. The total volume of the data is 14 Gigabytes. We have collected data from various websites, including newspapers, social networks, blog sites, Wikipedia, etc. The newspaper websites include Prothom Alo, BD news, Jugantor, Jaijaidin, and so on. We have collected raw data using python script and done necessary preprocessing at the time of saving the data into local memory. Then we have gone through some more preprocessing steps that have been described later in the preprocessing section of this article. We have, in the meantime, started to build some models based on
this data and the primary findings are satisfactory, and it ensures the quality of the dataset.There are a total of 19132010 observations in our dataset. We are releasing three versions of this dataset including, (i) Raw data, (ii) Preprocessed V1, and (iii) Preprocessed V2. The raw data can be preprocessed according to the demand of any particular project, and Preprocessed V1 is for LSTM based machine learning model, and Preprocessed V2 is better suitable for a statistical model. This dataset can also be manually labeled to be used for supervised learning. `Fig.1`
below shows the screen copy of the dataset view using pandas data frame. We can see the index and text from the table. Each of the indexes indicates a particular entry, and in the right column, we can read the value of the text. We can see the raw data along with  Preprocessed V2 word count in `Fig.2`, `Fig.3` correspondingly.

<p float='left'>
    <img src='./assets/screen_copy.png' alt='this is screen copy of data' width=100% >
    <img src='./assets/raw.png' alt='this is the raw data summary' width=50% align=left/>
</p>
<p> 
    
Here is he Summary of Preprocessed Data V2:
    
<img src='./assets/summary_v1.png' alt = 'this is summary of preprocessed data v1' width = '50%' align=left/>

<br>
The workflow of the data collection procedure is shown below in Fig. 5.
<img src='./assets/flowchart.png' alt = 'flowchart' width = '50%' align=left/>
</p>



## Get the data
You can use direct links to download the dataset. 
| Name | Size | Link (Compressed ZIP) |
| --- | --- | --- |
| `Raw data` | 13.27 GB | [Download](https://storage.googleapis.com/kaggle-data-sets/1343996/2352458/compressed/BanglaLM_raw/BanglaLM_raw.txt.zip?X-Goog-Algorithm=GOOG4-RSA-SHA256&X-Goog-Credential=gcp-kaggle-com%40kaggle-161607.iam.gserviceaccount.com%2F20210725%2Fauto%2Fstorage%2Fgoog4_request&X-Goog-Date=20210725T105754Z&X-Goog-Expires=259199&X-Goog-SignedHeaders=host&X-Goog-Signature=5518facbc9955fb08a884ec1b8476e92f4f90a6fcdbe252aa001e67f20acba7aef683fb76b5c6545d15bbb6556065bdd5dcfe93bde8c5f5b7816fdcf15e21431eb1d3f9a52115ea9cfbab4d339253e24df8417eec6aa97b4081ff3d53a9b97e4818d9c0471a56e962061d4bae41323c8bcea9775a85ef4dfeb0068b24b61a5c274a654b515e2d1aa142c1a6b70646bb04897c5c576afb4e75f4ea043e926570122f7fb9eb5b1fee0d9ccf24b882073636b2f8b22111e7ae06d81fb773ac6f4fa1f214055a82999dff40b12d97e22d4a001cde1b0cfc165b168a069dea8cd3339855f4818f6dcbbe22ac694142ded6e6729cfb5a0ef353bbd3a18d8a57ae227bb) |
| `Preprocessed V1` | 13.22 GB | [Download](https://storage.googleapis.com/kaggle-data-sets/1343996/2352458/compressed/BanglaLM_process_v1/banglaLM_process_v1.txt.zip?X-Goog-Algorithm=GOOG4-RSA-SHA256&X-Goog-Credential=gcp-kaggle-com%40kaggle-161607.iam.gserviceaccount.com%2F20210725%2Fauto%2Fstorage%2Fgoog4_request&X-Goog-Date=20210725T105843Z&X-Goog-Expires=259199&X-Goog-SignedHeaders=host&X-Goog-Signature=6131bf616575c8ea47080973f92bc21fa45fbb2fa6b1e9a9d8d92e10410d907f5820c65e0fff70ca5b6ecb9b51e8755fa7e51c61dbd47d6793624e29065ee9c1edb940f78c8d0783925c632155950dbe22ad75aa49e9c4a25907323e6f5062caab9b85a8a32905fae61a1e6b2a69fce511d10c83ac04d4b3ca961a129f8886ba4b5d09993ad1b9a8ba82c76b96a136a43bd9dcb510602f26fece570291227ffafb363cf8bbfb702e0523f7508d6859d67cbb6ac53391b58a903881a724d2ed79792dc5c0aac73b8974312ba152f6e76b63d2d086170c1a9607074f65f22a55a97423842ce3af9e74b76d7aa21b4e1d6bd94ddda3c434a8feece5df3593cf52ee) |
| `Preprocessed V2` | 12.89 GB | [Download](https://storage.googleapis.com/kaggle-data-sets/1343996/2352458/compressed/BanglaLM_process_v2/BanglaLM_process_v2.txt.zip?X-Goog-Algorithm=GOOG4-RSA-SHA256&X-Goog-Credential=gcp-kaggle-com%40kaggle-161607.iam.gserviceaccount.com%2F20210725%2Fauto%2Fstorage%2Fgoog4_request&X-Goog-Date=20210725T105855Z&X-Goog-Expires=259199&X-Goog-SignedHeaders=host&X-Goog-Signature=9249f125df4f9f450d7cf6cdd8c8aecc4fa84360243a73a0663160574ee7c5fd32f694f86c50fa7010e3bf5b3254e590b6d2b974a4b9d9046f8eaf19e8fe853188539ec446c0ad0338511ade26d454eef846fd0d1fea4ca1b310cc54e64c98b23fad4f7471f3dd0bc81fcbbb161835be39bda0f73cb09801619ba6643dc16eec73e2ca09a28466459b2074495e2d4d37a46107308dabb263119302e58e4e9114081a1d1a78a1073b81bf9535e37379136b8a0f40270114056f9f217b812709ab6d9a08878a496975e0ac394d6e96c431b0f0ad286c9cb6b6b24553bddaeffac8d2277630b6c7527f2b3ff00e0b00ee4854548e9cc65506f868f5b655b1f3599f) |


# Usage
A [bert-base-bangla](https://huggingface.co/Kowsher/bert-base-bangla) (Transformer based Masked language model) has been developed using the dataset


This dataset has been used to train the pretrained model [Bangla FastText Model & Toolkit](https://pypi.org/project/BanglaFastText/)

To install the latest release, you have to do:
```bash
!pip install BanglaFastText
```
For further information and introduction you can visit this Github repo: [Bangla FastText Model & Toolkit](https://github.com/Kowsher/Bangla-Fasttext)

## License
Contents of this repository are restricted to only non-commercial research purposes under the [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/). Copyright of the dataset contents belongs to the original copyright holders.


****Cite this dataset****👍 

```
@inproceedings{kowsher-etal-2021-banglalm,
    title = "BanglaLM: Bangla Corpus for Language Model Research",
    author ="Kowsher, Md. and
     Uddin, Md.Jashim and
     Tahabilder, Anik and
     Ruhul Amin, Md and
     Shahriar, Md. Fahim and 
     Sobuj, Md. Shohanur Islam
     ",
      
    conference = "International conference on inventive research in computing applications (ICIRCA)",
    month = "September",
    year = "2021",
    address = "Online",
    publisher = "IEEE",
    url = "https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3882903"
}
```
