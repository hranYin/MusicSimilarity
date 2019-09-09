# Music_Similarity
Research code for my dissertation while studying a MSc in Computer Science at University of Birmingham.

GTZAN data set: http://opihi.cs.uvic.ca/sound/genres.tar.gz

To run the software python 3 must be installed, the easiest method is still install anaconda as it contains most of the Dependancies.
Each notebook requires a directory of audio files with '.wav' extension in order to function correctly. The path variable must be updated to this directory.

Dependancies: librosa, numpy, Jupyter Notebook
Optional packages: pandas, tqdm, matplotlib.pyplot

Local Senstive Hashing has been implemented using Steve Tjoa version which can be found here: https://musicinformationretrieval.com/lsh_fingerprinting.html

Evaluation of the methods used are made using code provided by Matrix Profile Foundation, the specific algorithm used is SiMPle.
SiMPle source code: https://sites.google.com/site/ismir2016simple/SiMPle_code.zip?attredirects=0&d=1

Source code and other examples can be found at: https://sites.google.com/site/ismir2016simple/
