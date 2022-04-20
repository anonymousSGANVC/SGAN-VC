# SGAN-VC: A Subband-based Generative Adversarial Network for Non-parallel Many-to-many Voice Conversion
Non-parallel many-to-many voice conversion transfers the speech of the source speaker into an arbitrary style of the target speaker without parallel data, while keeping the source speech content unchanged. Especially when the target speaker does not exist in the training set, it is a challenge to accurately extract style information. Therefore, the task demands the model to have excellent robustness and generalization.

We propose a new voice conversion framework, i.e., Subband-based Generative Adversarial Network for Voice Conversion (SGAN-VC), explicitly exploits the style spatial characteristics of different subbands to convert each subband content of source speech separately. 

# Many-to-many Voice Conversion Samples
## VCTK Corpus
VCTK Corpus contains approximately 44 hours of speech recordings from 109 speakers with various accents. These sentences are selected from multiple media or archives. Each speaker reads out about 400 sentences selected by the greedy algorithm. VCTK Corpus contains 47 male speakers and 62 female speakers, with a relatively balanced gender ratio.

### Female to Female
