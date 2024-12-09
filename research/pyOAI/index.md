---
---
{% include section.html size="full" %}

{% include figure.html image="images/python_plain.png" width="300px" %}

{% include section.html %}

This repo is a collection of Python scripts and convenience functions for navigating and making sense of the Osteoarthritis Initiative dataset. With over 11,000 variables tracked for almost 5,000 patients, this project is a medical goldmine. It is also less than trivial to get a sense of where to start. The scripts in this repo attempt to help by making public the initial code that any researchers would need to write to use the data outside of SAS.

Check it out: {%
  include button.html
  type="github"
  link="pyOAI"
  icon="fa-brands fa-github"
  text="Check it out on GitHub"
  flip=true
%}

**Included:**
- Parse all SAS files into Pandas dataframe
- Save files in a stable binary format (not pickle!)
- Even parse some documentation PDFs to extract information unique to them
- Moves data to a multi-level index so that a single variable name covers all visits (but visits are their own level)
- Summarizes data
- Maintains the different types of SAS missing values even though it isn't native to Pandas
- Optimizes storage types for fast loading, reduced memory footprint

The only request in using this library is that you mention it in the acknowledgments when you publish. Maintaining this code takes time from research work. Doing so is worth it if more people benefit and contribute.
