# P-Finder
P Finder is a GUI software application for the fast identification of RNase P RNA in prokaryotes.


### Description
P Finder is written in C# and has been tested in multiple 64-bit Windows environments (Windows 7/8/Vista). It has a user-friendly graphical user interface (GUI) that allows for intuitive RNase P RNA identification and/or annotation.  The user can select from four search criteria including the use multiple threads. In addition, the user can determine what display data they wish to incorporate in the output such as: bitscore, E-value, percent ID, start location, end location, the strand in which the sequence is located, and of course the sequence itself.  P Finder is the only available algorithm that is capable of not only identifying the RNase P RNA for annotation but also differentiating among the five different RNase P RNA structural types (A, B, C, M, and T) with the option to select these data types for display in the final output. 

### Installation

The installation is comprised of two zip files. 

1) Download the extensions.zip folder
2) Unzip the extentions.zip folder
3) Place the  extensions folder in your C:\ drive so that the path is C:\extenstions

Now install P-Finder

1) download the PFinder.zip folder
2) Unzip PFinder.zip
3) Double click the setup icon and follow the instructions


### Options

E value - The Expectation value or Expect value represents the number of different alignments with scores equivalent to or better than S that is expected to occur in a database search by chance. The lower the E value, the more significant the score and the alignment.

Bit score - The bit score, S', is derived from the raw alignment score, S, taking the statistical properties of the scoring system into account. Because bit scores are normalized with respect to the scoring system, they can be used to compare alignment scores from different searches.

Minimum Sequence Length - The minimum length of a sequence length allowed

Number of Threads - Number of threads to be used for parallel processing.

Percent ID - A quantitative measurement of the similarity between two sequences. Closely related species are expected to have a higher percent identity for a given sequence than would more distantly related species, and thus percent identity to a degree reflects relatedness. 

Type - The structural classification of the RNase P RNA

Start location - location of the first nucleotide in the gene sequence

End location - location of the last nucleotide in the gene sequence

Strand - sequence location on either the plus or minus strand

Sequence - the DNA sequence of the RNase P RNA gene
  
### License
This program is distributed under the BSD 3-clause "New" or "Revised" License



