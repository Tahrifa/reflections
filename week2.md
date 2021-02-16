Visualization link: https://www.biorxiv.org/content/biorxiv/early/2019/05/10/634675/F1.large.jpg?width=800&height=600&carousel=1

![image](https://user-images.githubusercontent.com/54874663/108066203-0682b280-702d-11eb-9a78-6a52484c7c24.png)

Figure (a)  belongs to original EEG signals collected during anesthesia. 
These signals are filtered by EMD (Empirical Mode Decomposition) and noise is removed in Figure (b). 
These were further used to find the depth of anesthesia.
Here, sample data points (where 256 points=1 second) are shown in x-axis and Amplitudes of the signals are shown along y-axis. 
While filtering Empirical Mode Decomposition method was used. 
EMD is a method of breaking down a signal without leaving the time domain.
The way it is decomposed implies completeness. 
Factors such as environment during the signal acquisition, acquisition method and surgical operation make the collected EEG signals contain a lot of noise. 
Because the EEG signal is weak and the external noise is generally relatively strong, the features contained in the EEG signal are easily covered by external interference. 
If noise can not be eliminated, feature vectors will be inaccurate. 
Comparing the original signal and the filtered signal, the baseline drift in the EEG signal can be eliminated.
