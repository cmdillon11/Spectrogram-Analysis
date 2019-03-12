# Spectrogram-Analysis
Notebook to analyze image of a spectrogram and graph relative levels of color at a given frequency. Allows analysis of loudest frequency in a given image, similar to an FFT but only requires a picture of the spectrogram. 

In this case, the picture is being divided into 5 frequency bandwidths: 0-10, 10-100, 100-1000, 1000-10000, and 10000-100000 Hz.

Data analzyed from https://www.mbari.org/at-sea/cabled-observatory/mars-science-experiments/mars-hydrophone-data/

Images must be snipped or clipped indiviudally, and saved together in a folder. That folders path must be speicified in the beginning portion of the code.

Finally, a comparison image was used as a key to relate percentages of color in each image to thier total possible values. This image is called "KEY".
