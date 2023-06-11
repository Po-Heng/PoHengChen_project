---
type: "project" # DON'T TOUCH THIS ! :)
date: "2023-06-11" # Date you first upload your project.
# Title of your project (we like creative title)
title: "Uncovering the process of reprioritizing weaker meanings in human brain"

# List the names of the collaborators within the [ ]. If alone, simple put your name within []
names: [Po-Heng Chen]

# Your project GitHub repository URL
github_repo: https://github.com/Po-Heng/PoHengChen_project

# If you are working on a project that has website, indicate the full url including "https://" below or leave it empty.
website:

# List +- 4 keywords that best describe your project within []. Note that the project summary also involves a number of key words. Those are listed on top of the [github repository](https://github.com/PSY6983-2021/project_template), click `manage topics`.
# Please only lowercase letters
tags: [lexical ambiguity, frontal/anterior positivity, eeg/erp, meg]

# Summarize your project in < ~75 words. This description will appear at the top of your page and on the list page with other projects..

summary: "This project takes advantage of Magnetoencephalography (MEG), which has relatively good temporal and spatial resolution, to investigate the neural substrates of meaning reprioritization. MEG data were collected from 26 young participants while they read short phrases ending with either low-ambiguity words or ambiguous words in Taiwan Mandarin. Data were analyzed at sensor level and source level following the workflow of the MNE-Python software. [website]()."

# If you want to add a cover image (listpage and image in the right), add it to your directory and indicate the name
# below with the extension.
image: ""
---
<!-- This is an html comment and this won't appear in the rendered page. You are now editing the "content" area, the core of your description. Everything that you can do in markdown is allowed below. We added a couple of comments to guide your through documenting your progress. -->

## Project definition

### Background

Prior Electroencephalography (EEG) studies have demonstrated an enhanced anterior positivity for weaker but plausible meanings (e.g., an unexpected but understandable word in a highly-constraining context, or a less frequent meaning of an ambiguous word). However, the downside of EEG is its bad spatial resolution. So even though EEG research found this positivity effect more robust in anterior areas on the scalp, we still don’t know which area in human brain is responsible for or related to the process indexed by this anterior positivity effect. This project takes advantage of Magnetoencephalography (MEG), which has relatively good temporal and spatial resolution, to investigate the neural substrates of meaning reprioritization (which was reflected by the anterior positivity in past EEG studies).

### Tools

This project uses the following tools:
 * MNE-Python
 * NumPy
 * Github

### Data

MEG data were collected from 26 young participants while they read short phrases in Taiwan Mandarin. These phrases ended with a target word, which could be a low-ambiguity word or an ambiguous word. Each target word was preceded by a one-word minimal context that is semantically non-predictive but syntactically well-defined. For ambiguous words, the minimal context could be syntactically-biased toward either the frequent or the less frequent meaning.

### Deliverables

At the end of this project, we have:
  * a sensor-level preprocessing scripts for individual data
  * a source-level preprocessing scripts for individual data
  * a grand averaging and plotting scripts for sensor-level data
  * a grand averaging and plotting scripts for source-level data

## Results

### Progress overview

Data from 26 young participants were analyzed at sensor level and source level following the workflow of the MNE-Python software. Data from 3 participants were excluded due to excessive artifacts or incomplete dataset. Finally, 23 participants' data were averaged together.

### Tools I learned during this project

 * **MNE-Python** We used this tool to process MEG data.
 * **NumPy** We used this tool for computation (e.g., averaging).
 * **Github** We used this tool to open the scripts and present preliminary findings.

### Results

#### Sensor level

We found subordinate meanings elicited greater responses than dominant meanings/unambiguous words on the right-side sensors. These conditional differences were mainly present in two time windows: 100-300 ms and 600-900 ms. Intriguing, the pattern was reversed on the left-posterior sensors. However, 

#### Source level

Within the 100-300 ms time window, subordinate meanings seem to elicit greater responses than dominant meanings in the left temporal and parietal regions and the right occipital regions. Unambiguous words seem to elicit greater responses than dominant/subordinate meanings in the right temporal and occipital regions.

Within the 600-900 ms time window, subordinate meanings seem to elicit greater responses than dominant meanings in the left and right parietal regions, while dominant meanings seem to elicit greater responses than subordinate meanings in the left temporal regions. Unambiguous words seem to elicit greater responses than dominant/subordinate meanings in the right temporal regions.

## Conclusion and acknowledgement

This project helps us better understand the neural substrates of meaning reprioritization (which was reflected by the anterior positivity in past EEG studies). At sensor level, some differences between subordinate meanings and the other two conditions (i.e., dominant meanings and unambiguous words) were mainly observed in two time windows: 100~300 ms (probably related to early detection of mismatched word class information, e.g. Dikker et al., 2010) and 600~900 ms (probably related to higher-level meaning integration/reprioritization). At source level, in the earlier time window (100-300 ms), subordinate meanings seem to elicit greater responses than dominant meanings in the left temporal and parietal regions and the right occipital regions. In the later time window (600-900 ms), our brain seems to process alternative meanings of ambiguous words simultaneously in different regions (e.g., temporal and parietal regions). These preliminary findings still need more careful validation in the future.

Finally, we want to thank Prof. Chun-hsien Hsu, Prof. Chia-lin Lee, Yani Wu, Yun Chuang, and Chia-ho Lai for their helpful comments and assistance in data collection and preprocessing.