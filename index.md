# SGAN-VC: A Subband-based Generative Adversarial Network for Non-parallel Many-to-many Voice Conversion

<!-- You can use the [editor on GitHub](https://github.com/anonymousSGANVC/SGAN-VC.github.io/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files. -->

Non-parallel many-to-many voice conversion transfers the speech of the source speaker into an arbitrary style of the target speaker without parallel data, while keeping the source speech content unchanged. Especially when the target speaker does not exist in the training set, it is a challenge to accurately extract style information. Therefore, the task demands the model to have excellent robustness and generalization.

We propose a new voice conversion framework, i.e., Subband-based Generative Adversarial Network for Voice Conversion (SGAN-VC), explicitly exploits the style spatial characteristics of different subbands to convert each subband content of source speech separately. 

# Dataset
## VCTK Corpus
VCTK Corpus contains approximately 44 hours of speech recordings from 109 speakers with various accents. These sentences are selected from multiple media or archives. Each speaker reads out about 400 sentences selected by the greedy algorithm. VCTK Corpus contains 47 male speakers and 62 female speakers, with a relatively balanced gender ratio.

## AISHELL3
is a large-scale and high-fidelity multi-speaker Mandarin speech corpus. 
The corpus contains roughly 85 hours of recordings produced by 218 native Chinese speakers (consisting of 176 female and 42 male) and a total of 88,035 utterances. Due to the unbalanced gender ratio of AISHELL3, we employ all-male speakers and a randomly selected array of 42 female speakers as our evaluation dataset, called AISHELL3-84. Likewise, 5 male and 5 female data are randomly selected in AISHELL3-84 as the final test set. 

# Many-to-many Voice Conversion
## Female to Female
| | VCTK Corpus | AISHELL3-84 |
|---- | ---- | ---- | 
| | Sample 1 | Sample 2 | Sample 1 | Sample 2|
|Source | ---- | ---- | ---- | ----|
|Target | ---- | ---- | ---- | ----|
|StarGANv2-VC-noASR| ---- | ---- | ---- | ----|
|StarGANv2-VC-ASR | ---- | ---- | ---- | ----|
|SGAN-VC-Unseen | ---- | ---- | ---- | ----|
|SGAN-VC-Seen | ---- | ---- | ---- | ----|



## Female to Male
## Male to Female
## Male to Male


- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/anonymousSGANVC/SGAN-VC.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
