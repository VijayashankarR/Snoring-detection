# Snoring Detection
Sensing snoring automagically

At Dozee, our mission is to improve the quality of life through continuous health and well-being monitor. Our sensor tracks the quality of sleep and body vitals while a user is sleeping.

Snoring is one of the most common sleeping problems. It causes sleep deprivation to the snorers as well as the people around them. It can cause significant psychological and social damage in addition to the physiological damage to the sufferers. Multiple studies reveal a positive correlation between loud snoring and risk of heart attack and stroke. 

There have been many attempts to identify snoring instances through microphones but not many to detect it using body vibrations (ballistocardiography). Your mission, should you chose to accept it, is to write code to do the same. In the data folder you can find 5 files of 4 minutes of vibration data each with some snoring instances in them.

The image below represents normal time series data without snoring. 

![Scheme](images/snoring1.png)

The image below represents time series data with snoring instances marked.

![Scheme](images/snoring2.png)

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------




Snoring Detection kaggle notebook

https://www.kaggle.com/vijayashankar96/snoring-detection



Clone data from https://bitbucket.org/turtleshelltechnologies/snoring
Import Libraries,
Read the datas,
Librosa core Spectrum Can used for Processing,
Plot telementry values,
# fig, ax = plt.subplots(figsize=(24, 12))
# img = librosa.display.specshow(S, y_axis='log', ax=ax)
# ax.set_title('Power spectrogram')
# fig.colorbar(img, ax=ax, format="%+2.0f dB")
Generated training sequences for use in the model.
Plot time series X train,
Create Y-train using X-train,
Create sequences from test values,
Finally Plot the result
