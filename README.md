# Wild-animals-sounds-prediction
This notebook is meant to be runned to convert audio files of wild animals into MFCC features and predict which animals these sounds come from.
## Requirements
- To run the notebook type the following commands:
	- ```pip install librosa```
	- ```pip install keras```
- Once you've trained the Keras model run the following commands to save it:
	- ```filename = './pickle/wild-animals-mfcc-neural-network-model.h5'```
	- ```model.save(filename)```
