# Spoken_Digit_Recognition

Spoken digit recognition using LSTM (Long Short-Term Memory) is a common application of deep learning in the field of speech recognition. The goal is to design a model that can accurately classify spoken digits (numbers) based on the audio input.

Model Architecture:

1. Build an LSTM-based model for spoken digit recognition. LSTMs are well-suited for sequence data like audio because they can capture temporal dependencies.
2. The input to the LSTM model will be the sequence of audio features (e.g., spectrogram frames or MFCCs) over time.
3. You may also need to add an additional layer (e.g., a fully connected layer) after the LSTM to map the LSTM output to the number of classes (digits) for classification.
