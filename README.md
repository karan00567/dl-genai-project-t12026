# dl-genai-project-t12026

This Repository contains models which can be used to classify different songs based on thier genre.
Genres that the model can predict are blues, classical, country, disco, hiphop, jazz, metal, pop, reggae, rock.

The different Models trained are:-
* Convolutional Neural Network: This is one of the model first used to classify songs. This model, takes the spectogramic image of the song as input and predicts the genre of the song.
* Convolutional Reccurent Neural Network: This model is a hybrid between CNN and RNN. CNN is used for spatial extraction and RNN is used for sequential learning.
* Finetuned AST: This model is a finetuned version of MIT/ast-finetuned-audioset-10-10-0.4593, which is a Audio Spectrogram Transformer (AST) model trained on AudioSet dataset.

Dataset Details:
1. This dataset is made data provided in the Jan 2026 DLGenAI Project - Messy Mashup competition. This dataset consists of 100 songs from each genre, further broken down into different stems namely drums, vocals, bass, and others.  
2. Dataset consists of 10K song samples, which are differnt amount of noises ranging from 3-8, added from the ESC-50 Noise dataset, at random intervals of time at random length.
3. This dataset also has some temporal and rhtymic adjustments.
4. The songs from each genre are created by combining differnt stems from the same genre to create a single stem for that songs. This process is repeated for the other stems as well. Then these stems are added to create a song.

Libraries Used:
* Torch
* Librosa
* Torchaudio
* Transformers
* Seaborn & Matplotlib
* Pandas & Numpy


The logs of the trained models are visible at [here](https://wandb.ai/24f2000010-indian-institute-of-technology-madras/24f2000010-t12026)  

Model 1 CNN : [Kaggle Link](https://www.kaggle.com/models/sreekaranreddy2005/model1-cnn)  

Model 2 CRNN : [Kaggle Link](https://www.kaggle.com/models/sreekaranreddy2005/model2-crnn)  

Model 3 Finetuned-AST :[Kaggle Link](https://www.kaggle.com/models/sreekaranreddy2005/finetuned-ast)  


Dataset Link : [HuggingFace Link](https://huggingface.co/datasets/24f2000010/messy-mashup-augmented)  
Spectogram Dataset Link : [Kaggle Link](https://www.kaggle.com/datasets/sreekaranreddy2005/mel-spectograms)  
Spectogram Dataset Labels Link : [Kaggle Link](https://www.kaggle.com/datasets/sreekaranreddy2005/mel-spectograms-labels)




P.Sreekaran Reddy (24f2000010)
