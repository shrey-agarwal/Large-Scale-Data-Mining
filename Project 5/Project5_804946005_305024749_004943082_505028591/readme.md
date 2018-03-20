The project has been developed and tested in python2 as well as python3 for compatibility. 
But we highly recommend python3

The structure is as follows:
There are six python notebooks (ipynb)

To run the files:
If you already have pre-trained models
1. Set the "load_data" to True
2. Put the data in data folder. (download from the pdf link)
3. Since the data is huge, certain features have been stored in the pickle files and loaded 
later for ease of use. We could not add those models because of their huge size. 
Please train them or set load_data to false. The code will train them for you.
4. File Part 1,2.ipynb contains part 1.1 and 1.2
5. File Part 4,5.ipynb contains part 1.4 and 1.5
6. File part2.ipynb contains the part 2
7. File part3.ipynb contains part3.
None of these files are dependent on each other and can be executed separately.
You will need to extract the data files in txt and then load them for Part 2 and Part 3.
The code will not work otherwise.

By default, we have set the "load_data" to false so that all the models get trained and then used.