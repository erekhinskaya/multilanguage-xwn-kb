
Multilingual Extended WordNet Knowledge Base 0.9 for WordNet 3.1
====================
contains the following files:

1. Semantic relations for english glosses in .csv format

  Each line contains synset identifying gloss, relation type, first argument synset, second argument synset.

  For example, synset tam#n#4394182 has gloss 'a woolen cap of Scottish origin',
  which contatins relation VALUE between woolen#a#3142357 and cap#n#2958374
  is represented as: tam#n#4394182,VAL,woolen#a#3142357,cap#n#2958374

  Each synset is represented as lemma#pos#offset.
  Lemma is preserved for readability and to handle words in glosses that do not have corresponding synsets, i.e. 'its'. 
  Such words has offset=-1.
  
2. Translations of synsets in glosses in .csv format:
 
  Each line contains synset from english WordNet and translations to a target language

If you want to report errors or propose possible improvements, please write to: erekhinskaya@hlt.utdallas.edu
