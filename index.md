# COVID-19 Onset and Recovery Detection With Wearable Devices   
## Charlie Carver, Hunter J. Gallant, Viney Regunath, and Ho Man Colman Leung

### Objective

Given the continued relentlessness of COVID-19, proactive detection is essential for long-term management of the disease. Wearable devices offer an elegant solution to this problem, given their ubiquity and rich set of collected data. Prior work has already shown the possibility of using heart rate variability to detect the onset of COVID19 using wearable device data[^r1][^r2][^r3][^r4]. However, little work has been conducted on exploring how other sensing features (e.g., sleep duration, sleep variability) fare at predicting the onset of COVID19, and even less on detecting the recovery of COVID19. This project aims to explore the additional features provided by our dataset[^r5] at both predicting COVID19 onset and recovery.

### Innovation

Our proposed project relates to identifying other features such as sleep duration to indicate COVID onset. Since the onset of the outbreak, many researchers in the scientific community have tried to discover symptoms of COVID-19 in patients or clear universal signs of recovery from the virus. For instance, Jahrami et. al 2021 mentions how there is a correlation between higher rates of sleep problems and COVID-19 patients[^r6]. However, many studies such as Borsetto et al. mentioned that it is difficult to diagnose patients with COVID-19 without the use of antigen or PCR tests due to how similar said symptoms are to those of the common flu[^r7]. Furthermore, Borsetto mentions that the prevalence of COVID-19 among those with flu-like symptoms can vary substantially based on geographical context and phase of the disease. Studies from Tostmann et al. and  Zayet et al[^r8][^r9]. confirm this problem. The Wellroy dataset provides us an unprecedented opportunity to analyze COVID-19 trends throughout the world. We hope to infer new trends based on new studies on the disease and also prove that wearable technology can contribute greatly in the field of epidemiology. 


### Data Description

This data is separated into three primary sections, with several CSVs for each.

1. *Heart Rate Variability.* The Welltory Team used Bluetooth-enabled heart rate monitors, or in some instances, a high-resolution smartphone camera, to measure each subject's heart rate.

2. *Data from user-connected gadgets.* this data includes Apple Watch and Garmin, which synchronize with health apps. This can measure number of steps taken, the speed of those steps, calories burned, and a variety of other data inputs. 

3. *Clinically validated physical and mental health assessments.* They have datasets where users would input results from COVID tests and mental health assessments. The text results are standardized within the CSV to simplify analysis.

### P2: Exploratory Analysis

Our Google Colab notebook can be [downloaded here](p2.ipynb), and a PDF of our plots can be [downloaded here](p2.pdf). 

### P4: Initial Results

To view our initial results, please look at our [Google Colab notebook](p4.ipynb) or a [PDF output here](p4.pdf).

### P5: Final Paper

To view the final results from [our paper](paper.pdf), please look at our [Google Colab notebook](p5.ipynb) or a [PDF output here](p5.pdf).

### References

[^r1]: Mason, Ashley E., Frederick M. Hecht, Shakti K. Davis, Joseph L. Natale, Wendy Hartogensis, Natalie Damaso, Kajal T. Claypool et al. "Detection of COVID-19 using multimodal data from a wearable device: results from the first TemPredict Study." Scientific reports 12, no. 1 (2022): 1-15.
[^r2]: Tanwar, Gatha, Ritu Chauhan, Madhusudan Singh, and Dhananjay Singh. "Pre-emption of affliction severity using HRV measurements from a smart wearable; case-study on SARS-CoV-2 symptoms." Sensors 20, no. 24 (2020): 7068.
[^r3]: Hijazi, Haytham, Manar Abu Talib, Ahmad Hasasneh, Ali Bou Nassif, Nafisa Ahmed, and Qassim Nasir. "Wearable Devices, Smartphones, and Interpretable Artificial Intelligence in Combating COVID-19." Sensors 21, no. 24 (2021): 8424.
[^r4]: Ponomarev, Alexey, Konstantin Tyapochkin, Ekaterina Surkova, Evgeniya Smorodnikova, and Pavel Pravdin. "Heart rate variability as a prospective predictor of early COVID-19 symptoms." medRxiv (2021).
[^r5]: Pavel. 2021. “COVID-19 and Wearables Open Data Research.” OSF. December 21. osf.io/zd7gq.
[^r6]:  Jahrami, Haitham, et al. "Sleep problems during the COVID-19 pandemic by population: a systematic review and meta-analysis." Journal of Clinical Sleep Medicine 17.2 (2021): 299-313.
[^r7]:   Boscolo‐Rizzo, Paolo, Daniele Borsetto, and Claire Hopkins. "Challenges in interpreting the diagnostic performance of symptoms to predict COVID‐19 status: the case of anosmia." International forum of allergy & rhinology. Wiley-Blackwell, 2020.
[^r8]: Tostmann A, Bradley J, Bousema T, et al. Strong associations and moderate predictive value of early symptoms for SARS-CoV-2 test positivity among healthcare workers, the Netherlands, March 2020. Eurosurveillance 2020;25(16):2000508. 
[^r9]: Zayet S, Klopfenstein T, Mercier J, et al. Contribution of anosmia and dysgeusia for diagnostic of COVID-19 in outpatients. Infection Published online May 14, 2020

