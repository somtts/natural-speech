Copyright 2016 Istituto Italiano di Tecnologia
Authors: Leonardo Badino, Alessio Mereta, Claudia Canevari

                          bioRec

The current folder contains the following sub-folders:

- phonerec: toolbox for articulatory phone recognition. This code was used
  to run some of the experiments described in
  Badino, L., Canevari, C., Fadiga, L., Metta, G., "Integrating Articulatory
  Data in Deep Neural Network-based Acoustic Modeling",
  Computer Speech and Language, vol 36, pp. 173-195, 2016
.
  Please cite the above paper if you use phonerec.

   You can train and test a phone recognizer with phonerec scripts using a preprocessed version of mngu0 available at: https://zenodo.org/record/836692

- pce_phonerec: articulatory phone recognition using phone context embeddings and multi-task learning described in:
Badino, L., "Phonetic Context Embeddings for DNN-HMM Phone Recognition", in Proc. of Interspeech, San Francisco, CA, USA, 2016.

- zerorchallenge: zero-resource automatic speech recognition
  Contains code of our entry to the Zero Resource Speech Challenge at Interspeech 2015.
  If you use this code please cite:
  Badino, L., Mereta, A. Rosasco, L. "Discovering discrete subword units
  with Binarized Autoencoders and Hidden-Markov-Model Encoders",
  Proc. of Interspeech, Dresden, Germany, 2015.

 Datasets to train and test how zerorchallenge systems are available here:  https://zenodo.org/record/836692

- netutils: deep neural network utilites (e.g., training, forward pass)

- utils: utilities (e.g., data normalization,  Viterbi-based phone  decoding) 

A brief description of each function/script is provided within the README file of each sub-folder.

This toolbox uses the Parallel Computing Matlab toolbox.

