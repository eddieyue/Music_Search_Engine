Music Search Engine
====================

In this project, I built a music search engine. By Using simple signal analysis, I converted each song into a series of short strings, each representing a peak in the audio signal. Then, I stored these hashes in a database, allowing fast queries for specific sounds of interest. 

Process Music Data
===================

As a sample, I used abuot 100 songs from the [Free Music Archive](http://freemusicarchive.org), a royalty-free music source. 

Here is a demo for processing and displaying the music data, [Demo Notebook](http://nbviewer.ipython.org/github/eddieyue/Music_Search_Engine/blob/master/Demo_Music_Data.ipynb)

Find the Identical Song
=======================


By computing the similar distance for each pair of songs, I successfully identify the 74th, 83rd and 6th, 19th songs are the same after [manual verification](http://nbviewer.ipython.org/github/eddieyue/Music_Search_Engine/blob/master/Verification%20Notebook.ipynb).

Please check the [notebook](http://nbviewer.ipython.org/github/eddieyue/Music_Search_Engine/blob/master/Music_Search_Engine.ipynb) here for detail. 




