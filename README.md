# SciMed_preview_bst
An .bst file use with the package `natbib` that gives a preview of your reference in Oxford SciMed style (see the checklist: https://academic.oup.com/DocumentLibrary/Cybersecurity/Mini-style%20SciMed.pdf).

# Important Note
- This is NOT a perfectly valid reference style. Not exactly following SciMed either, because of some punctuation marks, bold/italic, etc.
- For preview ONLY: this style contains every element SciMed required, to make sure how many pages your manuscript fit in the template (when your supervisor is not covering any page excess fee for you.)
- Cannot implement Journal Title Abbreviation automatically. Need your manually modification in your .bib file, but it will save A LOT space. Useful link https://www.ncbi.nlm.nih.gov/nlmcatalog/journals/
- Currently only implemented for article, book, book chapter (incollection) and inproceeding. 

# Usage:
```{latex}
\Requirepackage{natbib}

%blablablah

\bibliographystyle{oxford}
\bibliography{brief-ref}
```

p.s. It's sad that neither ChatGPT nor Gemini good at writing or editing .bst. 
