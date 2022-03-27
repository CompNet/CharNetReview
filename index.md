## Extraction and Analysis of Fictional Character Networks: A Survey
This page is related to the following article:

V. Labatut and X. Bost, “*Extraction and Analysis of Fictional Character Networks: A Survey*,” ACM Computing Surveys 52(5):89, 2019. DOI: [10.1145/3344548](http://doi.org/10.1145/3344548) -- [arxiv:1907.02704](https://arxiv.org/abs/1907.02704) -- ⟨[hal-02173918](https://hal.archives-ouvertes.fr/hal-02173918)⟩

It aims at hosting an up-to-date list of academic articles related to the extraction and analysis of character networks from works of fiction.

If you use these resources, please cite the above article.

![CitationNet](/docs/assets/images/article_citation.svg)

# Resources
The resources associated to the article are available through the following links:

* [`table_bib.ods`](/docs/assets/data/table_bib.ods): LibreOffice table listing the articles with their main information.
* [`charnets.bib`](/docs/assets/data/charnets.bib): BibTeX file containing the bibliographic entries of these articles, as well as the ones they cite (the latter are not represented in the below graphs).
* [`article_citation.graphml`](/docs/assets/data/article_citation.graphml): article citation network, i.e. graph whose vertices are the listed articles and edges represent them citing each other.
* [`article_cociting.graphml`](/docs/assets/data/article_cociting.graphml): same, but the edges represent how much two articles cite the same bibliographic references.

# List of Academic Works
List of methods designed to extract character networks from fictional works. The *Relationships* column indicates whether the edges correspond to co-occurrences (*Cc.*), conversations (*Cv.*), mentions (*M.*), direct actions (*Ac.*), or affiliations (*Af.*). The *Graph* column shows whether the extracted networks are weighted (*W.*), directed (*Di.*), signed (*S.*), and dynamic (*Dy.*). When the authors experiment with different methods, several values may appear in the same cell. Note that this table has been completed after the publication of the official ACM CS article.

<table>
  <tr>
    <td><b>Work of fiction</b></td>
    <td><b>Reference</b></td>
    <td colspan="5"><b>Relationships</b></td>
    <td colspan="4"><b>Graph</b></td>
    <td><b>Application</b></td>
  </tr>
  <tr>
    <td/><td/><td><b>Cc.</b></td><td><b>Cv.</b></td><td><b>M.</b></td><td><b>Ac.</b></td><td><b>Af.</b></td><td><b>W.</b></td><td><b>Di.</b></td><td><b>S.</b></td><td><b>Dy.</b></td><td/>
  </tr>
  <tr><td>Mozart's <i>Cosi Fan Tutte</i></td><td>\cite{Harary1963}</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>Descriptive analysis</td></tr>
  <tr><td>Murdoch's <i>A Severed Head</i></td><td>\cite{Harary1966a}</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>Shakespeare's <i>A Midsummer Night's Dream</i></td><td>\cite{Stanton1967}</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>Descriptive analysis</td></tr>
  <tr><td>Wagner's <i>Der Ring des Nibelungen</i></td><td>\cite{Mayer1973}</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>Shakespeare's <i>Twelfth Night</i></td><td>\cite{Harary1975}</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>16 fairy tales</td><td>\cite{Auster1980}</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>Descriptive analysis</td></tr>
  <tr><td>Sophocles' <i>Oedipus Rex</i></td><td>\cite{Harary1982}</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>Priestley's <i>Dangerous Corner</i></td><td>\cite{Harary1985}</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>Comparative study</td></tr>
  <tr><td>5 classic novels</td><td>\cite{Knuth1993}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Benchmark for graph processing tools</td></tr>
  <tr><td><i>Marvel</i> comics</td><td>\cite{Alberich2002}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Level of realism</td></tr>
  <tr><td>10 Shakespeare's plays</td><td>\cite{Stiller2003, Stiller2005}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Level of realism</td></tr>
  <tr><td>All of Shakespeare's plays</td><td>\cite{Mutton2004}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N/Y</td><td>Visualization</td></tr>
  <tr><td>Dictionary of Greek and Roman mythology</td><td>\cite{Choi2007}</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N/Y</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td><i>Marvel</i> comics</td><td>\cite{Gleiser2007}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Level of realism</td></tr>
  <tr><td>Hollywood movies, and TV series</td><td>\cite{Weng2007, Weng2007a, Weng2009}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Storyline identification/segmentation</td></tr>
  <tr><td>9 classical plays</td><td>\cite{Voloshinov2008}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Level of realism</td></tr>
  <tr><td>Movies and TV series</td><td>\cite{Park2009, Park2011}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Role detection, story segmentation</td></tr>
  <tr><td><i>Friends</i> TV show</td><td>\cite{Yuan2009, Yuan2010}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Method assessment</td></tr>
  <tr><td>15 Hollywood movies</td><td>\cite{Zhang2009e, Liang2009a, Sang2011, Sang2012}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Face-name matching, Scene segmentation</td></tr>
  <tr><td>Austen's <i>Pride & prejudice</i>, and <i>Emma</i></td><td>\cite{Celikyilmaz2010}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Method assessment</td></tr>
  <tr><td>10 adversarial movies</td><td>\cite{Ding2010}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>Y</td><td>N</td><td>Method assessment</td></tr>
  <tr><td>60 19th century British novels</td><td>\cite{Elson2010, Elson2010a, Elson2012}</td><td>N/Y</td><td>N/Y</td><td>N/Y</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Check literary theories</td></tr>
  <tr><td>20 Hollywood movies</td><td>\cite{Ding2011a}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>Y</td><td>Y</td><td>Community detection</td></tr>
  <tr><td>300 19th century Swedish novels</td><td>\cite{Kokkinakis2011}</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Method assessment</td></tr>
  <tr><td>Toriyama's <i>Dragon Ball</i> vol.32</td><td>\cite{Murakami2011}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Method assessment</td></tr>
  <tr><td>Shakespeare's <i>Hamlet</i>, <i>Macbeth</i>, and <i>King Lear</i></td><td>\cite{Moretti2011a}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Discussion about the characters</td></tr>
  <tr><td>Collection of Greek Tragedies</td><td>\cite{Rydberg2011}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Plot structure comparison</td></tr>
  <tr><td>8 Hollywood movies</td><td>\cite{Tsai2011}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Scene segmentation</td></tr>
  <tr><td>Carroll's <i>Alice in Wonderland</i></td><td>\cite{Agarwal2011, Agarwal2012, Agarwal2013, Agarwal2013a, Agarwal2014a}</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N/Y</td><td>N</td><td>N/Y</td><td>Role detection</td></tr>
  <tr><td>41 19th century novels</td><td>\cite{Elsner2012}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Genre comparison</td></tr>
  <tr><td>Rowling's <i>Harry Potter</i> novels</td><td>\cite{Hutchinson2012}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Method assessment</td></tr>
  <tr><td>The <i>Old Testament</i></td><td>\cite{Lee2012f}</td><td>N</td><td>Y</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Method assessment</td></tr>
  <tr><td>4 European tales</td><td>\cite{MacCarron2012, MacCarron2013, MacCarron2013b, MacCarron2013a, MacCarron2014a, Kenna2016, Kenna2017}</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>N/Y</td><td>N</td><td>Y</td><td>N</td><td>Level of historicity</td></tr>
  <tr><td>19th and 20th century Swedish novels</td><td>\cite{Oelke2012, Oelke2013}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N/Y</td><td>Visualization</td></tr>
  <tr><td>6 canonical European novels</td><td>\cite{Sack2012, Sack2013, Sack2014}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Proto-narrative generation</td></tr>
  <tr><td>Frankel's <i>The Devil Wears Prada</i></td><td>\cite{Yeh2012, Yeh2014}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Face clustering</td></tr>
  <tr><td>Manzoni's <i>I promessi sposi</i></td><td>\cite{Bolioli2013}</td><td>N/Y</td><td>N/Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Method assessment</td></tr>
  <tr><td>Rowling's <i>Harry Potter</i> novels</td><td>\cite{Bossaert2013}</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Study of peer support</td></tr>
  <tr><td>3 classic European novels</td><td>\cite{He2013a, Makazhanov2014}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Method assessment</td></tr>
  <tr><td>10 Hollywood movie scripts</td><td>\cite{Jung2013a}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Role detection</td></tr>
  <tr><td>Homer's <i>Odyssey</i></td><td>\cite{Miranda2013, Miranda2018}</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Level of historicity</td></tr>
  <tr><td>Shakespeare's plays</td><td>\cite{Nalisnick2013, Nalisnick2013a}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Method assessment</td></tr>
  <tr><td>20 novels</td><td>\cite{Park2013, Park2013a, Seo2013, Seo2014}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>Rowling's <i>Harry Potter and the Philosopher's Stone</i></td><td>\cite{Sparavigna2013}</td><td>N</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Level of realism</td></tr>
  <tr><td>3 story books</td><td>\cite{Sudhahar2013}</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Role detection</td></tr>
  <tr><td>173 theater and 580 movie scripts</td><td>\cite{Suen2013}</td><td>N/Y</td><td>N/Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Classification of works</td></tr>
  <tr><td>12 Hollywood movies</td><td>\cite{Tsai2013}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Video summarization</td></tr>
  <tr><td>674 movie scripts</td><td>\cite{Agarwal2014b, Agarwal2016}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Performance evaluation</td></tr>
  <tr><td>238 novels</td><td>\cite{Ardanuy2014, Ardanuy2015}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Classification of works</td></tr>
  <tr><td>250,000 novels, myths and fary tales</td><td>\cite{Bodrova2014}</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Method assessment</td></tr>
  <tr><td>1,800 19th century British and American novels</td><td>\cite{Condello2014}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Comparative study</td></tr>
  <tr><td>Tales and myths</td><td>\cite{MacCarron2014}</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>Level of historicity, Categorization</td></tr>
  <tr><td><i>Das Nibelungenlied</i>, and Shakespeare's <i>Hamlet</i></td><td>\cite{Marazzato2014, Sparavigna2015}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Method assessment</td></tr>
  <tr><td>Rousseau's <i>Les confessions</i></td><td>\cite{Rochat2014a, Rochat2014}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N/Y</td><td>N</td><td>N</td><td>N/Y</td><td>Role detection</td></tr>
  <tr><td>Shakespeare's <i>Hamlet</i> and <i>Othello</i></td><td>\cite{Sparavigna2014a}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td><i>Star Trek</i> and <i>Star Gate</i> movies and TV series scripts</td><td>\cite{Tan2014a, Tan2017, Tan2018a}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Comparative study</td></tr>
  <tr><td>Knowles' <i>The Legends of King Arthur and his Knights</i></td><td>\cite{Trovati2014}</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>Method assessment</td></tr>
  <tr><td>Rowling's <i>Harry Potter</i> series</td><td>\cite{Zhang2014q}</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>20 novels</td><td>\cite{Amancio2015b}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>1,276 movie scripts</td><td>\cite{Gorinski2015}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Script summarization</td></tr>
  <tr><td>1,682 16--20th century German novels</td><td>\cite{Hettinger2015}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Classification of works</td></tr>
  <tr><td>60 19th century British novels</td><td>\cite{Jayannavar2015}</td><td>N</td><td>Y</td><td>N</td><td>Y</td><td>N</td><td>N/Y</td><td>N/Y</td><td>N</td><td>N</td><td>Check literary theories</td></tr>
  <tr><td>200 17--18th century French plays</td><td>\cite{Karsdorp2015}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Character ranking, Visualization</td></tr>
  <tr><td>617 movie scripts</td><td>\cite{Krishnan2015}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>Infer formality level of interactions</td></tr>
  <tr><td>58 German novels</td><td>\cite{Krug2015, Jannidis2016, Krug2020}</td><td>N/Y</td><td>N/Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Role detection</td></tr>
  <tr><td>Homer's <i>Iliad</i></td><td>\cite{Kydros2015}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>Embirikos' <i>The Great Eastern</i></td><td>\cite{Kydros2015a}</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>Shakespeare's <i>Julius Caesar</i></td><td>\cite{Lotker2015}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Detect communities of characters</td></tr>
  <tr><td>6 Hollywood movies</td><td>\cite{Li2015w}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Video summarization</td></tr>
  <tr><td>183 <i>Friends</i> episodes</td><td>\cite{Nan2015}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Method assessment</td></tr>
  <tr><td><i>The Wire</i> script</td><td>\cite{Pope2016}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Role detection</td></tr>
  <tr><td>Zola's <i>Les Rougon-Macquart</i></td><td>\cite{Rochat2015}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Plot structure comparison</td></tr>
  <tr><td>First 6 <i>Star Wars</i> movies</td><td>\cite{Tran2015}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Role detection</td></tr>
  <tr><td>Corpus of Hollywood movies</td><td>\cite{Tran2015a, Tran2017a, Do2018}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Movie summarization</td></tr>
  <tr><td>Large corpora of European plays</td><td>\cite{Fischer2015a, Trilcke2016, Fischer2016, Fischer2017, Fischer2017a}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Check literary theories</td></tr> % also: Descriptive analysis
  <tr><td>46 fantasy novels, and Hugo's <i>Les misérables</i></td><td>\cite{Waumans2015}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Classification of works</td></tr>
  <tr><td>Martin's <i>A Storm of Swords</i></td><td>\cite{Beveridge2016}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>3 modern novels</td><td>\cite{Bonato2016}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Model fitting</td></tr>
  <tr><td>3 TV series</td><td>\cite{Bost2016, Bost2016b, Bost2016c, Bost2018a}</td><td>N/Y</td><td>N/Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N/Y</td><td>Video summarization</td></tr>
  <tr><td>Zhi Ning's <i>Journey to the West Prequel<i></td><td>\cite{Chen2016k}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>Tarentino's <i>Pulp Fiction</i></td><td>\cite{Cipresso2016}</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>Edgeworth's <i>The Absentee</i></td><td>\cite{Falk2016}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Check literary theories</td></tr>
  <tr><td>19th century British novels</td><td>\cite{Grayson2016, Grayson2016a}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N/Y</td><td>Descriptive analysis</td></tr>
  <tr><td>4 novels</td><td>\cite{John2016, John2017, John2019}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Visualization</td></tr>
  <tr><td>Chinese Buddhist Canon</td><td>\cite{Lee2016d}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>10 Hollywood movies</td><td>\cite{Lee2016e, Lee2018}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Recommendation system</td></tr>
  <tr><td>Shakespeare's <i>Julius Caesar</i>, <i>Hamlet</i>, and <i>Othello</i></td><td>\cite{Lotker2016}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>Y</td><td>Study of time flow in dynamic networks</td></tr>
  <tr><td>501 movie scripts</td><td>\cite{Makris2016}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Method assessment</td></tr>
  <tr><td>The <i>Pentateuch</i></td><td>\cite{Massey2016}</td><td>N</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N/Y</td><td>Level of historicity</td></tr>
  <tr><td>Hugo's <i>Les misérables</i></td><td>\cite{Min2016, Min2016a, Min2016c}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N/Y</td><td>Story segmentation</td></tr>
  <tr><td><i>La chanson de Roland</i>, and %Carroll's 
  <tr><td><i>Alice in Wonderland</i></td><td>\cite{Prado2016}</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N/Y</td><td>Descriptive analysis</td></tr>
  <tr><td>Tolkien's <i>Middle-Earth</i> novels</td><td>\cite{Ribeiro2016}</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>All of Shakespeare's plays</td><td>\cite{Rieck2016}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Comparative study</td></tr>
  <tr><td>CMU Movie Summary corpus</td><td>\cite{Srivastava2016}</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>Method assessment</td></tr>
  <tr><td>Homer's <i>Iliad</i></td><td>\cite{Venturini2016}</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Visualization</td></tr>
  <tr><td>First 4 books of Martin's <i>A Song of Ice and Fire</i></td><td>\cite{Wohlgenannt2016}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Method assessment</td></tr>
    <tr><td>Molière's <i>L'école des femmes</i></td><td>\cite{Xanthos2016}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Visualization</td></tr>
  <tr><td><i>Ossian</i> corpus of Scottish epic poems</td><td>\cite{Yose2016}</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>Level of historicity</td></tr>
  <tr><td>3,568 English-language plays from 1550--1900</td><td>\cite{Algee-Hewitt2017, Piper2017}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Check literary theories</td></tr>
  <tr><td>817 movie scripts</td><td>\cite{Chen2017v}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N/Y</td><td>N/Y</td><td>N</td><td>N</td><td>Identify generative model</td></tr>
  <tr><td>4 gospels of the <i>New Testament</i></td><td>\cite{Grandjean2015}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Comparative study</td></tr>
  <tr><td>Staël's <i>Corinne ou l'Italie</i></td><td>\cite{Edmondson2017}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Visualisation</td></tr>
  <tr><td>British Victorian novels</td><td>\cite{Grener2017, Luczak-Roesch2018}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N/Y</td><td>Visualization</td></tr>
  <tr><td>9 fictionary, legendary and biographical books</td><td>\cite{Holanda2017}</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Level of historicity</td></tr>
  <tr><td><i>Game of Thrones</i> TV series (Seasons 1–7)</td><td>\cite{Janosov2017, Janosov2017a, Janosov2021a}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Event prediction</td></tr>
  <tr><td>Shakespeare's <i>Hamlet</i></td><td>\cite{Kwon2017}</td><td>N</td><td>N/Y</td><td>N/Y</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N/Y</td><td>N/Y</td><td>Descriptive analysis</td></tr>
  <tr><td>All of Shakespeare's plays</td><td>\cite{Lee2017d}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Visualization</td></tr>
  <tr><td><i>Game of Thrones</i> TV series (Seasons 1--6)</td><td>\cite{Liu2017d}</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>Descriptive analysis</td></tr>
  <tr><td>Shakespeare's <i>Romeo & Juliet</i></td><td>\cite{Masias2017}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N/Y</td><td>N</td><td>N</td><td>N</td><td>Role detection</td></tr>
  <tr><td><i>Wertheriaden</i> corpus</td><td>\cite{Murr2017, Barth2018}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Comparative study, Method assessment</td></tr>
  <tr><td>Corpus of science-fiction works</td><td>\cite{Rochat2017}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Plot structure comparison</td></tr>
  <tr><td>Leo Tolstoy's <i>War and Peace</i></td><td>\cite{Skorinkin2017}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Check narrative theory</td></tr>
  <tr><td>17 Hollywood movies</td><td>\cite{Tran2017b, Tran2017d}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Role detection</td></tr>
  <tr><td><i>Friends</i> TV series</td><td>\cite{Bazzan2018}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Check narrative theory</td></tr>
  <tr><td>Scripts of <i>Game of Thrones</i> seasons 1, 3 & 5</td><td>\cite{Beveridge2018}</td><td>Y</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>Cao & Gao's <i>The Story of the Stone</i></td><td>\cite{Bi2018}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Check literary theories</td></tr>
  <tr><td>956 movie scripts & 1 comic</td><td>\cite{Chao2018}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Dynamic patterns</td></tr>
  <tr><td>Summaries of 577 original movies and remakes</td><td>\cite{Chaturvedi2018}</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Plot structure comparison</td></tr>
  <tr><td>First 2 seasons of <i>Friends</i></td><td>\cite{Deleris2018}</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Method assessment</td></tr>
  <tr><td><i>Friends</i> TV series </td><td>\cite{Edwards2018, Edwards2019}</td><td>N/Y</td><td>N/Y</td><td>N/Y</td><td>N</td><td>N/Y</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Comparison of extraction methods</td></tr> % Descriptive analysis
  <tr><td>37 Shakespeare plays</td><td>\cite{Evalyn2018, Shukla2018, Shukla2018a}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Classification of works</td></tr>
  <tr><td><i>The Big Bang Theory</i> scripts</td><td>\cite{FronzettiColladon2019, FronzettiColladon2020}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Classification of works</td></tr>
  <tr><td>Hugo's <i>Les misérables</i></td><td>\cite{Ginsburg2018}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Literary analysis</td></tr>
  <tr><td>8 Hollywood movies</td><td>\cite{He2018i}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Role detection</td></tr>
  <tr><td><i>Wonder Woman</i>, <i>Thor</i>, and <i>Hunger Games</i> scripts</td><td>\cite{Jones2018a, Jones2020a}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Role detection, Check theory</td></tr>
  <tr><td>65 classic plays</td><td>\cite{Li2018h}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Classification of works</td></tr>
  <tr><td>7 Hollywood movies and their scripts</td><td>\cite{Mourchid2018, Mourchid2019a, Lafhel2020, Lafhel2021}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>Tagore's <i>Raktakarabi</i> and <i>Muktodhara</i></td><td>\cite{Muhuri2018}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Role detection</td></tr>
  <tr><td>4 popular mangas</td><td>\cite{Murakami2018, Murakami2020}</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Method assessment</td></tr>
  <tr><td>1 TV show and 3 movies</td><td>\cite{Lv2018}</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Method assessment</td></tr>
  <tr><td>53 Slovene fables</td><td>\cite{Markovic2018}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>Medieval Irish text <i>Cogadh Gaedhel re Gallaibh</i></td><td>\cite{Yose2017}</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>N/Y</td><td>N</td><td>Level of historicity</td></tr>
  <tr><td>51 movies</td><td>\cite{Vicol2018}</td><td>Y</td><td>Y</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>Y</td><td>N</td><td>Y</td><td>Annotated corpus presentation</td></tr>
  <tr><td>4 plays</td><td>\cite{Zawislak2018, Zawislak2019}</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>2 Chinese and 1 American TV series</td><td>\cite{Zhang2018ah}</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>5 Victorian and Modernist novels</td><td>\cite{Alexander2019}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Check narrative theory</td></tr>
  <tr><td>6 Jane Austen novels</td><td>\cite{Bipasha2019}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Method assessment</td></tr>
  <tr><td>Cao's <i>Dream of the Red Chamber</i></td><td>\cite{Chen2019q}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Method assessment</td></tr>
  <tr><td>2 novels and their movie adaptations</td><td>\cite{Chowdhury2019}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N/Y</td><td>N/Y</td><td>N</td><td>N</td><td>Plot structure comparison</td></tr>
  <tr><td>20 classic and 20 modern novels</td><td>\cite{Dekker2019}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>Rowling's <i>Harry Potter</i> novels</td><td>\cite{Everton2019}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>W</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>930 Polish 19th and 20th century novels</td><td>\cite{Kubis2019, Kubis2021}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Comparative study</td></tr>
  <tr><td>12 Hollywood movies</td><td>\cite{Lee2019c}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Method assessment</td></tr>
  <tr><td>142 movies</td><td>\cite{Lee2019b, Lee2019d, Lee2020, Lee2020a, Lee2020c}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Story and character embedding</td></tr>
  <tr><td><i>The Lord of the Rings</i> scripts and <i>Harry Potter</i> novels</td><td>\cite{Li2019o}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>The <i>Gospels</i> and <i>Acts of the Apostles</i></td><td>\cite{Massey2019}</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis, Comparative study</td></tr>
  <tr><td>1 Chinese TV series episode and 1 Hollywood movie</td><td>\cite{Pan2019b}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Visualization, Descriptive analysis</td></tr>
  <tr><td>4 Swedish and Finnish 19th century plays</td><td>\cite{Pikkanen2019}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>170 contemporary Dutch novels</td><td>\cite{Smeets2019, Volker2020, Smeets2021}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Check literary theories, Level of realism</td></tr>
  <tr><td><i>Game of Thrones</i> TV series</td><td>\cite{Stavanja2019}</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Link prediction</td></tr>
  <tr><td>Rowling's <i>Harry Potter</i> novels</td><td>\cite{Vani2019}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Visualization</td></tr>
  <tr><td>40 movies</td><td>\cite{Zeng2019b}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Quality prediction</td></tr>
  <tr><td>5,269 novels</td><td>\cite{Sims2020}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Information propagation</td></tr>
  <tr><td>4 TV comedy series</td><td>\cite{Bazzan2020}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Comparative study</td></tr>
  <tr><td>2 mythological and 1 historical texts</td><td>\cite{Besnier2020}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N/Y</td><td>Plot structure comparison</td></tr>
  <tr><td>Twain's <i>Adventures of Huckleberry Finn</i></td><td>\cite{Feild2020}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Presentation of a tool</td></tr>
  <tr><td>Martin's <i>A Song of Ice and Fire</i></td><td>\cite{GesseyJones2020}</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>894 movie scripts</td><td>\cite{Hopp2020}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Check narrative theory</td></tr>
  <tr><td>Jin Yong's 15 novels</td><td>\cite{Jia2020a, Jia2020c}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Method assessment</td></tr>
  <tr><td><i>The Force Awakens</i> script</td><td>\cite{Jones2020, Jones2020a}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>Y</td><td>Role detection, Check theory</td></tr>
  <tr><td>15,540 movie subtitles</td><td>\cite{Kagan2019}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Identification of gender biases</td></tr>
  <tr><td>Heterogeneous selection of 26 novels</td><td>\cite{Kim2019b, Kim2020a}</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Classification of works</td></tr>
  <tr><td>6 Hollywood movies</td><td>\cite{Kulshreshtha2020}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Segment story, Role detection</td></tr>
  <tr><td>Korean webtoons</td><td>\cite{Lee2020f}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Recommendation system</td></tr>
  <tr><td>Script of Phillips' <i>Joker</i></td><td>\cite{Lee2020h}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Mise-en-scène identification</td></tr>
  <tr><td>No experimental assessment</td><td>\cite{Lee2020j}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Movie summarization</td></tr>
  <tr><td>Rowling's <i>Harry Potter</i> and Alcott's <i>Little Women</i></td><td>\cite{Mellace2020, Vani2020}</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N/Y</td><td>Visualization</td></tr>
  <tr><td>Collection of classical tragedies</td><td>\cite{Moretti2020}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Network generation</td></tr>
  <tr><td>Rebreanu's <i>Ion</i></td><td>\cite{Pojoga2020}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Visualization</td></tr>
  <tr><td>Milton's <i>Paradise Lost</i>, Homer's <i>Iliad</i></td><td>\cite{Ruegg2020}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N/Y</td><td>Comparative study</td></tr>
  <tr><td>Summaries of 4 novels</td><td>\cite{Shahsavari2020}</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Estimation from summaries</td></tr>
  <tr><td>6 contemporary US novels</td><td>\cite{Thomas2020}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Check literary theories</td></tr>
  <tr><td>Shakespeare's <i>Macbeth</i> and <i>Othello</i></td><td>\cite{Yavuz2020}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>7 Chinese novels</td><td>\cite{Zhao2020f}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Detect communities of characters</td></tr>
  <tr><td><i>Bleak House</i>, <i>Ulysses</i>, and <i>The Wire</i></td><td>\cite{Alexander2021}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Comparative study</td></tr>
  <tr><td>Lafayette's <i>La Princesse de Clèves</i></td><td>\cite{Bilis2021}</td><td>Y</td><td>Y</td><td>Y</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Visualization</td></tr>
  <tr><td>Galsworthy's <i>Strife</i> and Bhattacharya's <i>Nabanna</i></td><td>\cite{Chakraborty2021}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>Y</td><td>Community detection</td></tr>
  <tr><td>Bulgakov's <i>The Master and Margarita</i></td><td>\cite{Danilova2021}</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>2 classic Chinese novels</td><td>\cite{Fan2021, Fan2021c}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
    <tr><td>144 Russian plays and Tolstoy's <i>War & Peace</i></td><td>\cite{Fischer2021}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N/Y</td><td>Descriptive analysis</td></tr>
  <tr><td>Lowe's <i>Long Time No See</i></td><td>\cite{Huang2021b}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis, Visualization</td></tr>
  <tr><td>969 IMSDb scripts</td><td>\cite{Kounelis2021}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Recommendation system</td></tr>
  <tr><td>Scripts of 12 Hollywood movies</td><td>\cite{Lee2021}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Subplot identification</td></tr>
  <tr><td>89 popular movies</td><td>\cite{Malik2021a}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Identification of racial biases</td></tr>
  <tr><td>10 Tagore's plays and novels</td><td>\cite{Mandal2021a}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Presentation of a tool</td></tr>
  <tr><td>Shakespeare's <i>Measure for Measure</i></td><td>\cite{Marceniuk2021}</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Visualization</td></tr>
  <tr><td>500 fanfiction books</td><td>\cite{Rahul2021}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Genre prediction</td></tr>
  <tr><td>Grimm's <i>Children's and Household Tales</i></td><td>\cite{Schmidt2021}</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Annotated corpus presentation</td></tr>
  <tr><td>Lynch's <i>Twin Peaks</i></td><td>\cite{Siljak2021}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>Sophocles' <i>Antigone</i></td><td>\cite{Yavuz2021}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Speech sequence modeling</td></tr>
  <tr><td>Luo's <i>Romance of the Three Kingdoms</i></td><td>\cite{Zhang2021o}</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Comparative study</td></tr>
  <tr><td>Fan-Fictions</td><td>\cite{Zadeh2022}</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Popularity prediction</td></tr>
</table>


# Contact
Please, contact me if you detect an article missing from the above list:

Vincent Labatut <[vincent.labatut@univ-avignon.fr](mailto:vincent.labatut@univ-avignon.fr)>

