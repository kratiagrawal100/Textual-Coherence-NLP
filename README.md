# Textual-Coherence-NLP
## Project: Introduction to NLP
## Team: 36
* **Description:** 
An important aspect for a textual discourse, coherence measures the readability, clarity, and
consistency of ideas expressed in a passage. Within a discourse, the coherency is exhibited at
both - local and global levels. Whether to model the problem on a global level or to decompose it
into a series of local decisions remains a modeling choice. 
This project is regarding the experiments with neural models in measuring textual coherence.

* **Dataset Used:**  GCDC Corpus 
### Code Location
* Download the zip, extract it
* Folder named 36-Final will contain the corresponding code files
* files names:36_GRU, 36_RNN_LSTM, 36_Transformer
### Code structure
* Following files contain the respective experiments done
1. 36_RNN_LSTM.py
* This File contains the experiment on dataset with neural model RNN and LSTM

2. 36_GRU.py
* This File contains the experiment on dataset with neural model GRU

3. 36_Transformer.py
* This File contains the experiment on dataset with neural model Transformer


### Data location
* Dataset Link: https://drive.google.com/file/d/1q8S6u7No0iYKLCf5whfo51JdXb8UjHZx/view?usp=share_link

### Model checkpoints
* This is the overall Link that contains data zip as well as saved Models
Saved Model names are appended with neural network name For e.g. LSTM_model
* we have experimented considering different test set from GCDC so for each model there would be 4 corresponding files.
* In case of more than 4 files these are hyper parameter tuning model files
* all this interpretation can be easily understood while walkthrough through code files once.
* Model checkpoints Link: https://drive.google.com/drive/folders/1p8ka3ldqXD0F_CB4FglXdo-McmPjYS7E?usp=share_link

### How to Run
* Download data (zip) from data Link, extract and rename to GCDC_data_domain
* Run specific Model file (RNN,LSTM,GRU or transformer)
* Change absolute path to the path where you want to save the model or other important files like vocabulary etc.
* In case of only testing change absolute path to the path from where model files can be loaded.
* `python3 36_RNN_LSTM.py` similarly we can do for other files.
