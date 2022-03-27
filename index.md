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
  <tr><td>58 German novels</td><td><a href="http://www.aclweb.org/anthology/W15-0711">Krug2015</a>, <a href="http://dh2016.adho.org/abstracts/297">Jannidis2016</a>, <a href="https://opus.bibliothek.uni-wuerzburg.de/frontdoor/index/index/docId/20918">Krug2020</a></td><td>N/Y</td><td>N/Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Role detection</td></tr>
  <tr><td>Homer's <i>Iliad</i></td><td><a href="http://doi.org/10.3366/ijhac.2015.0141">Kydros2015</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>Embirikos' <i>The Great Eastern</i></td><td><a href="https://www.researchgate.net/profile/Dimitrios_Kydros/publication/273357563_Social_network_analysis_in_literature._The_case_of_The_Great_Eastern_by_A._Embirikos/links/54ff172f0cf2672e22419bd6.pdf">Kydros2015a</a></td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>N</td><td>N</td><td>Descriptive analysis</td></tr>
  <tr><td>Shakespeare's <i>Julius Caesar</i></td><td><a href="http://doi.org/10.1145/2808797.2810064">Lotker2015</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Detect communities of characters</td></tr>
  <tr><td>6 Hollywood movies</td><td><a href="http://doi.org/10.1109/MMSP.2015.7340794">Li2015w</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>Video summarization</td></tr>
  <tr><td>183 <i>Friends</i> episodes</td><td><a href="http://doi.org/10.1145/2808797.2809306">Nan2015</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>Y</td><td>Method assessment</td></tr>
  <tr><td><i>The Wire</i> script</td><td><a href="https://arxiv.org/abs/1610.01720">Pope2016</a></td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Role detection</td></tr>
  <tr><td>Zola's <i>Les Rougon-Macquart</i></td><td><a href="http://dh2015.org/abstracts/xml/ROCHAT_Yannick_Character_Network_Analysis_of__mil/ROCHAT_Yannick_Character_Network_Analysis_of__mile_Zola.html">Rochat2015</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Plot structure comparison</td></tr>
  <tr><td>First 6 <i>Star Wars</i> movies</td><td><a href="http://doi.org/10.3217/jucs-021-06-0796">Tran2015</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Role detection</td></tr>
  <tr><td>Corpus of Hollywood movies</td><td><a href="http://doi.org/10.1007/978-3-319-24069-5_37">Tran2015a</a>, <a href="http://doi.org/10.1007/s11042-016-3633-6">Tran2017a</a>, <a href="http://doi.org/10.1007/s40595-018-0111-2">Do2018</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Y</td><td>N</td><td>N</td><td>N</td><td>Movie summarization</td></tr>
  <tr><td>Large corpora of European plays</td><td><a href="http://dh2015.org/abstracts/xml/FISCHER_Frank_Digital_Network_Analysis_of_Dramati/FISCHER_Frank_Digital_Network_Analysis_of_Dramatic_Text.html">Fischer2015a</a>, <a href="http://dh2016.adho.org/abstracts/360">Trilcke2016</a>, <a href="http://doi.org/10.6084/m9.figshare.3101203">Fischer2016</a>, <a href="https://sht.asso.fr/le-drame-comme-reseau-de-relations-une-application-de-lanalyse-automatisee-pour-lhistoire-litteraire-du-theatre/">Fischer2017</a>, <a href="https://dh2017.adho.org/abstracts/071/071.pdf">Fischer2017a</a></td><td>Y</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>N</td><td>Check literary theories</td></tr>
</table>

# Contact
Please, contact me if you detect an error or an article missing from the above list:

Vincent Labatut <[vincent.labatut@univ-avignon.fr](mailto:vincent.labatut@univ-avignon.fr)>

