# Baptisms in the Catholic Parish of Juncewo, Poland

These files are my personal index of Juncewo baptisms, created by 
examining microfilms available from the FamilySearch microfilm
library. Two microfilms are involved:

- 2152673, which has been digitized and is available online at
  FamilySearch.org.

- 2152674, which has *not* been digitized. Since FamilySearch is
  no longer loaning out microfilms, it is not really available unless
  you go to Salt Lake City. However, there is a copy at my local
  Family History Center; I got it on long-term loan before FamilySearch
  stopped loaning out films. I have been working my way through it.

The files are in two formats:

- .ods, which is the spreadsheet format used by LibreOffice. 

- .csv, which is a cross-platform text format in which the fields on 
  each row are separated by commas. I'm using the UTF-8 character set,
  so you'll want to make certain that is selected when you import the
  files; this is a bit fiddly with Excel (see below).

The .ods files are the master files; when I am working on the index, I
update the .ods files and generate new .csv files from them.

-----

### Caveats

There are several things to be aware of when using these files:

- They are riddled with typos. I have not done any proofreading on most
  of them. Proofreading has been minimal when I have done it. And I've
  lost track of which bits I've done and which I haven't.

- It took me a while to catch onto things like the fact that Starezyn
  is the name of a town, not an abbreviation for Starezynek (and the
  same regarding Damaslaw and Damaslawek). There are abbreviations that
  I did not understand until some time later; I did not go back and fill
  in the abbreviations when I found out what they were.

- I do not speak Polish and am not very good at Latin.

- The handwriting is, at times, nigh on illegible. I refer to 1851 as
  "peak illegibility".

- There is one page that has more children listed than parents with no
  obvious sets of twins. I've done my best to figure out which children
  go to which parents, but I may have gotten it wrong.

-----

### The Files

The following data sets are available:

- **Juncewo-2152673-Item4**: Baptisms from 1732 through 1779. My index of 
  this item is incomplete.

- **Juncewo-2152673-Item5**: Baptisms from 1779 through 1802. This part of
  the microfilm also contains marriages and deaths, but those
  are *not* included in this index.

- **Juncewo-2152673-Item6**: Baptisms from 1802 through 1836.

- **Juncewo-2152674-Item1**: Baptisms from 1837 through 1853.

- **Juncewo-2152674-Item2**: Baptisms from 1853 through 1865. My index of
  this item is incomplete.

I will be working on the incomplete items and then doing some proofreading,
but the going will be slow. I will probably be concentrating on 
Juncewo-2152673-Item4 for the foreseeable future, because I can do that
without access to the microfilm.

-----

### The Data

Within each file, the data is arranged in the following columns:

- **A**: The microfilm number.

- **B**: The frame number. For 2152673, this is the frame number according
  to the microfilm reader app. For 2152674, this is the frame number 
  shown at the top of each frame of the film.

- **C**: The primary date of the record. Most of the time, this is the
  date of the baptism. Sometimes the record contains only one date and
  it is not clear whether it is a baptismal date or a birth date. If a
  record contains *only* a birth date, the date appears both here and
  in column K.

  Dates are recorded as an 8-digit number in the format yyyymmdd.

- **D**: The name of the town associated with the family. 

- **E**: The sex of the child. This should be "m" or "f", but there may
  be a few records in which it is not clear. I don't recall whether I
  left this field blank in that case, or put "unknown" here.

- **F**: The name of the child.

- **G**: Information about the father. This includes:

  - Given name, which is capitalized.

  - Surname, if available, capitalized and enclosed in slashes (e.g.,
    /Tefelski/). There is at least one instance in which a two-word
    surname is recorded.

  - Other information about the father, such as profession. This is
    not capitalized. There may be an abbreviation, if one was used and
    I did not know what it stood for when I created the entry.

- **H**: Information about the mother. Same format as column G.

- **I**: Information about the godfather. Same format as column G; note
  that if the information contains a town name (such as "de Juncewo"), the
  name of the town is capitalized.

- **J**: Information about the godmother. Same format as column I.

- **K**: Birth date, if available, in the same format as column C.

- **L** and subsequent columns: Notes about the record. 

-----

### Loading a UTF-8 .csv file into Excel

This is for Excel 2010, which is the version I have. Your mileage may vary.

- Create a blank workbook.

- Select the "Data" tab at the top and select "From Text" in the "Get External 
  Data" category.

- Select the file and click "Import". Excel will notice that your file
  is delimited text.

- To the right of "File *o*rigin", select "Unicode (UTF-8)". Click "Next".

- Under "Delimiters", make certain that Comma is selected. Click "Next".

- Under "Column data format", make certain that General is selected.
  Click "Finish".

- It will ask you where to put the data. Since you just created a blank
  worksheet, "Existing worksheet" works and cell =$A$1 is just fine.
  Click "OK".

You should see the data with all the glorious Polish characters intact.

