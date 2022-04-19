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

## try

<audio id="audio" controls="" preload="none">
      <source id="wav" src="https://github.com/anonymousSGANVC/SGAN-VC/raw/gh-pages/samples/p239_278_mic2_to_p236_167_mic1/source_p239_278_mic2.wav">
      </audio>


## Female to Female

| | Sample 1 | Sample 2 | Sample 1 | Sample 2|
|---- | ---- | ---- | ---- | ---- | 
|Source |  | ---- | ---- | ----|
|Target | ---- | ---- | ---- | ----|
|StarGANv2-VC-noASR| ---- | ---- | ---- | ----|
|StarGANv2-VC-ASR | ---- | ---- | ---- | ----|
|SGAN-VC-Unseen | ---- | ---- | ---- | ----|
|SGAN-VC-Seen | ---- | ---- | ---- | ----|


## Female to Male
| | Sample 1 | Sample 2 | Sample 1 | Sample 2|
|---- | ---- | ---- | ---- | ---- | 
|Source | ---- | ---- | ---- | ----|
|Target | ---- | ---- | ---- | ----|
|StarGANv2-VC-noASR| ---- | ---- | ---- | ----|
|StarGANv2-VC-ASR | ---- | ---- | ---- | ----|
|SGAN-VC-Unseen | ---- | ---- | ---- | ----|
|SGAN-VC-Seen | ---- | ---- | ---- | ----|


## Male to Female

| | Sample 1 | Sample 2 | Sample 1 | Sample 2|
|---- | ---- | ---- | ---- | ---- | 
|Source | ---- | ---- | ---- | ----|
|Target | ---- | ---- | ---- | ----|
|StarGANv2-VC-noASR| ---- | ---- | ---- | ----|
|StarGANv2-VC-ASR | ---- | ---- | ---- | ----|
|SGAN-VC-Unseen | ---- | ---- | ---- | ----|
|SGAN-VC-Seen | ---- | ---- | ---- | ----|

## Male to Male

| | Sample 1 | Sample 2 | Sample 1 | Sample 2|
|---- | ---- | ---- | ---- | ---- | 
|Source | ---- | ---- | ---- | ----|
|Target | ---- | ---- | ---- | ----|
|StarGANv2-VC-noASR| ---- | ---- | ---- | ----|
|StarGANv2-VC-ASR | ---- | ---- | ---- | ----|
|SGAN-VC-Unseen | ---- | ---- | ---- | ----|
|SGAN-VC-Seen | ---- | ---- | ---- | ----|
