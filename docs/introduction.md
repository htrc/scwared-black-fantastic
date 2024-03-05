# The Black Fantastic: Curated Vocabularies, Artifact Analysis, and Identification
Clarissa West-White and Seretha Williams[^1]

An aim of this project is to identify volumes in HathiTrust Digital Library (HTDL) that can be categorized as belonging to the genre of Black Fantastic, an umbrella term we use to be inclusive of the variations of speculative writing produced by writers who identify as Black people. We define the Black Fantastic as the cultural production of African Diasporic artists and creators who engage with the intersections of race and technology in their work, and propose that the Black Fantastic genre includes Afrofuturism, Afro-surrealism, Black science fiction, Black horror, and even historical nonfiction documents. Early examples of the Black Fantastic mode include Martin Delaney’s _Blake, or the Huts of America_; Sutton Grigg’s _Imperium in Imperio_; Charles W. Chesnutt’s _The Conjure Woman_; W.E.B. DuBois’ “The Comet;” Pauline Hopkins’ _Of One Blood_; and George Schuyler’s _Black No More_. In these texts, African American authors

## Mary McLeod Bethune
Prior to her assent to Statuary Hall and homage from Vice-President of the United States Kamala Harris, the dearth of Mary McLeod Bethune’s accomplishments and impact on the historical and political landscape of America remain largely unknown. The first of Samuel and Patsy McLeod’s seventeen children to be born free, this remarkable powerbroker would become the founder of the Daytona Literary and Industrial Training Institute for Negro Girls, advisor to four sitting U.S. Presidents, the only woman of color at the founding conference of the United Nations, founder of the National Council of Negro Women, co-founder of the United Negro College Fund, the longest serving president of the Study of Negro Life and History, Inc., now known as the Association for the Study of African American Life and History, Inc., and Director of the Division of Negro Affairs, which at that time represented the highest federal appointment ever held by an African American woman. These are only a sliver of her accolades and honors. 

Therefore, if any single woman of the 19th and 20th century can serve as the persona of the Black Fantastic, it is Mary Jane McLeod Bethune. The forward-thinking trailblazer held
the imagination and hope of her peers and race at home and abroad with dynamic speeches and writings. Using Womack’s (2013) definition of the term Afrofuturism - “an intersection of imagination, technology, the future, and liberation” (p. 9) - we posit that her relationship to such Afrofuturists as W.E.B. DuBois, Zora Neale Hurston, and Langston Hughes requires an intimate review and her writings, found within HathiTrust, the Mary McLeod Bethune Collection at Carl S. Swisher Library and select databases, further inspection.  One aspect of this project seeks to establish a controlled vocabulary to identify Afrofuturistic texts, another to apply vocabulary to the selected works of Mrs. Bethune that were converted to OCR with Adobe. The collection housed at Bethune-Cookman University spans Mary McLeod Bethune’s lifetime. It includes documents; photographs; and scrapbooks pertaining to her life and works, her tenure as president of Bethune-Cookman College, and her involvement in government and international affairs. The arrangement of the collection is in both series and box identification and divided into four series. The other aspect of the project includes a list of keywords associated with the Black Fantastic, the workset of volumes in HathiTrust that can be associated with the Black Fantastic, and Black Fantastic volumes not included in HathiTrust. 

## Identifying the Black Fantastic
### Using keywords

The Black Fantastic keyword list evolved from an earlier endeavor to identify works of Afrofuturism within the History of Black Writing’s digital corpus. The original project used keyword lists from [Amazon’s science fiction list](https://d2vvqscadf4c1f.cloudfront.net/2gx8d9XdQ02yGSTTUSmI_Required%20Keywords%20for%20Amazon%20Categories.pdf) and [The Oxford Dictionary of Science Fiction](https://www.oxfordreference.com/view/10.1093/acref/9780195305678.001.0001/acref-9780195305678). Some of those terms were in the HBW corpus, but many were not. The primary investigators added words considered culturally specific, including “conjure” and “hoodoo.” For the HathiTrust workset, the keyword list from the HBW project served as the foundation for early searches of Afrofuturism in the HTDL. The keyword list was not successful in identifying Black Fantastic or Afrofuturism texts for a number of reasons. The team concluded that some of the texts in the HBW corpus were not included in the HTDL and that the keywords were not helpful in identifying texts in a subgenre. Jordan, Mubin, and Silva’s (2016) “[A Conceptual Research Agenda and Quantification Framework for the Relationship Between Science-Fiction Media and Human-Computer Interaction](https://doi.org/10.1007/978-3-319-40548-3_9),” Short’s (2019) “[Text Mining and Subject Analysis for Fiction; or, Using Machine Learning and Information Extraction to Assign Subject Headings to Dime Novels](https://doi.org/10.1080/01639374.2019.1653413),”   Menadue and Cheer’s (2017) “[Human Culture and Science Fiction: A Review of the Literature, 1980-2016](https://doi.org/10.1177/2158244017723690),” and Toliver’s (2022) ["Defining Afrofuturism"](https://readingblackfutures.com/defining-afrofuturism/) are four examples of text analysis articles that incorporate keyword or subject heading search as a methodology.   The authors of these articles found keywords helpful in demarcating science fiction from other fictions; however, keywords alone may not be helpful in identifying Black fantastic texts.

### Exploratory lexical analysis

With an initial set of 18 volumes of Black Fantastic literature identified (We’d later identify additional volumes using title-author searches from additional Black Fantastic bibliographies including [Afrofuturism: Selected Bibliography](https://research.cgu.edu/sah-events-and-conferences/about/bradshaw-conference/2021-futurity-and-future-publics/2021-conference-schedule/afrofutures/afrofuturism-selected-bibliography-2/), [Afrofuturism as an Arts Movement](https://www.concordia.ca/content/dam/library/docs/research-guides/art-history/Afrofuturism_Bibliography.pdf), and [Afro-Futurism](https://cookman.libguides.com/c.php?g=833951)), we performed exploratory data analysis primarily to uncover trends and characteristics in the texts that could be used as criteria to identify other potential BF works in the HTDL. This analysis consisted of identifying frequent words and parts-of-speech as well as prominent words using term frequency - inverse document frequency (TF-IDF), a technique intended to isolate words that are important to a set of volumes while controlling for frequent words. TF-IDF results were compared to a random sample of English-language fiction with a goal of finding disparate terms between the two sets. Though manual review of these results uncovered a prominence of the term “time” in known BF texts–which could serve as a potential mechanism for identifying additional BF texts–this approach was challenged by the term’s general commonness, and additional search efforts using “time” as an indicator were not fruitful.

### Topic modeling

Additional exploratory analysis was conducted on the initial Black Fantastic volume set, including Latent Dirichlet Allocation (LDA) topic modeling, a method intended to uncover clusters of prominent, co-occurring words in our volume set in order to summarize the themes present in their contents. This was implemented using HTRC’s [Extracted Features](https://doi.org/10.13012/R2TE-C227) (EF) data for each volume and an implementation of LDA in Python, using [GenSim](https://radimrehurek.com/gensim/). Topic-focused results helped us better understand the structure and contents of our BF volumes. One particularly interesting result was the clustering of Black Vernacular English (BVE) terms into one topic, signaling a shared use of such terms across the BF volumes–but again the topic model did not yield actionable results for finding more BF volumes. Additional rounds of volume clustering between known BF volumes and comparison sets of known, Black-authored English-language fiction and random English-language fiction did not show a strong enough reliable distinction between BF texts and their comparison groups to warrant further investigation of this type of modeling for exploratory uses.

### Manual identification

These three experiments–TF-IDF, topic modeling, and volume clustering–did not consistently capture the distinction or essence of Black Fantastic texts. For this reason, we turned to manual efforts, which were our most fruitful efforts for finding BF texts in HathiTrust. However, potential BF texts were identified through keyword analysis, and these texts were verified or excluded as Black Fantastic using domain expertise and further research about the author and the volume’s contents. All texts included in the workset and identified as Black Fantastic underwent this manual process, and our findings indicate this is still the best means for identifying works in this genre, though we do not rule out the success of additional automated efforts that were out of scope of this project. Also out of scope is the interesting question of whether these particular negative algorithmic results might themselves have some meaning related to our understanding of genre.

## Content of the Workset and Subsets
### Keywords

Dr. Seretha Williams contributed a keyword list developed as part of an [earlier digital project](https://youtu.be/Zpwndv3ISa8?t=287), which searched for instances of Afrofuturism in the digital corpus of the History of Black Writing’s database housed in [PhiloLogic](https://textual-optics-lab.uchicago.edu/black_writing_corpus) at University of Chicago. The keyword list, a compilation of search terms for speculative fiction and words that appeared in pre-identified Black Fantastic texts, provided a starting point for identifying Black Fantastic texts. The keyword searches in the HathiTrust corpus helped to identify texts that could be examples of the Black Fantastic. Using TF-IDF analysis, the project investigators developed a list of frequently occurring words. One of the significant findings was the recurrence of the word “time.” The investigators then built a list of words associated with time to determine whether analysis of time words could be a predictor of Black Fantastic texts. Although the analysis of time and time-related words was not a reliable predictor of Black Fantastic texts, the results indicated that many texts written by Black writers referenced time and time-related words with high frequency. 

Foundational Keyword List from the History of Black Writing/Black Book Interactive Project:

| BBIP Keywords  |  |  | 
| :---------| :---------- | :----------------- | 
| Alien(s)     | Force Field   | Psychic       | 
| Androids   | Future(s), Futurelessness   | Ray gun    | 
| Angel(s)  | Galaxy(ies)(ial)  | Robot(s)          |   
| Beam(ed) (s)    | Genes         | Root work         | 
| Blaster (s), Blasted  | Ghost(s) | Shifters | 
| Clone(d)(s)  | Goopher         | Spacecraft   | 
| Comet(s)     | Healer(s)  | Spaceman       | 
| Computer      | Hoodoo/Voodoo     | Spaceship(s)   | 
| Conjure(d)(s), Conjuring(s)  | Mad Scientist   | Star(s) |
| Conjuror(s)    | Magic, Magical(ly)  | Starship  | 
| Constellation(s)  | Metaphysical  | Teleport(ed)(s), Teleportation | 
| Cryogenics | Mutant(s), Mutation(s), Mutating (ed) | Telepath(s), Telepathy (ic)  | 
| Death Ray       | Orbit(s)(ed)(ing)    |   Universe(s)   | 
| Dystopia         | Outer Space    |  Vampire   | 
| Elf, Elves  | Pantheon    | Witch(es), witchcraft, witchery  | 
| Fairy (ies)  | Pirates         |           | 

Time-related search words (To review the results, go to [BF_KW_time](https://docs.google.com/spreadsheets/d/159FITssl0ouX9O0lIuzcpIT4eWDt6jzZtT8H26z7PBU/edit?usp=sharing)):


| BF KW Titles "Time"  |  |  
| :---------| :---------- | 
| ago  | moment | 
| ancient | passing | 
| becoming | past |   
| clock | remember | 
| day | solar |
| future | soon | 
| later | time| 
| lifetime | tomorrow | 
| lunar  | year| 
| memory | | 
 

### BF Volumes in HathiTrust

Title | Author | OrigDate of Pub. | | Title | Author | OrigDate of Pub. |
| :-------| :------- | :-------| :------- | :-------| :-------- | :-------- | 
| Ark of Bones | Henry Dumas | 1970 | | Nova | Samuel R. Delany | 1968 |
| Babel-17 | Samuel R. Delany | 1966 | | Ordeal of Mansart | W.E.B. DuBois | 1957 |
| Ballad of Beta- 2 | Samuel R. Delany | 1965 | | Over Edom, I Lost My Shoe | George Russ | 1970 |
| Black No More | George Schuyler | 1931 | | Portrait of a Young Man Drowning | Charles Perry | 1962 |
| Book of Numbers | Robert Deane Pharr | 1969 | | S.R.O. | Robert Deane Pharr | 1971 |
| Brown Girl in the Ring | Nalo Hopkinson | 1998 | | Stars in My Pocket Like Grains of Sand | Samuel R. Delany | 1984 |
| Burn, Killer, Burn! | Paul Crump | 1962 | | Survivors | Kristin Hunter | 1975 |
| City of a Thousand Suns | Samuel R. Delany | 1965 | | Sweet Whispers, Brother Rush | Virginia Hamilton | 1982 |
| Clarion People | Audrey Lee | 1968 | | The Bloodworth Orphans | Leon Forrest | 1977 |
| Cold Fire Burning (A) | Nathan C. Heard | 1974 | | The Cattle Killing | John Edgar Wideman | 1996 |
| Echo Tree | Henry Dumas | 2003 | | The Conjure Woman | Charles Chesnutt | 1899 |
| I Want a Black Doll | Frank Hercules | 1967 | | The Ear, the Eye, and the Arm | Nancy Farmer | 1994 |
| Imperium in Imperio | Sutton Griggs | 1899 | | The Militants | Nivi-Kofi Easley | 1974 |
| Kindred | Octavia Butler | 1979 | | The Salt Eaters | Toni Cade Bambara | 1980 |
| Landlord | Kristin Hunter | 1966 | | The Spook Who Sat by the Door | Sam Greenlee | 1969 |
| Light Ahead of the Negro | Edward A. Johnson | 1904 | | Those the Sun Has Loved | Rose Jourdain | 1978 |
| Many Thousands Gone | Ronald A. Fair | 1971 | | Tobias and the Angel | Frank Yerby | 1975 |
| Mind of My Mind | Octavia Butler | 1977 | | Tragic Magic | Wesley Brown | 1978 |
| Night Studies | Cyrus Colter | 1979 | | When the Whites Went | Robert Bateman | 1963 |
| | | | | Zone One | Colson Whitehead | 2011 |

Thirty-nine distinct Black Fantastic titles were found in the HTDL. This listing does not include duplicate titles and HathiTrust identification numbers. The titles on this list may or may not qualify as Black Fantastic texts. 

Samuel R. Delany, Octavia Butler, and Nalo Hopkins are authors we anticipated HathiTrust’s collection would include. Additionally, texts such as Griggs’ _Imperium in Imperio_, Chesnutt’s _The Conjure Woman_, Schuyler’s _Black No More_, and Bambara’s _The Salt Eaters_ were texts we anticipated finding. 

Although DuBois’s _Ordeal of Mansart_ was found in HathiTrust, his story “The Comet,” which is described as an early Afrofuturist text, was not. Our cursory search for Afrofuturist or Black Fantastic texts within the History of Black Writing corpus uncovered significant gaps in the HathiTrust collection. Collection building, which is beyond the scope of this limited project, is integral to future research of the Black Fantastic in HathiTrust.

## Significance  

The Black Fantastic workset can be used as a starting point for identifying characteristics of the Black Fantastic, which broadly defined includes fictional texts that exist at the “intersection of speculative practice and liberation” (Julian Chambliss). Black Fantastic speculative practice may take place in real or imagined worlds, or it may focus on the recovery of the past or a reframing of the future. The workset includes an array of texts written by Black authors, and those texts do not belong to any one genre. Instead, manual review of the texts indicates that the texts span multiple literary eras and categories of fiction. Samuel Delany and Octavia Butler are, perhaps, the most representative authors of the Black Fantastic. Their work is regularly described as science or speculative fiction. However, Sutton Griggs, W.E.B. DuBois, Charles Chesnutt, and Nalo Hopkins are also included on lists of Afrofuturist authors, because their work includes elements of the Black Fantastic. Other authors and texts on the list have not been previously identified as Afrofuturist or a part of the Black Fantastic. Their inclusion here may provide opportunities to compare and contrast and to further delimit or expand characteristics of the Black Fantastic. 


### Limitations of the workset

This project proposes that the Black Fantastic is not limited to fiction. Instead, the project investigators have suggested that Black Fantastic characteristics may also be identified in nonfiction texts, such as the writings of Mary McCleod Bethune. However, the workset does not include nonfiction texts for comparison or analysis. Additionally, the workset does not include twenty-first century Black Fantastic texts. The workset is limited to digitized texts found in the HathiTrust corpus.


## Research Questions

- Can the workset be used to test viability of TF-IDF and Topic Modeling to learn about texts that intersect race, gender, and speculative fiction?
- Can the workset be used to identify subgenres that may not be Black Fantastic but include characteristics of Black Fantastic?
- Can the workset be used to discover nonfiction texts with Black Fantastic characteristics? 
- Can the workset be used to expand topic searches within Black fiction?
- Can the workset be used to build out a keyword list that aids in identifying texts written by Black writers?

-----
[^1]: Clarissa West-White (Bethune-Cookman University, whitec@cookman.edu); Seretha Williams (Augusta University, seretha.williams@augusta.edu).