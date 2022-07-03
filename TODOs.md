
## TODOS

* Finish roadmap shape
* Hook up roadmap with tags for interactivity
* Get standard bibliography for sources
* Start filling in readmes
* Make initial PR

## Roadmap scratchpd


## Resources

* Programming language
* Notebooks
* note -> basic concepts
* note -> math prerequisites

* Data manipulation
  * ndarrays - numpy
  * tabular data - pandas
  * images - opencv2
  * text - NLTK

* Basic DL Theoretic fundamentals
* Basic DL Practical fundamentals
* Basic classic ml fundmentals
  * sklearn

* data cleaning

* Data visualization

* ML engineering concepts
  * Data versioning
  * Experiment management
  * Data pipeline tools
  * Big data manipulations
  * Running experiments on cloud
  * Highlevel DL component libraries
  * Auto ML
  * Running ML on edge devices
  * GPU optimizations

* DL research concepts
  * RL in depth (sergey course)
  * NAS
  * +
  * Contrastive learning
  * Transfer learning
  * Active learning
  * One shot/few shot learning
  * Auto encoders
  * Transformers

* AI safety
  * TODO look at effective altruism youtube guide
  * goal alignmnet exposition

## Sources

* fastai book
* MDLI starting ai guide
* TODO look for more
  * Look for awsome DL guides etc 


## Useful commands

```bash
# get all entry names from balsamiq json
cat public/project/ai.json | jq '.. | objects | with_entries(select(.key | contains("controlName"))) | select(. != {}) | .controlName ' > node_names.tmp

# create stubs of all markdown files
```