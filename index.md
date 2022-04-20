# SGAN-VC: A Subband-based Generative Adversarial Network for Non-parallel Many-to-many Voice Conversion
Non-parallel many-to-many voice conversion transfers the speech of the source speaker into an arbitrary style of the target speaker without parallel data, while keeping the source speech content unchanged. Especially when the target speaker does not exist in the training set, it is a challenge to accurately extract style information. Therefore, the task demands the model to have excellent robustness and generalization.

We propose a new voice conversion framework, i.e., Subband-based Generative Adversarial Network for Voice Conversion (SGAN-VC), explicitly exploits the style spatial characteristics of different subbands to convert each subband content of source speech separately. 

# Many-to-many Voice Conversion Samples
## VCTK Corpus
VCTK Corpus contains approximately 44 hours of speech recordings from 109 speakers with various accents. These sentences are selected from multiple media or archives. Each speaker reads out about 400 sentences selected by the greedy algorithm. VCTK Corpus contains 47 male speakers and 62 female speakers, with a relatively balanced gender ratio.

### Female to Female

<table>
    <tr>
    	<td></td>
    	<td> Sample 1 (p233 → p236) </td>
    	<td> Sample 2 (p239 → p244) </td>
    </tr>
    <tr>
    	<td><font size="1"> Source</td>
    	<td><audio id="audio" controls="" preload="none">
      		<source id="wav" src="https://github.com/anonymousSGANVC/SGAN-VC/raw/gh-pages/samples/p233_316_mic1_to_p236_298_mic2/source_p233_316_mic1.wav">
		</audio>
		</td>
    	<td><audio id="audio" controls="" preload="none">
      		<source id="wav" src="https://github.com/anonymousSGANVC/SGAN-VC/raw/gh-pages/samples/p239_455_mic2_to_p244_400_mic1/source_p239_455_mic2.wav">
		</audio>
	    </td>
    </tr>
    <tr>
    	<td>Target</td>
    	<td><audio id="audio" controls="" preload="none">
      		<source id="wav" src="https://github.com/anonymousSGANVC/SGAN-VC/raw/gh-pages/samples/p233_316_mic1_to_p236_298_mic2/target_p236_298_mic2.wav">
		</audio>
	 	</td>
    	<td><audio id="audio" controls="" preload="none">
      		<source id="wav" src="https://github.com/anonymousSGANVC/SGAN-VC/raw/gh-pages/samples/p239_455_mic2_to_p244_400_mic1/target_p244_400_mic1.wav">
		</audio>
	    </td>
    </tr>
    <tr>
    	<td>StarGANv2-VC-noASR</td>
    	<td><audio id="audio" controls="" preload="none">
      		<source id="wav" src="https://github.com/anonymousSGANVC/SGAN-VC/raw/gh-pages/samples/p233_316_mic1_to_p236_298_mic2/starganv2-vc-noasr_p233_316_mic1_to_p236_298_mic2.wav">
		</audio>
	    </td>
    	<td><audio id="audio" controls="" preload="none">
      		<source id="wav" src="https://github.com/anonymousSGANVC/SGAN-VC/raw/gh-pages/samples/p239_455_mic2_to_p244_400_mic1/starganv2-vc-noasr_p239_455_mic2_to_p244_400_mic1.wav">
	    </td>
    </tr>
    <tr>
    	<td>StarGANv2-VC-ASR</td>
    	<td><audio id="audio" controls="" preload="none">
      		<source id="wav" src="https://github.com/anonymousSGANVC/SGAN-VC/raw/gh-pages/samples/p233_316_mic1_to_p236_298_mic2/starganv2-vc-asr_p233_316_mic1_to_p236_298_mic2.wav">
		</audio>
	    </td>
    	<td><audio id="audio" controls="" preload="none">
      		<source id="wav" src="https://github.com/anonymousSGANVC/SGAN-VC/raw/gh-pages/samples/p239_455_mic2_to_p244_400_mic1/starganv2-vc-asr_p239_455_mic2_to_p244_400_mic1.wav">
		</audio>
	    </td>
    </tr>
    <tr>
    	<td>SGAN-VC-Unseen</td>
    	<td><audio id="audio" controls="" preload="none">
      		<source id="wav" src="https://github.com/anonymousSGANVC/SGAN-VC/raw/gh-pages/samples/p233_316_mic1_to_p236_298_mic2/sganvc_unseen_p233_316_mic1_to_p236_298_mic2.wav">
		</audio>
	    </td>
    	<td><audio id="audio" controls="" preload="none">
      		<source id="wav" src="https://github.com/anonymousSGANVC/SGAN-VC/raw/gh-pages/samples/p239_455_mic2_to_p244_400_mic1/sganvc_unseen_p239_455_mic2_to_p244_400_mic1.wav">
		</audio>
	    </td>
    </tr>
</table>
