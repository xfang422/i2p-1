# Practical Overview

## To Dos

- [] Export Docker conda environment to Huanfa
- [] Add Inside Airbnb csv.gz file to Git LFS next to Geopackage.
- [] Record videos of installing and running both Vagrant and Conda installers. [**Huanfa to record a Windows version**]
  - Setting up a directory for CASA work (with subdirectories for each class)
  - Downloading and installing all relevant software
  - Downloading configuration files for installation (where to save)
  - Running installation
  - Any cleanup involved after.
  - Starting JupyterLab
  - Downloading a notebook
  - Launching a notebook
  - Shutting down the notebook
  - Shutting down the server
- How to deal with installation and start-up problems?
  - Work with PGTAs to deal with individual installation issues.
  - Support PGTAs so that they know what's going on too!
  - Simplify installation options: either vagrant *or* YAML (drop VirtualBox for this year).
  - Remind students that they need to get this sorted ASAP.

## General Notes

- I2P is optional for both CASA programmes.
- QM is *mandatory* for both CASA programmes.
- Quiz function in Moodle: one quiz per week of 5–8 questions covering all video and related content (e.g. readings, etc.).
- Pattern
  - 30 minutes max for Q&A at the start of class
    - Based off of Padlet input? So more of an '&A' than Q&A.
  - 30 minutes in breakout rooms on readings?
  - Use Zoom & Polls
    - Have to set up and run as a Webinar
    - So no student participation orally... all questions must be typed.
  - Demonstration Data Set
    - 2019 Crime Data for Chicago: location, timestamp, types (https://data.cityofchicago.org/Public-Safety/Crimes-2019/w98m-zvie).
    - For 'We Do' section need to reconcile with the Zoom Webinar format (use polls? *Good idea in principle as they can vote on what to do next but we need to plan ahead on this...*).

## Syllabus

### Week 1: Setting Up

#### Theoretical Content

- What are We Doing in this Module?
- Making the Most of this Module
- Thinking Computationally
- Computers in Urban Studies

#### Technical Content

- Some useful additional material:
  - https://www.taniarascia.com/setting-up-a-brand-new-mac-for-development/
- Installing the VM
- Introducing Markdown
- The Command Line / Terminal / PowerShell
  - https://www.taniarascia.com/how-to-use-the-command-line-for-apple-macos-and-linux/
  - http://swcarpentry.github.io/shell-novice/
- The File System
- Git & Version Control
  - Setting up Git/GitHub
  - http://swcarpentry.github.io/git-novice/

#### Linking Content/Activities to Next Week

- Readings
  - Burton (1963): **Need to post copy online!**
  - Arribas-Bel & Reades (2018) Geography and computers: Past, present, and future, *Geography Compass* [DOI](https://doi.org/10.1111/gec3.12403)
  - Muller, C.L. and Kidd, C. (2014) Debugging geographers: teaching programming to non-computer scientists, *Journal of Geography in Higher Education* [DOI](https://www.tandfonline.com/doi/full/10.1080/03098265.2014.908275?casa_token=P8SfW5R9L4cAAAAA%3ALBobLToXXrdqN2ilafffb2udotXFCoeDZsJE4UPbRWMaZPCpzKmOE6R-z6mreOrABwXEET9hC--D)
- Videos

### Week 2: Foundations 1 (Recapping the Basics)

#### Theoretical Content

#### Technical Content

- Variables
- Lists & Dicts 
- Simple Functions
- Errors & Try/Except

#### Linking Content/Activities to Next Week

- Readings
  - Etherington, T.R. (2015) Teaching introductory GIS programming to geographers using an open source Python approach, *Journal of Geography in Higher Education* [DOI](https://doi.org/10.1080/03098265.2015.1086981)
  - Donoho (2017) 50 Years of Data Science, *Journal of Computational and Graphical Statistics* [DOI](https://doi.org/10.1080/10618600.2017.1384734)
  - Unwin, D. (1980) Make your practical open-ended, *Journal of Geography in Higher Education* [DOI](https://doi.org/10.1080/03098268008708772)
- Videos

### Week 3: Foundations 2 (Recapping the Hard Bits)

#### Theoretical Content

- How to think abstractly
- What's OOP?
- Representing data in a data structure (part 2)

#### Technical Content

- Reusing Functions
- Packages
- Methods
- Classes & Objects
- From LOLs to Data Structures

#### Linking Content/Activities to Next Week

- Readings
  - Cox, M. and Slee, T. (2016) How Airbnb's data hid the facts in New York City, *Inside Airbnb* [http://insideairbnb.com/reports/how-airbnbs-data-hid-the-facts-in-new-york-city.pdf](http://insideairbnb.com/reports/how-airbnbs-data-hid-the-facts-in-new-york-city.pdf)
  - D'Ignazio, C. and Klein, L.F. (2020), Chapter 5: Unicorns, Janitors, Ninjas, Wizards, and Rock Stars in *Data Feminism*; [Pre-review Chapter URL](https://bookbook.pubpub.org/pub/fcshwhq6)
- Videos

### Week 4: Numeric Data

#### Theoretical Content

- Representing data in a data structure (part 2)
- Linking data

#### Technical Content

- Structured Data 1: CSVs & TSVs
- Introducing Pandas
- Reading/Writing Data in Pandas
- Data Types in Pandas
- Summarising Data in Pandas
- Indexes in Pandas ***[JR: Move later???]***
- Basic Plots in Pandas
- *Structured Data 2: JSON [**This is too much; leave for DSSS**]*
- *Joins (Non-Spatial)? [**This is too much. Would like to leave it for DSSS**]*

#### Linking Content/Activities to Next Week

- Readings
  - D'Ignazio, C. and Klein, L.F. (2020), Chapter 4: What Gets Counted Counts in *Data Feminism*; [Pre-review URL](https://bookbook.pubpub.org/pub/rykaknh1)
  - Kitchin, R. and Lauriault, T.P. and McArdie, G. (2016), Chapter 2: Smart Cities and the Politics of Urban Data in *Smart Urbanism* Marvin, Luque-Ayala, McFarlane (Eds.)
- Videos

### Week 5: Spatial Data

#### Theoretical Content

- Focus on strategies for thinking about data in a spatial context (*e.g.* what does buffering allow you to *do*)
- I'm a bit worried by the risk of dropping spatial joins

#### Technical Content

- Recap: Classes & Inheritance
- Introducing: GeoPandas! (as good example of inheritance)
- Projection & Reprojection **[GIS will cover this, and most, if not all, I2P students will attend GIS. It is good to teach projection in Python and Geopandas, especially since it has changed with Geopandas 0.6]**
- Reading/Writing Geodata in Pandas
- Basic Maps
- Simple Spatial Operations (e.g. Buffers & Centroids)
- *Joins & Spatial Joins [**This looks like too much; move later**]*

#### Linking Content/Activities to Next Week

- Readings
  - Elwood, S. and Wilson, M. (2017) Critical GIS pedagogies beyond 'Week 10 Ethics', *International Journal of Geographical Information Science* [DOI](https://doi.org/10.1080/13658816.2017.1334892)
  - ???
- Videos

### Week 6: Textual Data

#### Theoretical Content

- Handling text in a quantitative way

#### Technical Content

- Pattern Matching & Regular Expressions
- Stemming
- Lemmatisation 
- The 'Bag of Words'
- TF/IDF
- Pandas.apply()
- Sampling 
- Random Seeds **[This is important. Many students of this year asked what random seeds are in various modules]**
- Word Clouds?

#### Linking Content/Activities to Next Week

- Readings
  - D'Ignazio, C. and Klein, L.F. (2020), Chapter 6: The Numbers Don't Speak for Themselves in *Data Feminism*; [Pre-review URL](https://bookbook.pubpub.org/pub/6ui5n4vo)
  - Landlsey (2016) [https://doi.org/10.1080/21681376.2016.1177466](https://doi.org/10.1080/21681376.2016.1177466) 
- Videos

### Week 7: Visualising Data

#### Theoretical Content

- Dealing with Distributions & Outliers

#### Technical Content

- Seaborn
- Matplotlib
- Fonts, Annotations, and Labels
- Colours Schemes
- Interacting with labels, axes, rotation, etc.
- Automation (e.g. using a function to apply same style to all elements)
- Automation (e.g. using a function to create a comparable plot for each columns)

#### Linking Content/Activities to Next Week

- Readings
  - D'Ignazio, C. and Klein, L.F. (2020), Chapter 3: On Rational, Scientific, Objective Viewpoints from Mythical, Imaginary, Impossible Standpoints in *Data Feminism*; [Pre-review URL](https://bookbook.pubpub.org/pub/8tjbs2x5)
  - McNeill (2016), Chapter 3: IBM and the Visual Formation of Smart Cities, *Smart Urbanism* Marvie, Luque-Ayala, McFarlane (Eds.)
- Videos

### Week 8: Classifying Data

#### Theoretical Content

- From classes in maps *back* to the distribution

#### Technical Content

- Standardisation
- Normalisation
- Transformations more generally 
- Classification Schemes & The Distribution
- Working with sklearn
- Working with PySAL for classification (Fisher-Jenks, etc.) **[This may be too much. Perhaps focusing on sklearn and briefly introducing PySAL?]**
- Interacting with Legends and Colour Schemes

#### Linking Content/Activities to Next Week

- Readings
  - Fischer-Baum, R. (2014), Whose Good Life Are These Coffee Shapes "Positive Markers" Of? *Gawker* [URL](https://gawker.com/whose-good-life-are-these-coffee-shops-positive-marker-1561899283)
  - Badger, E. and Bui, Q. and Gebeloff, R. (2019) Neighborhood Is Mostly Black. The Home Buyers Are Mostly White. *New York Times* [URL](https://www.nytimes.com/interactive/2019/04/27/upshot/diversity-housing-maps-raleigh-gentrification.html)
  - Bunday, B.D. (????) *A Final Tale* or *You Can Prove Anything with Figures* [URL](https://www.ucl.ac.uk/~ucahhwi/AFinalTale.pdf)
- Videos

### Week 9: Dimensionality

#### Theoretical Content

- Dealing with the 'Data Space' — focus on abstraction of data into dimensions regardless of scale or number of dims.

#### Technical Content

- Regression / Correlation & Cross-Correlation
- t-SNE
- PCA **[I would like to focus on PCA, as it can be integrated with regression/classification/clustering]**
- UMAP

#### Linking Content/Activities to Next Week

- Readings
  - Cima, R. (2014) The Most and Least Diverse Cities in America, *Priceonomics* [URL](https://priceonomics.com/the-most-and-least-diverse-cities-in-america/) [**But need to provide PDF as figures now missing**]
  - Cima, R. (2015) The Least Segregated Cities in America, *Priceonomics* [URL](https://priceonomics.com/the-most-and-least-segregated-cities-in-america/) [**But need to provide PDF as figures now missing**]
  - Shapiro, W. and Yavuz, M. (2017) Rethinking 'distance' in New York City *Medium* [URL](https://medium.com/topos-ai/rethinking-distance-in-new-york-city-d17212d24919)
- Videos

### Week 10: Clustering

#### Theoretical Content

- Groups and Differences in Data
- Thinking about Distance in Data

#### Technical Content

- DBSCAN 
- HDBSCAN
- pysal.esda.ADBSCAN

#### Linking Content/Activities to Next Week

- Readings
  - Wolf, L. *et al.* (2020) Quantitative geography III: Future challenges and challenging futures, *Progress in Human Geography* [DOI](https://doi.org/10.1177%2F0309132520924722)
  - Arribas-Bel & Singleton (2019) Geographic Data Science, *Geographical Analysis* [DOI](https://doi.org/10.1111/gean.12194)
- Videos
