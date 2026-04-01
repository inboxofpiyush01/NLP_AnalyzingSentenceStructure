# NLP_AnalyzingSentenceStructure
Scanned full tweet dataset using string split to extract unique @mention tags; saved to References.txt
Applied nltk.pos_tag + ne_chunk with NP grammar {<DT>?<JJ>*<NN.*>+} to extract noun phrases per sentiment (positive/negative/neutral) into 3 files
Reused same NLTK chunking pipeline with VP grammar {<VB.*><NP|PP|CLAUSE>+} to extract verb phrases per sentiment into 3 files
Read phrase counts from output files and plotted labelled pie charts using matplotlib.pyplot.pie() for all 3 sentiment classes
