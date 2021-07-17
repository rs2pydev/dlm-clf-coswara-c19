# I. Description

Project [Coswara](https://github.com/iiscleap/Coswara-Data) by Indian Institute of Science (IISc) Bangalore is an attempt to build a diagnostic tool for Covid-19 based on respiratory, cough and speech sounds. The project is in the data collection stage now. It requires the participants to provide a recording of breathing sounds, cough sounds, sustained phonation of vowel sounds and a counting exercise. 

NOTE: This repository contains the raw audio data received at https://coswara.iisc.ac.in/. 

The annotation process of this is ongoing (https://github.com/iiscleap/Coswara-Exp) and would be delayed compared to the uploaded data here. This is the data repository for Project Coswara (https://coswara.iisc.ac.in/). To view more information about the database such as distributions of gender, age, etc. [click here](https://iiscleap.github.io/coswara-blog/coswara/2020/11/23/visualize_coswara_data_metadata.html)

Each folder contains metadata and recordings corresponding to a person. To download and extract the data, you can run the script extract_data.py. Voice samples collected include breathing sounds (fast and slow), cough sounds (deep and shallow), phonation of sustained vowels (/a/ as in made, /i/,/o/), and counting numbers at slow and fast pace. Metadata information collected includes the participant's age, gender, location (country, state/ province), current health status (healthy/ exposed/ positive/recovered) and the presence of comorbidities (pre-existing medical conditions). 

# II. Important Links:

- [Google Colab Notebook](https://colab.research.google.com/github/iiscleap/coswara-blog/blob/master/_notebooks/2020-11-23-visualize_coswara_data_metadata.ipynb)
- [Binder Notebook](https://hub.gke2.mybinder.org/user/iiscleap-coswara-blog-ska67jbp/notebooks/_notebooks/2020-11-23-visualize_coswara_data_metadata.ipynb)
- [Dataset Link](https://raw.githubusercontent.com/iiscleap/Coswara-Data/master/combined_data.csv)

