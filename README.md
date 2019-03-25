# Discovery

This is a data/code release accompaning this paper:

* Title: "Mining Discourse Markers for Unsupervised Sentence Representation Learning"
* Authors: Damien Sileo, Tim Van de Cruys, Camille Pradel and Philippe Muller
* To be presented at NAACL 2019


# Contents

The Discovery datasets consists adjacent sentence pairs (s1,s2) and a marker (y) that occured at the beginning of s2. They were extracted from the [depcc](https://www.inf.uni-hamburg.de/en/inst/ab/lt/resources/data/depcc.html) web corpus. In this repository, you can find:
* a list of the 174 discourse markers we used
* a base version of our dataset with 1.74 million pairs (10k exemples per marker)
* a big version with 3.4 million pairs
* a hard version with 1.74 million pairs where the connective couldn't be predicted with a fasttext linear model

#### 5 examples from the Discovery dataset:
s1 | s2 | y
---- | ---- | ----
The  motivations  for  playing  are  vastly  different  ,  and  yet  Spin  the  Bottle  manages  to  meet  the  needs  of  all  its  players  . | It  is  a  well  crafted  game  . | truly,
Prefiguring  The  General  many  years  later  ,  Bernard  liked  nothing  better  than  to  cock  a  snoot  at  the  law  . | Men  working  on  a  bog  ,  less  than  a  mile  from  the  Kirwan  farm  ,  dug  up  a  human  torso  . | eventually,
Think  a  certain  vertical  market  or  knowledge  about  multilocations  '  unique  needs  . | Ernest  's  strength  lay  in  the  multilocation  arena  and  gives  Birch  a  new  capability  . | indeed,
@  Sklivvz  :  but  you  are  implicitly  using  one  such  interpretation  yourself  . | One  that  tells  you  that  it  's  unphysical  to  ask  anything  except  measurements  . | namely,
Perhaps  the  Jeanneau  's  are  a  bargain  compared  to  similarly  capable  boats  from  B  or  C.  . | Seattle  ,  the  prices  for  the  36  and  39  went  down  about  20G  ,  a  39  now  sells  for  a  bit  more  than  the  36  did  . | locally,

# Contacts
For further information, you can contact:

damien dot sileo at gmail dot com
