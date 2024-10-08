# Wug InDirect Evidence Test (WIDET)

## Repository Contents
- WIDET data: ```/data```
- Additional train instances: ```/data/additional_train```
    - Additional train instances that we mainly employed (<wug#123>): ```/data/additional_train/tag```
        - Direct evidence: ```de.txt```, Lexically indirect evidence: ```lexie.txt```, Syntactically Indirect evidence: ```synie.txt```
    - Additional train instances adding morphology into a tag (<wug#321>s): ```/data/additional_train/tag_w_morph```
    - Additional train instances adding morphology into a tag (wug): ```/data/additional_train/wug```
- Evaluation instances:
    - Evaluation instances that we mainly employed: ```data/eval/tag```
- Tokenizer added <wug#\n>: ```/data/tokenizer/wikipedia_vocab9k```
- Pretrain data used in this work: ```/data/pretrain```

<!-- ## For the use of insert/train/eval scripts
Install the repositorys as below at first and add args into our shell scripts.
```
git clone git@github.com:phueb/BabyBERTa.git
git clone https://github.com/babylm/evaluation-pipeline
``` -->

<!-- ## Recommended Citation
If you use WIDET in your work, please cite it as follows: -->

## License
WIDET is distributed under a [CC-BY](https://creativecommons.org/licenses/by/4.0/) license.