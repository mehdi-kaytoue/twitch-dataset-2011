# The Twitch.tv 2011 dataset
by Mehdi Kaytoue, [Acces directly to the dataset on google drive](https://drive.google.com/drive/folders/0B0o_VYpo5luIeVAtLUpBQVp2RTg?usp=sharing)

#####A few notes by the author
This dataset gives the whole state of Twitch.tv every 5 minutes, from Sept. 2011 to Jan. 2012:
it gives the list of all active channels and several informations about each of them.
As this dataset is complete and built in the very early stage of Twitch.tv,
it is of high interested for studying (video game) live streaming.

This dataset was originally created and studied in a scientific article:
> Mehdi Kaytoue, Arlei Silva, Loïc Cerf, Wagner Meira Jr and Chedy Raïssi. 
> Watch me playing, I am a professional: a first study on video game live streaming"
> In International Workshop on Mining Social Network Dynamics (MSND)
> in conjunction with the conference WWW'2012. April 16, 2012. Lyon, France.

The goal of this page is to maintain an access to this dataset, and hopefully, 
to invite others data scientists to share their datasets on Twitch.tv.

**The original article**: http://dl.acm.org/citation.cfm?doid=2187980.2188259
**If you use this dataset, please cite us**: http://dblp.uni-trier.de/rec/bibtex/conf/www/KaytoueSCMR12
**Articles citing this work** (**58** on 01/15/2017): https://scholar.google.com/scholar?oi=bibs&hl=fr&cites=11987539755633476248

##### Dataset
A little description is provided 

    - Period of acquisition: September 29, 2011 - January 9, 2012 (every 5 minutes)
    - Rough data: 28,292 XML files -- Each filename gives the time of crawling in millisecond (epoch GMT -3)
    - Cleaned Data: more than 24 millions of tuples in CSV format (channel, timestamp, nbViewers, other info)
    - Other info for cleaning the data
        * Streamers logins list: all (129,332), closed (309), illegal (769)
        * Cleaned game list: 375 games
        * Missing files: missing (746), corrupted (86), that is less than 0.3% of missing data points

[Acces to the dataset on google drive](https://drive.google.com/drive/folders/0B0o_VYpo5luIeVAtLUpBQVp2RTg?usp=sharing)
