Download Link: https://assignmentchef.com/product/solved-cmu11485-homework-1-part-2-an-introduction-to-neural-networks
<br>
Part 2: Frame Level Classification of Speech

This part of the homework is a live competition on <a href="https://www.kaggle.com/c/11-785-fall-20-homework-1-part-2">kaggle</a><a href="https://www.kaggle.com/c/11-785-fall-20-homework-1-part-2">.</a>

In this challenge you will take your knowledge of feedforward neural networks and apply it to a more useful task than recognizing handwritten digits: speech recognition. You are provided a dataset of audio recordings (utterances) and their phoneme state (subphoneme) labels. The data comes from LibriSpeech corpus which is derived from audiobooks that are part of the LibriVox project, and contains 1000 hours of speech sampled at 16 kHz. If you have not encountered speech data before or have not heard of phonemes or spectrograms, we will clarify the problem further. For more information, see the paper ”LibriSpeech: an ASR corpus based on public domain audio books”, Vassil Panayotov, Guoguo Chen, Daniel Povey and Sanjeev Khudanpur, ICASSP 2015 (submitted) <a href="http://www.danielpovey.com/files/2015_icassp_librispeech.pdf">(pdf</a><a href="http://www.danielpovey.com/files/2015_icassp_librispeech.pdf">).</a>

You will be evaluated on the accuracy of the prediction of the phoneme state labels for each frame in the test set.

Please refer to the <a href="https://www.kaggle.com/c/11-785-fall-20-homework-1-part-2">kaggle page</a> for more details on the task.

<h2>Data</h2>

<ul>

 <li><strong>npy</strong>: (22002, )</li>

 <li><strong>train labels.npy</strong>: (22002, )</li>

 <li><strong>npy</strong>: (2332, )</li>

 <li><strong>dev labels.npy</strong>: (2332, )</li>

 <li><strong>npy</strong>: (2251, )</li>

</ul>

The audio data has been transcribed into mel spectrograms. You have 100 13-dimensional mel spectral (row) vectors per second of speech in the recording.

<h2>1.1         Task</h2>

Your task is to generate predictions for the phonemes of the test set. You will be evaluated based on the accuracy of your predictions. Grade cut-offs are released after the early deadline. For detailed information, please look at the <a href="https://www.kaggle.com/c/11-785-fall-20-homework-1-part-2">kaggle page</a>

2