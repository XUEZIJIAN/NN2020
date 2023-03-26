NN2022 project
This project is a reimplementation of Shuffling Recurrent Neural Networks,
using the premute_mnist data set,
tested different shuffling types,
and combined with Sliced Recurrent Neural Networks to improve the performance.

Usage
Use Google Colab
1.mount your Google Drive by
	from google.colab import drive
	drive.mount('/content/drive')
2.Specify the directory where you put the files(notebook,runs,model),for example
	os.chdir("/content/drive/My Drive/Colab Notebooks") 
3.run the notebook

References
Rotman M, Wolf L. Shuffling recurrent neural networks[C]//Proceedings of the AAAI Conference on Artificial Intelligence. 2021, 35(11): 9428-9435.
Yu Z, Liu G. Sliced recurrent neural networks[J]. arXiv preprint arXiv:1807.02291, 2018.