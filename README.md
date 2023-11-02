# Sound-Detection
The main objective of this project is to develop digital methods for detecting a reference sound in a video or audio file. We want to predict its starting time in the target sample.

## Code and details

* The notebook [1_introduction_to_sound_processing.ipynb](https://github.com/centralelyon/Sound-Detection/blob/main/1_introduction_to_sound_processing.ipynb) defines sound and introduces methods of sound processing including filtering and time stretching.
* The notebook [2_Feature_extraction_from_Audio_signal.ipynb](https://github.com/centralelyon/Sound-Detection/blob/main/2_Feature_extraction_from_Audio_signal.ipynb) explains the multiple ways of representing a sound signal and focuses on the information that we can extract from this signal : spectral_centroid_feature, spectral rolloff, spectral bandwidth, zero_crossing rate, MFCCs etc.
* The notebook [3_Sound_detection.ipynb](https://github.com/centralelyon/Sound-Detection/blob/main/3_Sound_detection.ipynb) defines our performance criteria , evaluate the different methods (feature_based, correlation_based, spectrogram_based)  on a labeled dataset (link to dataset : (https://drive.google.com/drive/folders/1LqGDj05BkmnG4FyfKOQcJo86juj4C5Sa?usp=sharing )) and finally  conclude on the best method to use.


## Results

<img src="https://github.com/centralelyon/Sound-Detection/blob/main/results.png" alt="Results" width="300"/>

