# terminology-project-2022

This repository will contain the dataset that will be used for the terminology project 2022 for Master 2 NLP.

The dataset is made of abstracts from the computational linguistics journal: https://direct.mit.edu/coli/issue


# Directories tree


pilot/

train/

    2009/
    2010/
    ...
    2021/


dev/

    2009/
    2010/
    ...
    2021/

test/

    2009/ 
    2010/ 
    ... 
    2021/ 

# File naming

<year>-<volume>-<number>-<pages>

<year>: year of publication
<volume>: volume 
<number>: number 
<pages> : page range

ex. 2022-48-3-491-516

Extensions

    - .txt => plain text of the abstract of the publication (ex. 2022-48-3-491-516.txt)
    - .ann1 => text annotated by annotator 1 (2022-48-3-491-516.ann1)
    - .ann2 => text annotated by annotator 2 (2022-48-3-491-516.ann2)
    - .final => adjudicated annotated text


# Job distribution over groups

Each group is assigned two years of publications
- year1: the two members of the group are in charge of individually annotating in parallel the abstracts of the papers published in year1, producing .txt, .ann1 and .ann2 files
- year2: the two members are in charge of adjudicating the individual annotations (ann1 and ann2) produced by another group and producing .final files

The year distribution is given on the Arche page.









