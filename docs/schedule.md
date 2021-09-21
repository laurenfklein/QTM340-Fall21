# QTM 340: Current Class-by-Class Schedule

## Introduction and Overview

#### 8/26 - What does it mean to be practical?

* In class: syllabus overview, intro/transcription exercise
  
#### 8/31 - What can you do with text?

* Before class:
	* Read: Li-Young Lee, “[Persimmons](https://www.poetryfoundation.org/poems/43011/persimmons)”
	* **HW0 due**: Video intro (on Canvas)
* In class: close reading and [Voyant](https://voyant-tools.org/) exercise 

#### 9/2 - What can you do with text as data?
* Before class:
	* Read: Farhad Manjoo, "[How Do You Know a Human Wrote This?](https://www.nytimes.com/2020/07/29/opinion/gpt-3-ai-automation.html)"
	* Spend at least 30 minutes playing [AI Dungeon](https://play.aidungeon.io/)
	* **HW1 due**: Introduce yourself with GPT-2 (on Canvas)
* In class: demo JupyterHub / Jupyter Notebook ([class notebook](../notebooks/class3-jupyter-intro.ipynb))

#### 9/7 - What *should* you do with text as data?
* Before class:
	* Read: Michael Whitmore, “[Text: A Massively Addressable Object](https://dhdebates.gc.cuny.edu/read/untitled-88c11800-9446-469b-a3be-3fdb36bfbd1e/section/402e7e9a-359b-4b11-8386-a1b48e40425a)"
	* Read: Emily M. Bender and Timnit Gebru et al., “[On the Dangers of Stochastic Parrots: Can Language Models Be Too Big?](https://dl-acm-org.proxy.library.emory.edu/doi/pdf/10.1145/3442188.3445922)” 
* In class: discussion and more intro to Jupyter / Python ([class notebook](../notebooks/class3-jupyter-intro.ipynb))

## Unit 1: Turning Text into Data

#### 9/9 - Platforms and People
* Before class:
	* Read: Lilly Irani, “[Justice for ‘Data Janitors’](https://www.publicbooks.org/justice-for-data-janitors/)”
	* Watch: Andrew Norman Wilson, "[Workers Leaving the Googleplex](https://vimeo.com/15852288)"
	* Read: Astrid Smith and Bridget Whearty, “All the Work You Do Not See” (Canvas) 
	* **HW2 due**: Intro to Python / Strings ([HW2 notebook](../notebooks/hw2-python-strings.ipynb))
* In class: getting started with web scraping and HTML ([class notebook](../notebooks/class5-web-scraping-preview.ipynb) and [completed version](../notebooks/class5-web-scraping-preview-complete.ipynb))

#### 9/14 - Web Scraping

* Before class:
	* Read: Astead Herndon et al.,, “[What Do Rally Playlists Say About the Candidates?](https://www.nytimes.com/interactive/2019/08/19/us/politics/presidential-campaign-songs-playlists.html)”
	* Read: Hanah Anderson and Matt Daniels, “[Film Dialogue](https://pudding.cool/2017/03/film-dialogue/)”
* In class: web scraping on the open web ([class notebook](../notebooks/class6-web-scraping-NYT.ipynb) and [completed version](../notebooks/class6-web-scraping-NYT-complete.ipynb))

#### 9/16 - APIs

* Before class:
	* Read: Xavier Adam, “[An Illustrated Introduction to APIs](https://medium.com/epfl-extension-school/an-illustrated-introduction-to-apis-10f8000313b9)” and “[API Whispering 101](https://medium.com/epfl-extension-school/api-whispering-101-e04fbb5a08fd)”
	* **Quiz 1 due**: Scraping song lyrics from Genius.com
* In class: APIs ([class notebook #1: API intro](../notebooks/class7-accessing-apis.ipynb) ([completed version](../notebooks/class7-accessing-apis-complete.ipynb)) and [class notebook #2: Genius API](../notebooks/class7-genius-api.ipynb) ([completed version](../notebooks/class7-genius-api-complete.ipynb)))

#### 9/21 - Text Parsing / Regular Expressions

* Before class:
	* Read: Joel Spolsky, “[The Absolute Minimum Every Software Developer Absolutely, Positivitely Must Know About Unicode and Character Sets (No Excuses!)](https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/)
	* Optional more technical version of the previous post: David Zentgraf, "[What Every Programmer Absolutely, Positively Needs to Know about Encodings and Character Sets to Work with Text](https://kunststube.net/encoding/)"
	* Also optional but very interesting: Miriam Sweeney and Kelsea Whaley, “[Technically White: Emoji Skin-Tone Modifiers as American Technoculture](https://firstmonday.org/ojs/index.php/fm/article/view/10060/8048)” 
* In class: text parsing and regex with your song lyrics ([class notebook #1: regex intro](../notebooks/class8-regex-intro.ipynb) ([completed version](../notebooks/class8-regex-intro-complete.ipynb)) and [class notebook #2: regex w/ song lyrics](../notebooks/class8-regex-with-song-lyrics.ipynb) ([completed version](../notebooks/class8-regex-with-song-lyrics-complete.ipynb)))

## Unit 2: Introductory Data Science with Text

#### 9/23 - Sentiment Analysis 

* Before class:
	* Read: Ethan Reed, “[Measured Unrest in the Poetry of the Black Arts Movement](https://scholarslab.lib.virginia.edu/blog/measured-unrest-in-the-poetry-of-the-black-arts-movement/)”, ["Poems with Pattern and VADER, Part 1: Quincy Troupe"](https://scholarslab.lib.virginia.edu/blog/poems-with-pattern-and-vader-part-1-quincy-troupe/), ["Poems with Pattern and VADER, Part 2: Nikki Giovanni"](https://scholarslab.lib.virginia.edu/blog/poems-with-pattern-and-vader-part-2-nikki-giovanni/)
	* Read: Sujay Khandekar et al., “[Opico: A Study of Emoji-first Communication in a Mobile Social App](https://dl-acm-org.proxy.library.emory.edu/doi/pdf/10.1145/3308560.3316547)” 
	* **Quiz 2 due**: Scraping song lyrics using the Genius API
* In class: sentiment analysis 

#### 9/28 - Natural Language Processing 101, day 1 

* Before class:
	* Read: Patrick Juola, “[How a Computer Program Helped Show J.K. Rowling Wrote A Cuckoo’s Calling](https://www.scientificamerican.com/article/how-a-computer-program-helped-show-jk-rowling-write-a-cuckoos-calling/)”
	* Read: Milo Beckman, “[These are the Phrases Each GOP Candidate Uses Most](https://fivethirtyeight.com/features/these-are-the-phrases-each-gop-candidate-repeats-most/)”
	* **Quiz 3 due**: Sentiment analysis of your song lyrics 
* In class: word counts, n-grams, lexicons  

#### 9/30 - Natural Language Processing 101, day 2 
* Before class:
	* Read: Maarten Sap et al., “[Connotation Frames of Power and Agency in Modern Films](https://aclanthology.org/D17-1247.pdf)”
	* Maria Antoniak et al, “[Narrative Paths and Negotiation of Power in Birth Stories](https://maria-antoniak.github.io/resources/2019_cscw_birth_stories.pdf)”
	* **HW3 due**: Named entity recognition (NER), part-of-speech (POS) tagging
* In class: Guest lecture, [Maria Antoniak](https://maria-antoniak.github.io/), Cornell  

#### 10/5 - Turning Words into Numbers
* Before class:
	* Read: Daniel Jurafsky & James H. Martin, ["Vector Semantics & Embeddings": SECTIONS 6-6.3](https://web.stanford.edu/~jurafsky/slp3/6.pdf)
	* **Quiz 4 due**: Counting and collocating with emoji 
* In class: intro to scikit-learn

#### 10/7 - (Textual) Information Retrieval 

* Before class:
	* Read: Matt Daniels, “[The Language of Hip Hop](https://pudding.cool/2017/09/hip-hop-words/)”
	* Read: Daniel Jurafsky & James H. Martin, ["Vector Semantics & Embeddings": SECTIONS 6.5-6.6](https://web.stanford.edu/~jurafsky/slp3/6.pdf)
	* Optional: Lauren Klein, "[Dimensions of Scale](https://drive.google.com/file/d/1RvcTMegIw0sd9qV4XAIrU83Ud5558CSR/view)" 
* In class: TF-IDF and PMI/PPMI; intro of final project  

#### [ FALL BREAK ]

## Unit 3: Modeling Text as Data I

#### October 14 - Topic Models

* Before class:
	* Read: Lucy Li and David Bamman, “[Gender and Representation Bias in GPT-3 Generated Stories](https://aclanthology.org/2021.nuse-1.5.pdf)”
	* Read: Richard Jean So, “Consecration: The Canon and Racial Inequality,” from *Redlining Culture* (Canvas) 
* In class: topic modeling

#### October 19 - Word Embedding Models 

* Before class:
	* Read: Lauren Klein and Sandeep Soni, “[How Words Lead to Justice](https://www.publicbooks.org/how-words-lead-to-justice/)” 
	* Read: Laura K. Nelson, “Leveraging the Alignment Between Machine Learning and Intersectionality” (Canvas) 
	* **HW4 due**: Word embedding notebook
* In class: Guest lecture, [Dr. Sandeep Soni](https://sandeepsoni.github.io/), UC Berkeley  	

#### October 21 - Data, Pandas, Projects, day 1
* Before class:
	* Explore: Ben Schmidt, “[Gendered Language in Teacher Reviews](http://benschmidt.org/profGender)” 
	* Read: Anelise Hanson Shrout, ["(Re)Humanizing Data: Digitally Navigating the Bellevue Almshouse"](https://crdh.rrchnm.org/essays/v01-10-(re)-humanizing-data/)
	* Optional: Jessica Marie Johnson, “Markup Bodies” (Canvas)
	* **Quiz 5 due**: Exploratory research exercise  
* In class: pandas; project brainstorming session 

#### October 26 - Data, Pandas, Projects, day 2
* Before class:
	* Read: Timnit Gebru et al., “[Datasheets for Datasets](https://arxiv.org/pdf/1803.09010.pdf)”
	* Catherine D’Ignazio and Lauren Klein, “[The Numbers Don’t Speak for Themselves](https://data-feminism.mitpress.mit.edu/pub/czq9dfs5/release/2),” from *Data Feminism*  
	* **Final project prep (FPP) #1 due**: Formal project brainstorm 
* In class: pandas ii; discussion of data and its limits  
	
#### October 28 - Data, Pandas, Projects, day 3
* Before class:
	* Read: Melanie Walsh, “The Challenges and Possibilities of Social Media Data” (Canvas)
	* Read: Colored Conventions Project, “[Introduction to CCP Corpus](https://coloredconventions.org/about-records/ccp-corpus/)”
	* Explore COVID Black, [Homegoing](https://www.covidblack.org/homegoing) 
* In class: pandas iii; more project discussion, more data discussion  

## Unit 4: Modeling Text as Data II

#### November 2 – Classification, day 1
* Before class:
	* Read: Dan Sinykin and Edwin Roland, ["Against Conglomeration: Nonprofit Publishing and American Literature after 1980"](https://post45.org/2021/04/against-conglomeration-nonprofit-publishing-and-american-literature-after-1980/)
	* **HW5 due**: Classification part 1
* In class: classification, part 2

#### November 4 – Classification, day 2 

* Before class:
	* Read: Terra Blevins et al., “[Automatically Processing Tweets from Gang-Involved Youth: Towards Detecting Loss and Aggression](https://www.aclweb.org/anthology/C16-1207)”
	* **FPP #2 due**: Datasheet OR project proposal 
* In class: Guest lecture tbd 

#### November 9 – Clustering (and maybe more on neural networks tbd) 

* Before class: 
	* Read: Ben Schmidt, "[Genre, Manifolds, and AI](http://benschmidt.org/post/2021-03-08-genre-and-manifolds/genres-and-manifolds/)"
	* Read: Matthew Wilkens, "Genre, Computation, and the Varieties of 20th Century U.S. Fiction" (Canvas)
* In class: clustering 

#### November 11 - BERT (Bidirectional Encoder Representations from Transformers)

* Before class:
	* Read: Ted Underwood, ["How Predictable Is Fiction?"](https://tedunderwood.com/2020/07/05/how-predictable-is-fiction/)
	* Read: Lucy Li and David Bamman, “[Characterizing English Variation across Social Media Communities with BERT](https://arxiv.org/abs/2102.06820)” 
	* **FPP #3 due**: Datasheet OR project proposal 
* In class: sentiment analysis with BERT and next sentence prediction

#### November 16 – Arguing with models
* Before class:
	* Read: Dong Nguyen et al., “[How we do things with words: Analyzing text as social and cultural data](https://arxiv.org/pdf/1907.01468.pdf)”
* In class: Guest lecture, [Lucy Li](https://lucy3.github.io/), UC Berkeley

#### November 18 – Arguing with models
* Before class:
	* Read: Richard Jean So, ["All Models are Wrong"](https://www-mlajournals-org.proxy.library.emory.edu/doi/pdf/10.1632/pmla.2017.132.3.668)”
	* Read: Safiya Noble, “Introduction” and “Searching for Black Girls” from *Algorithms of Oppression: How Search Engines Reinforce Racism* (Canvas) 
	* **FPP #4 due**: Final project first pass
* In class: discussion of models and their limits 

#### [ THANKSGIVING BREAK ]

## Unit 5: Final Projects and Course Wrap-Up
#### November 30 – Project Presentations

#### December 2 – Project Presentations

#### December 7 – Course wrap-up and assessment 

### FINAL PROJECTS DUE DECEMBER 9TH, 2PM ET 


*This syllabus draws from previous iterations of QTM 340 taught by myself and [Dan Sinykin](http://www.dansinykin.com/). It also incorporates materials and resources developed by [Melanie Walsh](https://melaniewalsh.github.io/Intro-Cultural-Analytics/welcome.html), [Jinho Choi](https://github.com/emory-courses/data-science), [Alison Parrish](http://www.decontextualize.com/teaching/), [David Mimno](https://mimno.infosci.cornell.edu/info3350/), [David Bamman](http://people.ischool.berkeley.edu/~dbamman/info256.html), [Ryan Cordell](http://s17hda.ryancordell.org), and [Ben Schmidt](http://benschmidt.org/HDA19/), as well as suggestions and other input from Heather Froehlich, Ted Underwood, Jacob Eisenstein, Jim Casey, Taylor Arnold, Lauren Tilton, Lisa Rhody, Eileen Clancy, and the Colored Conventions Project Team.* 
