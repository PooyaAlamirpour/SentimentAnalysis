[image1]: ./Images/pos.png "Result 1"
[image2]: ./Images/neg.png "Result 2"

## Deep Learning - Sentiment Analysis

In this repository, I am going to implement a Sentiment Analysis on the IMDB reviews. So based on this project user can put his opinion for each movie he wants, then he will receive a suitable sentiment about it. One of the fantastic parts of this project would be deploying this project into a server as a Web Application. So a user can open a browser and puts his data and gets feedback.

## Installation
For running this project you should install some requirements such as [Anaconda](http://conda.pydata.org/docs). 
> Conda is an open source package management system and environment management system 
for installing multiple versions of software packages and their dependencies and 
switching easily between them. It works on Linux, OS X and Windows, and was created 
for Python programs but can package and distribute any software.

Download the latest version of `miniconda` that matches your system.

|        | Linux | Mac | Windows | 
|--------|-------|-----|---------|
| 64-bit | [64-bit (bash installer)][lin64] | [64-bit (bash installer)][mac64] | [64-bit (exe installer)][win64]
| 32-bit | [32-bit (bash installer)][lin32] |  | [32-bit (exe installer)][win32]

[win64]: https://repo.continuum.io/miniconda/Miniconda3-latest-Windows-x86_64.exe
[win32]: https://repo.continuum.io/miniconda/Miniconda3-latest-Windows-x86.exe
[mac64]: https://repo.continuum.io/miniconda/Miniconda3-latest-MacOSX-x86_64.sh
[lin64]: https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh
[lin32]: https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86.sh

Before start to work you should define an **Environment** on the Anaconda. You can put this command either on the terminal window such CMD or in the **Anaconda Console Application**.

* __Linux__ or __Mac__: 
	```
	conda create -n SentimentAnalysis python=3.6
	source activate SentimentAnalysis
	```
* __Windows__: 
	```
	conda create --name SentimentAnalysis python=3.6
	activate SentimentAnalysis
	```
	
Now it is time to clone the repositort and run it.
```
git clone https://github.com/PooyaAlamirpour/SentimentAnalysis.git
cd SentimentAnalysis
jupyter notebook
```
The below image indicates the result

![Sample Output][image1]

![Sample Output][image2]
