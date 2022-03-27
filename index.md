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
  <tr><td><b>Work of fiction</b></td><td><b>Reference</b></td><td colspan="5"><b>Relationships</b></td><td colspan="4"><b>Graph</b></td><td><b>Application</b></td></tr>
  <tr><td/><td/><td><b>Cc.</b></td><td><b>Cv.</b></td><td><b>M.</b></td><td><b>Ac.</b></td><td><b>Af.</b></td><td><b>W.</b></td><td><b>Di.</b></td><td><b>S.</b></td><td><b>Dy.</b></td><td/></tr>
  <tr><td>Mozart's <i>Cosi Fan Tutte</i></td><td><a href="http://doi.org/10.2466/pr0.1963.13.2.466">Harary1963</a></td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>Descriptive analysis</td></tr>
  <tr><td>Murdoch's <i>A Severed Head</i></td><td><a href="http://doi.org/10.2466/pr0.1966.19.2.473">Harary1966a</a></td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>Shakespeare's <i>A Midsummer Night's Dream</i></td><td><a href="http://doi.org/10.2466/pr0.1967.20.2.657">Stanton1967</a></td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>Descriptive analysis</td></tr>
  <tr><td>Wagner's <i>Der Ring des Nibelungen</i></td><td><a href="https://www.persee.fr/doc/roman_0048-8593_1973_num_3_6_4957">Mayer1973</a></td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>Shakespeare's <i>Twelfth Night</i></td><td><a href="http://www.numdam.org/item/MSH_1975__51__77_0/">Harary1975</a></td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>16 fairy tales</td><td><a href="http://doi.org/10.2466/pr0.1980.47.1.183">Auster1980</a></td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>Descriptive analysis</td></tr>
  <tr><td>Sophocles' <i>Oedipus Rex</i></td><td><a href="https://dokumen.tips/documents/oedipus-loves-his-mother.html">Harary1982</a></td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>Priestley's <i>Dangerous Corner</i></td><td><a href="http://doi.org/10.1515/semi.1985.54.3-4.387">Harary1985</a></td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>Comparative study</td></tr>
  <tr><td>5 classic novels</td><td><a href="http://www-cs-faculty.stanford.edu/~knuth/sgb.html">Knuth1993</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Benchmark for graph processing tools</td></tr>
  <tr><td><i>Marvel</i> comics</td><td><a href="http://arxiv.org/abs/cond-mat/0202174">Alberich2002</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Level of realism</td></tr>
  <tr><td>10 Shakespeare's plays</td><td><a href="http://doi.org/10.1007/s12110-003-1013-1">Stiller2003, Stiller2005</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Level of realism</td></tr>
  <tr><td>All of Shakespeare's plays</td><td><a href="http://doi.org/10.1109/IV.2004.1320122">Mutton2004</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N/Y</td><td>Visualization</td></tr>
  <tr><td>Dictionary of Greek and Roman mythology</td><td><a href="http://doi.org/10.1016/j.physa.2007.04.035">Choi2007</a></td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N/Y</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td><i>Marvel</i> comics</td><td><a href="http://doi.org/10.1088/1742-5468/2007/09/P09020">Gleiser2007</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Level of realism</td></tr>
  <tr><td>Hollywood movies, and TV series</td><td><a href="http://doi.org/10.1109/ICME.2007.4284922">Weng2007</a>, <a href="http://doi.org/10.1145/1290082.1290092">Weng2007a</a>, <a href="http://doi.org/10.1109/TMM.2008.2009684">Weng2009</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Storyline identification/segmentation</td></tr>
  <tr><td>9 classical plays</td><td><a href="http://ets.ifmo.ru/tomasov/konferenc/AutoPlay/Docs/Volume%204/8_06.pdf">Voloshinov2008</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Level of realism</td></tr>
  <tr><td>Movies and TV series</td><td><a href="">Park2009, Park2011</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Role detection, story segmentation</td></tr>
  <tr><td><i>Friends</i> TV show</td><td><a href="">Yuan2009, Yuan2010</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Method assessment</td></tr>
  <tr><td>15 Hollywood movies</td><td><a href="">Zhang2009e, Liang2009a, Sang2011, Sang2012</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Face-name matching, Scene segmentation</td></tr>
  <tr><td>Austen's <i>Pride & prejudice</i>, and <i>Emma</i></td><td><a href="">Celikyilmaz2010</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Method assessment</td></tr>
  <tr><td>10 adversarial movies</td><td><a href="">Ding2010</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>Y</td><td>N</td><td>Method assessment</td></tr>
  <tr><td>60 19th century British novels</td><td><a href="">Elson2010, Elson2010a, Elson2012</a></td><td>N/Y</td><td>N/Y</td><td>N/Y</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Check literary theories</td></tr>
  <tr><td>20 Hollywood movies</td><td><a href="">Ding2011a</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>Y</td><td>Y</td><td>Community detection</td></tr>
  <tr><td>300 19th century Swedish novels</td><td><a href="">Kokkinakis2011</a></td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Method assessment</td></tr>
  <tr><td>Toriyama's <i>Dragon Ball</i> vol.32</td><td><a href="">Murakami2011</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Method assessment</td></tr>
  <tr><td>Shakespeare's <i>Hamlet</i>, <i>Macbeth</i>, and <i>King Lear</i></td><td><a href="">Moretti2011a</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Discussion about the characters</td></tr>
  <tr><td>Collection of Greek Tragedies</td><td><a href="">Rydberg2011</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Plot structure comparison</td></tr>
  <tr><td>8 Hollywood movies</td><td><a href="">Tsai2011</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Scene segmentation</td></tr>
  <tr><td>Carroll's <i>Alice in Wonderland</i></td><td><a href="">Agarwal2011, Agarwal2012, Agarwal2013, Agarwal2013a, Agarwal2014a</a></td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N/Y</td><td>N</td><td>N/Y</td><td>Role detection</td></tr>
  <tr><td>41 19th century novels</td><td><a href="">Elsner2012</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Genre comparison</td></tr>
  <tr><td>Rowling's <i>Harry Potter</i> novels</td><td><a href="">Hutchinson2012</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Method assessment</td></tr>
  <tr><td>The <i>Old Testament</i></td><td><a href="">Lee2012f</a></td><td>N</td><td>Y</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Method assessment</td></tr>
  <tr><td>4 European tales</td><td><a href="">MacCarron2012, MacCarron2013, MacCarron2013b, MacCarron2013a, MacCarron2014a, Kenna2016, Kenna2017</a></td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>N/Y</td><td>N</td><td>Y</td><td>N</td><td>Level of historicity</td></tr>
  <tr><td>19th and 20th century Swedish novels</td><td><a href="">Oelke2012, Oelke2013</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N/Y</td><td>Visualization</td></tr>
  <tr><td>6 canonical European novels</td><td><a href="">Sack2012, Sack2013, Sack2014</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Proto-narrative generation</td></tr>
  <tr><td>Frankel's <i>The Devil Wears Prada</i></td><td><a href="">Yeh2012, Yeh2014</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Face clustering</td></tr>
  <tr><td>Manzoni's <i>I promessi sposi</i></td><td><a href="">Bolioli2013</a></td><td>N/Y</td><td>N/Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Method assessment</td></tr>
  <tr><td>Rowling's <i>Harry Potter</i> novels</td><td><a href="">Bossaert2013</a></td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Study of peer support</td></tr>
  <tr><td>3 classic European novels</td><td><a href="">He2013a, Makazhanov2014</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Method assessment</td></tr>
  <tr><td>10 Hollywood movie scripts</td><td><a href="">Jung2013a</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Role detection</td></tr>
  <tr><td>Homer's <i>Odyssey</i></td><td><a href="">Miranda2013, Miranda2018</a></td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Level of historicity</td></tr>
  <tr><td>Shakespeare's plays</td><td><a href="">Nalisnick2013, Nalisnick2013a</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Method assessment</td></tr>
  <tr><td>20 novels</td><td><a href="">Park2013, Park2013a, Seo2013, Seo2014</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>Rowling's <i>Harry Potter and the Philosopher's Stone</i></td><td><a href="">Sparavigna2013</a></td><td>N</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Level of realism</td></tr>
  <tr><td>3 story books</td><td><a href="">Sudhahar2013</a></td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Role detection</td></tr>
  <tr><td>173 theater and 580 movie scripts</td><td><a href="">Suen2013</a></td><td>N/Y</td><td>N/Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Classification of works</td></tr>
  <tr><td>12 Hollywood movies</td><td><a href="">Tsai2013</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Video summarization</td></tr>
  <tr><td>674 movie scripts</td><td><a href="">Agarwal2014b, Agarwal2016</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Performance evaluation</td></tr>
  <tr><td>238 novels</td><td><a href="">Ardanuy2014, Ardanuy2015</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Classification of works</td></tr>
  <tr><td>250,000 novels, myths and fary tales</td><td><a href="">Bodrova2014</a></td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Method assessment</td></tr>
  <tr><td>1,800 19th century British and American novels</td><td><a href="">Condello2014</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Comparative study</td></tr>
  <tr><td>Tales and myths</td><td><a href="">MacCarron2014</a></td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>Level of historicity, Categorization</td></tr>
  <tr><td><i>Das Nibelungenlied</i>, and Shakespeare's <i>Hamlet</i></td><td><a href="">Marazzato2014, Sparavigna2015</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Method assessment</td></tr>
  <tr><td>Rousseau's <i>Les confessions</i></td><td><a href="">Rochat2014a, Rochat2014</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N/Y</td><td>N</td><td>N</td><td>N/Y</td><td>Role detection</td></tr>
  <tr><td>Shakespeare's <i>Hamlet</i> and <i>Othello</i></td><td><a href="">Sparavigna2014a</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td><i>Star Trek</i> and <i>Star Gate</i> movies and TV series scripts</td><td><a href="">Tan2014a, Tan2017, Tan2018a</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Comparative study</td></tr>
  <tr><td>Knowles' <i>The Legends of King Arthur and his Knights</i></td><td><a href="">Trovati2014</a></td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>Method assessment</td></tr>
  <tr><td>Rowling's <i>Harry Potter</i> series</td><td><a href="">Zhang2014q</a></td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>20 novels</td><td><a href="">Amancio2015b</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>1,276 movie scripts</td><td><a href="">Gorinski2015</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Script summarization</td></tr>
  <tr><td>1,682 16--20th century German novels</td><td><a href="">Hettinger2015</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Classification of works</td></tr>
  <tr><td>60 19th century British novels</td><td><a href="">Jayannavar2015</a></td><td>N</td><td>Y</td><td>N</td><td>Y</td><td>N</td><td>N/Y</td><td>N/Y</td><td>N</td><td>N</td><td>Check literary theories</td></tr>
  <tr><td>200 17--18th century French plays</td><td><a href="">Karsdorp2015</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Character ranking, Visualization</td></tr>
  <tr><td>617 movie scripts</td><td><a href="">Krishnan2015</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>Infer formality level of interactions</td></tr>
  <tr><td>58 German novels</td><td><a href="">Krug2015, Jannidis2016, Krug2020</a></td><td>N/Y</td><td>N/Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Role detection</td></tr>
  <tr><td>Homer's <i>Iliad</i></td><td><a href="">Kydros2015</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>Embirikos' <i>The Great Eastern</i></td><td><a href="">Kydros2015a</a></td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>Shakespeare's <i>Julius Caesar</i></td><td><a href="">Lotker2015</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Detect communities of characters</td></tr>
  <tr><td>6 Hollywood movies</td><td><a href="">Li2015w</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Video summarization</td></tr>
  <tr><td>183 <i>Friends</i> episodes</td><td><a href="">Nan2015</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Method assessment</td></tr>
  <tr><td><i>The Wire</i> script</td><td><a href="">Pope2016</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Role detection</td></tr>
  <tr><td>Zola's <i>Les Rougon-Macquart</i></td><td><a href="">Rochat2015</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Plot structure comparison</td></tr>
  <tr><td>First 6 <i>Star Wars</i> movies</td><td><a href="">Tran2015</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Role detection</td></tr>
  <tr><td>Corpus of Hollywood movies</td><td><a href="">Tran2015a, Tran2017a, Do2018</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Movie summarization</td></tr>
  <tr><td>Large corpora of European plays</td><td><a href="">Fischer2015a, Trilcke2016, Fischer2016, Fischer2017, Fischer2017a</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Check literary theories</td></tr> % also: Descriptive analysis
  <tr><td>46 fantasy novels, and Hugo's <i>Les misérables</i></td><td><a href="">Waumans2015</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Classification of works</td></tr>
  <tr><td>Martin's <i>A Storm of Swords</i></td><td><a href="">Beveridge2016</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>3 modern novels</td><td><a href="">Bonato2016</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Model fitting</td></tr>
  <tr><td>3 TV series</td><td><a href="">Bost2016, Bost2016b, Bost2016c, Bost2018a</a></td><td>N/Y</td><td>N/Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N/Y</td><td>Video summarization</td></tr>
  <tr><td>Zhi Ning's <i>Journey to the West Prequel<i></td><td><a href="">Chen2016k</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>Tarentino's <i>Pulp Fiction</i></td><td><a href="">Cipresso2016</a></td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>Edgeworth's <i>The Absentee</i></td><td><a href="">Falk2016</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Check literary theories</td></tr>
  <tr><td>19th century British novels</td><td><a href="">Grayson2016, Grayson2016a</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N/Y</td><td>Descriptive analysis</td></tr>
  <tr><td>4 novels</td><td><a href="">John2016, John2017, John2019</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Visualization</td></tr>
  <tr><td>Chinese Buddhist Canon</td><td><a href="">Lee2016d</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>10 Hollywood movies</td><td><a href="">Lee2016e, Lee2018</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Recommendation system</td></tr>
  <tr><td>Shakespeare's <i>Julius Caesar</i>, <i>Hamlet</i>, and <i>Othello</i></td><td><a href="">Lotker2016</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>Y</td><td>Study of time flow in dynamic networks</td></tr>
  <tr><td>501 movie scripts</td><td><a href="">Makris2016</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Method assessment</td></tr>
  <tr><td>The <i>Pentateuch</i></td><td><a href="">Massey2016</a></td><td>N</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N/Y</td><td>Level of historicity</td></tr>
  <tr><td>Hugo's <i>Les misérables</i></td><td><a href="">Min2016, Min2016a, Min2016c</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N/Y</td><td>Story segmentation</td></tr>
  <tr><td><i>La chanson de Roland</i>, and <i>Alice in Wonderland</i></td><td><a href="">Prado2016</a></td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N/Y</td><td>Descriptive analysis</td></tr>
  <tr><td>Tolkien's <i>Middle-Earth</i> novels</td><td><a href="">Ribeiro2016</a></td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>All of Shakespeare's plays</td><td><a href="">Rieck2016</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Comparative study</td></tr>
  <tr><td>CMU Movie Summary corpus</td><td><a href="">Srivastava2016</a></td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>Method assessment</td></tr>
  <tr><td>Homer's <i>Iliad</i></td><td><a href="">Venturini2016</a></td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Visualization</td></tr>
  <tr><td>First 4 books of Martin's <i>A Song of Ice and Fire</i></td><td><a href="">Wohlgenannt2016</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Method assessment</td></tr>
    <tr><td>Molière's <i>L'école des femmes</i></td><td><a href="">Xanthos2016</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Visualization</td></tr>
  <tr><td><i>Ossian</i> corpus of Scottish epic poems</td><td><a href="">Yose2016</a></td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>Level of historicity</td></tr>
  <tr><td>3,568 English-language plays from 1550--1900</td><td><a href="">Algee-Hewitt2017, Piper2017</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Check literary theories</td></tr>
  <tr><td>817 movie scripts</td><td><a href="">Chen2017v</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N/Y</td><td>N/Y</td><td>N</td><td>N</td><td>Identify generative model</td></tr>
  <tr><td>4 gospels of the <i>New Testament</i></td><td><a href="">Grandjean2015</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Comparative study</td></tr>
  <tr><td>Staël's <i>Corinne ou l'Italie</i></td><td><a href="">Edmondson2017</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Visualisation</td></tr>
  <tr><td>British Victorian novels</td><td><a href="">Grener2017, Luczak-Roesch2018</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N/Y</td><td>Visualization</td></tr>
  <tr><td>9 fictionary, legendary and biographical books</td><td><a href="">Holanda2017</a></td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Level of historicity</td></tr>
  <tr><td><i>Game of Thrones</i> TV series (Seasons 1–7)</td><td><a href="">Janosov2017, Janosov2017a, Janosov2021a</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Event prediction</td></tr>
  <tr><td>Shakespeare's <i>Hamlet</i></td><td><a href="">Kwon2017</a></td><td>N</td><td>N/Y</td><td>N/Y</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N/Y</td><td>N/Y</td><td>Descriptive analysis</td></tr>
  <tr><td>All of Shakespeare's plays</td><td><a href="">Lee2017d</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Visualization</td></tr>
  <tr><td><i>Game of Thrones</i> TV series (Seasons 1--6)</td><td><a href="">Liu2017d</a></td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>Descriptive analysis</td></tr>
  <tr><td>Shakespeare's <i>Romeo & Juliet</i></td><td><a href="">Masias2017</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N/Y</td><td>N</td><td>N</td><td>N</td><td>Role detection</td></tr>
  <tr><td><i>Wertheriaden</i> corpus</td><td><a href="">Murr2017, Barth2018</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Comparative study, Method assessment</td></tr>
  <tr><td>Corpus of science-fiction works</td><td><a href="">Rochat2017</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Plot structure comparison</td></tr>
  <tr><td>Leo Tolstoy's <i>War and Peace</i></td><td><a href="">Skorinkin2017</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Check narrative theory</td></tr>
  <tr><td>17 Hollywood movies</td><td><a href="">Tran2017b, Tran2017d</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Role detection</td></tr>
  <tr><td><i>Friends</i> TV series</td><td><a href="">Bazzan2018</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Check narrative theory</td></tr>
  <tr><td>Scripts of <i>Game of Thrones</i> seasons 1, 3 & 5</td><td><a href="">Beveridge2018</a></td><td>Y</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>Cao & Gao's <i>The Story of the Stone</i></td><td><a href="">Bi2018</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Check literary theories</td></tr>
  <tr><td>956 movie scripts & 1 comic</td><td><a href="">Chao2018</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Dynamic patterns</td></tr>
  <tr><td>Summaries of 577 original movies and remakes</td><td><a href="">Chaturvedi2018</a></td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Plot structure comparison</td></tr>
  <tr><td>First 2 seasons of <i>Friends</i></td><td><a href="">Deleris2018</a></td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Method assessment</td></tr>
  <tr><td><i>Friends</i> TV series </td><td><a href="">Edwards2018, Edwards2019</a></td><td>N/Y</td><td>N/Y</td><td>N/Y</td><td>N</td><td>N/Y</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Comparison of extraction methods</td></tr> % Descriptive analysis
  <tr><td>37 Shakespeare plays</td><td><a href="">Evalyn2018, Shukla2018, Shukla2018a</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Classification of works</td></tr>
  <tr><td><i>The Big Bang Theory</i> scripts</td><td><a href="">FronzettiColladon2019, FronzettiColladon2020</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Classification of works</td></tr>
  <tr><td>Hugo's <i>Les misérables</i></td><td><a href="">Ginsburg2018</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Literary analysis</td></tr>
  <tr><td>8 Hollywood movies</td><td><a href="">He2018i</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Role detection</td></tr>
  <tr><td><i>Wonder Woman</i>, <i>Thor</i>, and <i>Hunger Games</i> scripts</td><td><a href="">Jones2018a, Jones2020a</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Role detection, Check theory</td></tr>
  <tr><td>65 classic plays</td><td><a href="">Li2018h</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Classification of works</td></tr>
  <tr><td>7 Hollywood movies and their scripts</td><td><a href="">Mourchid2018, Mourchid2019a, Lafhel2020, Lafhel2021</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>Tagore's <i>Raktakarabi</i> and <i>Muktodhara</i></td><td><a href="">Muhuri2018</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Role detection</td></tr>
  <tr><td>4 popular mangas</td><td><a href="">Murakami2018, Murakami2020</a></td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Method assessment</td></tr>
  <tr><td>1 TV show and 3 movies</td><td><a href="">Lv2018</a></td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Method assessment</td></tr>
  <tr><td>53 Slovene fables</td><td><a href="">Markovic2018</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>Medieval Irish text <i>Cogadh Gaedhel re Gallaibh</i></td><td><a href="">Yose2017</a></td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>N/Y</td><td>N</td><td>Level of historicity</td></tr>
  <tr><td>51 movies</td><td><a href="">Vicol2018</a></td><td>Y</td><td>Y</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>Y</td><td>N</td><td>Y</td><td>Annotated corpus presentation</td></tr>
  <tr><td>4 plays</td><td><a href="">Zawislak2018, Zawislak2019</a></td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>2 Chinese and 1 American TV series</td><td><a href="">Zhang2018ah</a></td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>5 Victorian and Modernist novels</td><td><a href="">Alexander2019</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Check narrative theory</td></tr>
  <tr><td>6 Jane Austen novels</td><td><a href="">Bipasha2019</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Method assessment</td></tr>
  <tr><td>Cao's <i>Dream of the Red Chamber</i></td><td><a href="">Chen2019q</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Method assessment</td></tr>
  <tr><td>2 novels and their movie adaptations</td><td><a href="">Chowdhury2019</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N/Y</td><td>N/Y</td><td>N</td><td>N</td><td>Plot structure comparison</td></tr>
  <tr><td>20 classic and 20 modern novels</td><td><a href="">Dekker2019</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>Rowling's <i>Harry Potter</i> novels</td><td><a href="">Everton2019</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>W</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>930 Polish 19th and 20th century novels</td><td><a href="">Kubis2019, Kubis2021</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Comparative study</td></tr>
  <tr><td>12 Hollywood movies</td><td><a href="">Lee2019c</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Method assessment</td></tr>
  <tr><td>142 movies</td><td><a href="">Lee2019b, Lee2019d, Lee2020, Lee2020a, Lee2020c</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Story and character embedding</td></tr>
  <tr><td><i>The Lord of the Rings</i> scripts and <i>Harry Potter</i> novels</td><td><a href="">Li2019o</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>The <i>Gospels</i> and <i>Acts of the Apostles</i></td><td><a href="">Massey2019</a></td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis, Comparative study</td></tr>
  <tr><td>1 Chinese TV series episode and 1 Hollywood movie</td><td><a href="">Pan2019b</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Visualization, Descriptive analysis</td></tr>
  <tr><td>4 Swedish and Finnish 19th century plays</td><td><a href="">Pikkanen2019</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>170 contemporary Dutch novels</td><td><a href="">Smeets2019, Volker2020, Smeets2021</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Check literary theories, Level of realism</td></tr>
  <tr><td><i>Game of Thrones</i> TV series</td><td><a href="">Stavanja2019</a></td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Link prediction</td></tr>
  <tr><td>Rowling's <i>Harry Potter</i> novels</td><td><a href="">Vani2019</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Visualization</td></tr>
  <tr><td>40 movies</td><td><a href="">Zeng2019b</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Quality prediction</td></tr>
  <tr><td>5,269 novels</td><td><a href="">Sims2020</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Information propagation</td></tr>
  <tr><td>4 TV comedy series</td><td><a href="">Bazzan2020</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Comparative study</td></tr>
  <tr><td>2 mythological and 1 historical texts</td><td><a href="">Besnier2020</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N/Y</td><td>Plot structure comparison</td></tr>
  <tr><td>Twain's <i>Adventures of Huckleberry Finn</i></td><td><a href="">Feild2020</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Presentation of a tool</td></tr>
  <tr><td>Martin's <i>A Song of Ice and Fire</i></td><td><a href="">GesseyJones2020</a></td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>894 movie scripts</td><td><a href="">Hopp2020</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Check narrative theory</td></tr>
  <tr><td>Jin Yong's 15 novels</td><td><a href="">Jia2020a, Jia2020c</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Method assessment</td></tr>
  <tr><td><i>The Force Awakens</i> script</td><td><a href="">Jones2020, Jones2020a</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>Y</td><td>Role detection, Check theory</td></tr>
  <tr><td>15,540 movie subtitles</td><td><a href="">Kagan2019</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Identification of gender biases</td></tr>
  <tr><td>Heterogeneous selection of 26 novels</td><td><a href="">Kim2019b, Kim2020a</a></td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Classification of works</td></tr>
  <tr><td>6 Hollywood movies</td><td><a href="">Kulshreshtha2020</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Segment story, Role detection</td></tr>
  <tr><td>Korean webtoons</td><td><a href="">Lee2020f</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Recommendation system</td></tr>
  <tr><td>Script of Phillips' <i>Joker</i></td><td><a href="">Lee2020h</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Mise-en-scène identification</td></tr>
  <tr><td>No experimental assessment</td><td><a href="">Lee2020j</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Movie summarization</td></tr>
  <tr><td>Rowling's <i>Harry Potter</i> and Alcott's <i>Little Women</i></td><td><a href="">Mellace2020, Vani2020</a></td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N/Y</td><td>Visualization</td></tr>
  <tr><td>Collection of classical tragedies</td><td><a href="">Moretti2020</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Network generation</td></tr>
  <tr><td>Rebreanu's <i>Ion</i></td><td><a href="">Pojoga2020</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Visualization</td></tr>
  <tr><td>Milton's <i>Paradise Lost</i>, Homer's <i>Iliad</i></td><td><a href="">Ruegg2020</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N/Y</td><td>Comparative study</td></tr>
  <tr><td>Summaries of 4 novels</td><td><a href="">Shahsavari2020</a></td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Estimation from summaries</td></tr>
  <tr><td>6 contemporary US novels</td><td><a href="">Thomas2020</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Check literary theories</td></tr>
  <tr><td>Shakespeare's <i>Macbeth</i> and <i>Othello</i></td><td><a href="">Yavuz2020</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>7 Chinese novels</td><td><a href="">Zhao2020f</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Detect communities of characters</td></tr>
  <tr><td><i>Bleak House</i>, <i>Ulysses</i>, and <i>The Wire</i></td><td><a href="">Alexander2021</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Comparative study</td></tr>
  <tr><td>Lafayette's <i>La Princesse de Clèves</i></td><td><a href="">Bilis2021</a></td><td>Y</td><td>Y</td><td>Y</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Visualization</td></tr>
  <tr><td>Galsworthy's <i>Strife</i> and Bhattacharya's <i>Nabanna</i></td><td><a href="">Chakraborty2021</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>Y</td><td>Community detection</td></tr>
  <tr><td>Bulgakov's <i>The Master and Margarita</i></td><td><a href="">Danilova2021</a></td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>2 classic Chinese novels</td><td><a href="">Fan2021, Fan2021c</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
    <tr><td>144 Russian plays and Tolstoy's <i>War & Peace</i></td><td><a href="">Fischer2021</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N/Y</td><td>Descriptive analysis</td></tr>
  <tr><td>Lowe's <i>Long Time No See</i></td><td><a href="">Huang2021b</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis, Visualization</td></tr>
  <tr><td>969 IMSDb scripts</td><td><a href="">Kounelis2021</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Recommendation system</td></tr>
  <tr><td>Scripts of 12 Hollywood movies</td><td><a href="">Lee2021</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Subplot identification</td></tr>
  <tr><td>89 popular movies</td><td><a href="">Malik2021a</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Identification of racial biases</td></tr>
  <tr><td>10 Tagore's plays and novels</td><td><a href="">Mandal2021a</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Presentation of a tool</td></tr>
  <tr><td>Shakespeare's <i>Measure for Measure</i></td><td><a href="">Marceniuk2021</a></td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Visualization</td></tr>
  <tr><td>500 fanfiction books</td><td><a href="">Rahul2021</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Genre prediction</td></tr>
  <tr><td>Grimm's <i>Children's and Household Tales</i></td><td><a href="">Schmidt2021</a></td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Annotated corpus presentation</td></tr>
  <tr><td>Lynch's <i>Twin Peaks</i></td><td><a href="">Siljak2021</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>Sophocles' <i>Antigone</i></td><td><a href="">Yavuz2021</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Speech sequence modeling</td></tr>
  <tr><td>Luo's <i>Romance of the Three Kingdoms</i></td><td><a href="">Zhang2021o</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Comparative study</td></tr>
  <tr><td>Fan-Fictions</td><td><a href="">Zadeh2022</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Popularity prediction</td></tr>
</table>


# Contact
Please, contact me if you detect an error or an article missing from the above list:

Vincent Labatut <[vincent.labatut@univ-avignon.fr](mailto:vincent.labatut@univ-avignon.fr)>

