# twitter_election_misinfo_interventions
Repository for "Twitter flagged Donald Trump’s tweets with election misinformation. They continued to spread both on and off the platform."

## Abstract
We analyze the spread of Donald Trump’s tweets that were flagged by Twitter using two intervention strategies — attaching a warning label and blocking engagement with the tweet entirely. We find that while blocking engagement on certain tweets limited their diffusion, messages with warning labels spread further on Twitter than those without labels. However, the messages that had been blocked on Twitter remained popular on Facebook, Instagram, and Reddit, garnering more visibility and engagement than messages that had either been labeled by Twitter or received no intervention at all. Taken together, our results emphasize the importance of considering content moderation at the ecosystem level.

## BibTex Citation
Please cite the following:
```
@article{2021SandersonTwitterInterventions, title={Twitter flagged Donald Trump's tweets with election misinformation.
They continued to spread both on and off the platform.}, author={Sanderson, Zeve and Brown, Megan A. 
and Bonneau, Richard and Nagler, Jonathan and Tucker, Joshua A.}, journal={Harvard Kennedy School
Misinformation Review}, year={2021}}
```

## Repository Contents
There are three directories in this repository:
* `data`: contains Tweet labels for whether or not they are political
* `code`: contains files for each of the main figures for generating the plots
* `plots`: generated plots from the code

To install the requirements for this repository, clone the repostiory using 
```
git clone https://github.com/SMAPPNYU/twitter_election_misinfo_interventions.git
```

Then, install the requirements by running 
```
pip install -r requirements.txt
```

To generate the figures in `plots`, run each of the notebooks in `code`.
