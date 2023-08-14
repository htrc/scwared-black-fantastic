# Introduction
The `workset` directory contains multiple data files with metadata about the workset and its volumes. Details about each file, its format, and structure are included below
explain:

## `black-fantastic-works.csv`

These are simple CSV files listing the volume ID and some additional metadata for each volume in the worksets.

The columns in the CSV file are:

- id (volume identifier)
- title 
- year (year of publication)
- language (volume language represented as ISO-369-3 language code) 
- authors

Example:

| id | title | year | language | authors |
|:---|:---   |:---  |:---      |:---     |
| uc1.$b404153 | City of a thousand suns [by] Samuel R. Delany | 1969 | eng | Delany, Samuel R |
| uc1.b3467348 | Tragic magic : a novel / by Wesley Brown. | 1978 | eng | Brown, Wesley 1945- |
| uc2.ark:/13960/t4sj1b439 | The conjure woman / by Charles W. Chesnutt. / Stephanie Perry Moore. | 1899 | eng | Chesnutt, Charles W. (Charles Waddell) 1858-1932 |
| mdp.39015000544745 | Portrait of a young man drowning. | 1962 | eng | Perry, Charles 1924-1969 |
| dul1.ark:/13960/t4wh8z13n | Kindred / Octavia E. Butler ; with an introduction by Robert Crossley. | 1988 | eng | Butler, Octavia E |


## `black-fantastic-works.json`

These are JSON files with some basic metadata about the worksets themselves, including the creators of and contributors to the worksets. Also included is a list of workset IDs as persistent links to the item in the [HathiTrust Digital Library](https://hathitrust.org).

