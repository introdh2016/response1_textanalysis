
# Response 

The 500-1500 word response should explain the data set, the initial findings, and how one would go about further exploring the data set/ findings/ arguments. It should  also address the following questions:
- Which data did you select for the corpus? Make sure to specificy the kind of data and periodization. 
- Why the number of topics? 
- What are the initial findings and/or possible arguments? In other words, what do these topics tell us?
- What are the possibilities and limitations of topic modeling?

More details:

 
- Images: Include images of your topic models. Save the photos in this Github repo. To get the image link, right click and select "Copy Link Address". It should look like: https://github.com/introdh2016/response1_textanalysis/blob/master/NAMEOFYOURIMAGE.jpg?raw=true .... For example: https://github.com/introdh2016/response1_textanalysis/blob/master/IMG_3680.jpg?raw=true
- Citations: Please use a modified  format since citations will be drawn from course readings. Cite relevant readings using in-text/ parenthetical citations: (author, publication, date). Ex. (Blevins, personal blog, 09-09-2009) or (Goldstone and Underwood, JDH, 2012). 
- Grading: [Rubric](https://github.com/introdh2016/response1_textanalysis/blob/master/response_rubric.pdf)


# Corpus

## Jstor
[JStor Data for Research](http://about.jstor.org/service/data-for-research) provides machine-readable data from JStor, a digital library of academic journals, books, and primary sources.

## Downloading Data

It takes several days for Jstor to send the data. Make sure to make this request immediately. Visit [here](fr.jstor.org). Set up an account and select your data. Select Data Type: "Citations Only" and "Word Counts" and Output Format: "CSV".  If the data has more than 1000 records, there are two options. You can make several requests to capture all the data or you need to select a subset. If you do not, you will get a random generated subset from JStor. Do not use a random subset. 

## 
Once you have the data, please email me. The data will need to be processed and we are using Andrew Goldstone’s [Count2Text](https://github.com/agoldst/dfr-analysis/blob/master/count2txt) technique on GitHub.  If you are comfortable, feel free to do it yourself! Here is how:

1. Download the code from github. Save the code to your Desktop.
2. In the terminal, type:

```sh
chmod +x ~/Desktop/count2text
```

3. Then move into the director with your CSV files from Jstor. Once in the folder, type:

```sh
~/Desktop/count2text.pl --multifile  *.CSV
```

4. Go back to your file with the Jstor data. Go into wordcounts and you'll see .CSV and .txt files. For Mallet, you will need to put the .txt files in a different folder. 







