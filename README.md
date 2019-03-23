# RNN-Product-Classification-NDSC2019
RNN based prediction approach on Shopee Dataset by team Datakrafters


Our network model consists of an recurrent neural network designed to process the text data only. This decision was chosen due to the large amount of noise and inconsistencies observed in the image data.

To apply the RNN architecture to our dataset, we treated our problem as a case of sequence-to-sequence prediction. 
* Each feature/attribute category had its labels transformed into one-hot encoded vectors, which served as our sequenced target labels in for our RNN. 
* The contents of the title feature were tokenized and treated as our sequenced inputs. 
* Our network was then trained on each of the three datasets, before producing a predicted output sequence from which output feature/attribute categories could be extracted. 
* Undefined NaN labels were encoded as “defaults” during training and prediction, before being restored in post-processing

Team Datakrafters:

Liu Peng<br/>
Yijie Xu<br/>
Shaun Tan<br/>
Krupa Malik<br/>
