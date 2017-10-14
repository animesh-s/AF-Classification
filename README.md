# AF-Classification

This project encourages the development of algorithms to classify, from a single
short ECG lead recording (between 30 s and 60 s in length), whether the recording shows
normal sinus rhythm, atrial fibrillation (AF), an alternative rhythm, or is too noisy to be
classified.

AF is defined as a “tachyarrhythmia characterized by predominantly uncoordinated atrial
activation with consequent deterioration of atrial mechanical function” by the American
College of Cardiology (ACC), the American Heart Association (AHA) and the European
Society of Cardiology (ESC). AF is the most common sustained cardiac arrhythmia,
occurring in 1-2% of the general population and is associated with significant mortality and
morbidity through association of risk of death, stroke, hospitalization, heart failure and
coronary artery disease, etc. More than 12 million Europeans and North Americans are
estimated to suffer from AF, and its prevalence will likely triple in the next 30-50 years.
More importantly, the incidence of AF increases with age, from less than 0.5% at 40-50
years of age, to 5-15% for 80 year olds.

## Data	Description:

The training set contains 7000 single lead ECG recordings lasting
from 9 s to just over 60 s and the test set contains 1528 ECG recordings of similar lengths.
ECG recordings were sampled as 300 Hz and they have been band pass filtered by the
AliveCor device.
