# Low-Cost Smart Stethoscope 
Problem:
20 million people are affected by Rheumatic heart disease (RHD), notably in poor countries. RHD leads to valve damage after untreated strep throat, creating a swishing sound ("murmur"). Screening depends on expert listener, but not many where RHD is common. Although ultrasound is accurate, it is costly and requires experts. AI murmur detectors exist, mostly as research software, but are not cheap devices.

Tech Stack:
To accomplish a stethoscope that is under $40 with AI that runs offline, catches less than 80% of murmurs in children the model has never heard, and clears less than 60% of children without murmurs correctly, we will utilize the following technology:
- Arduino/ESP32, C++ on Arduino IDE.
- Python, run in Google Colab (AI); CirCor DigiScope.