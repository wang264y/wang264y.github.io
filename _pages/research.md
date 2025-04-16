---
layout: archive
title: "Research Experiences"

author_profile: true

redirect_from: 
  - /research/
  - /research.html
---

Below are the research projects I have done in the past few years. 

## Privacy and Utility Metrics Generation and Data Analytics 

**Abstract:** The sensitive nature of electronic health records (EHR) and wearable data poses significant challenges for sharing biomedical resources while mitigating re-identification risks. This study evaluates two synthetic data generation methods – DataSifter, a statistical obfuscation method, and the Synthetic Data Vault (SDV), a synthetic data generator – to create privacy-preserving "digital twins" from real-world datasets comprising EHR and Apple Watch-derived activity data (3,029 participants). By applying varying obfuscation levels (DataSifter: small, medium, large; SDV: CTGAN and Gaussian Copula), the generated synthetic datasets were assessed using utility metrics (e.g., statistical fidelity, machine learning performance) and privacy metrics (e.g., re-identification risk, detection likelihood). Results demonstrated that DataSifter (large obfuscation) achieved the highest privacy scores (e.g., 0.83 average privacy score) while maintaining moderate utility (e.g., 83.1% confidence interval overlap in regression models), outperforming SDV methods, which struggled with longitudinal data and exhibited lower utility (e.g., near-zero regression accuracy). Applying machine learning tasks to the native and synthetic digital twin data demonstrated declining performance with higher levels of obfuscation, yet broadly preserving the utility of the subsequent analytical tasks. This study highlights the importance of generating digital twin datasets and the adaptability of the DataSifter in balancing the privacy-utility trade off, offering a scalable solution for secure data sharing. These findings underscore the potential of synthetic data with heterogeneous elements to enhance collaborative research while safeguarding sensitive health information, though challenges remain in desensitizing some overly complex, unstructured, and high-dimensional data types.

This research is conducted at University of Michigan, Ann Arbor, Statistics Online Computational Resource Team with [Yipeng Liu](https://www.linkedin.com/in/yipeng-liu-efraim/), under the mentorship of [Dr. Simeone Marino](https://scholar.google.com/citations?user=6CFSyAIAAAAJ&hl=en) and [Professor Ivo Dinov](https://nursing.umich.edu/faculty-staff/faculty/ivo-d-dinov). Our manuscript titled "Medical Data Sharing and Synthetic Clinical Data Generation – Maximizing Biomedical Resource Utilization and Minimizing Participant Re-identification Risks" is currently submitted to NPJ Digital Medicine for review.  

## Parking Functions and Unit Interval Parking Functions with Fixed Ascent and Descent Sets

**Abstract:** We recall that unit interval parking functions of length $n$ are a subset of parking functions in which every car parks in its preference or in the spot after its preference, and Fubini rankings of length n are rankings of $n$ competitors allowing for ties. We present an independent proof of a result of Hadaway, which establishes that unit interval parking functions and Fubini rankings are in bijection. We also prove that the cardinality of these sets are given by Fubini numbers. In addition, we give a complete characterization of unit interval parking functions by determining when a rearrangement of a unit interval parking function is again a unit interval parking function. This
yields an identity for the Fubini numbers as a sum of multinomials over compositions. Moreover, we introduce a generalization of Fubini rankings, which we call the $r$-Fubini rankings of length $n + r$. We show that this set is in bijection with unit interval parking functions of length $n + r$ where the first $r$ cars have distinct preferences. We conclude by establishing that these sets are enumerated by the $r$-Fubini numbers.

This research was completed at the [Summer@ICERM 2022 REU](https://icerm.brown.edu/summerug/2022/) in Providence, Rhode Island with Eva Reutercrona (Pacific Lutheran University) and Juliet Whidden (Vassar College), under the mentorship of [Professor Gordon Rojas Kirby](https://sites.google.com/view/girkirby/), [Professor Pamela E. Harris](https://www.pamelaeharris.com/), [Professor Jennifer Elder](https://jennifer.totallyconsultants.com/) and graduate student S. Alex Bradt. Our paper is accepted and published (See publication section).

**Talks and Posters:**

1. 2022 Summer@ICERM Final Presentation ([slide](https://app.icerm.brown.edu/assets/372/4320/4320_3425_Reutercrona-Wang-Whidden_080320221100_Slides.pdf))
2. 2023 Joint Mathematics Meeting - Pi Mu Epsilon Poster Session ([poster](files/pf_poster.pdf))
3. 2023 Joint Mathematics Meeting - Pi Mu Epsilon Contributed Session on Research by Undergraduates

## Determination of Average Time that A Particle Escapes from a Channel with Diverse Parameters

**Abstract:** As a particle bounces within a macroscopic billiard table, microstructures affect the frequency of output angles. There also exists a connection between macrostructures and microstructures, both of which determining particle behavior, which we quantify as the mean escape time. In the case of a microstructure that introduces specular diffuse collision law, the mean escape time is reminiscent of martingales and optional stopping theorem. With triangular microgeometry, the output angles are finite. We begin to construct the transition matrix which models the behavior of these output angles, and define the ways in which the angles transform within the triangular cells.

This research was completed at Summer 2021 REU at Mount Holyoke College with Ruozhen Gong and Emily Rosaci, under the mentorship of [Professor Timothy Chumley](https://tchumley.mtholyoke.edu/?_ga=2.98059675.564660943.1704846727-1838912408.1704846727). Our group wrote a [final report](https://tchumley.mtholyoke.edu/pdf/Summer_2021_research_report.pdf) and built an [R-shiny app](https://olypys-yuxuan-wang.shinyapps.io/Billiards_Probability_and_their_Interplay/) to showcase our results.

## Leveraging Financial News Analysis to Predict Stock Price Movement

**Abstract:** Stock market predictions have been prominent among scholars. Sentiment analysis applying financial news articles for predicting stock has also grown in popularity over the past few decades. Our research indicates the impact of sentiment analysis of financial news on forecasting asset prices. In this research, sentiment is culled from financial news of companies over the past three years. Subsequently the asset prices can be predicted using stock market data, alongside sentiment analysis data with several machine learning algorithms. The results show a more convincing level of precision in the aggregation of both stock market data and sentiment analysis data.

This research was completed in Summer 2020 CIS REU with Mingchen Xu (Shanghai International Studies University), Yiran Huang (Nankai University), and Mulei Xu, under the mentorship of Professor Patrick Houlihan at Columbia University. Our published paper is available [here](https://www.airitilibrary.com/Article/Detail/P20200813001-202107-202107160001-202107160001-265-276). 

