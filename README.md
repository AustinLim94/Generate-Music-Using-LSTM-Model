# Generate-Music-Using-LSTM-Model
In this project, I generated classical music (20th Century Music) using LSTM Neural Network Model. 

You can download the weights.hdf5 and just run the predict.py to save time from running the lstm.py. 

File Explanation:

- Data/note: is needed to run the lstm.py
- midi_songs: Has all the songs to feed into the LSTM model
- lstm.py: This file shows how I constructed the LSTM model and did the training
- predict.py: This file creates a new song based on the lstm output
- test_output.mid is the final result I got from predict.py 
- weights.hdf5: Use this weight to run predict.py so you can skip the training part
