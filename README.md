# RVA streets
## Which Streets Share Names with Civil Rights and Confederate Leaders?

### method

1. get names of civil rights and confederate leaders
  1. pull out last names without suffixes like Jr, III
1. get street names
  1. identify stopwords in street names using most frequent short (esp. vowelless) unigrams
    1. pull out non-stopwords from street names
1. join barest civil rights and confederate leader names to barest street names
1. map!

### sources
* http://dbpedia.org/page/Confederate_States_Army
* http://dbpedia.org/page/Civil_and_political_rights
* TIGER/Line Richmond City zip
