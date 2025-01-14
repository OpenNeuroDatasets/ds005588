# Overview

This is the dataset of an Functional Magnetic Resonance Imaging (fMRI) study of social decision-making. 

# Abstract
This study investigated the neural mechanisms involved in feelings of interpersonal guilt and responsibility evoked by social decisions. In two studies (one during fMRI), participants repeatedly chose between safe and risky monetary outcomes in social contexts. Across conditions, each participant chose for both themselves and a partner (Social condition), or the partner chose for both themselves and the participant (Partner condition), or the participant chose just for themselves (Solo condition, control). If the risky option was chosen in the Social or Partner condition, participant and partner could each receive either the high or the low outcome of a lottery with 50% probability, independently of each other. Participants were shown the outcomes for themselves and for their partner on each trial, and reported their momentary happiness every few trials. As expected, participant happiness decreased following both low lottery outcomes for themselves and for the partner. Crucially, happiness decreases following low outcomes for the partner were larger when the participant rather than their partner had made the choice, which fits an operational definition of guilt. This guilt effect was associated with BOLD signal increase in the left anterior insula. Connectivity between this region and the right inferior frontal gyrus varied depending on choice and experimental condition, suggesting that this part of prefrontal cortex is sensitive to guilt-related information during social choices. Variations in happiness were well explained by computational models based on participant’s and partner’s rewards and reward prediction errors. A model-based analysis revealed a left superior temporal sulcus cluster that tracked partner reward prediction errors that followed participant choices. Our findings identify neural mechanisms of guilt and social responsibility during social decisions under risk.


# Dataset content overview

This is an overview of the dataset content.

The data are organized as follows:

participants.tsv: Description of the participants 

./sub-XXX: subject directories

Note that there is one session per subject, with 2 runs of the task called "respo" and one T1-weighted anatomical scan.

Subject directories comprise the following subdirectories:

anat/ for T1w image
func/ for functional data

Regarding functional data, the file naming conventions is sub-XXX\_task-respo\_run-X\_bold.nii.gz, where XXX is the subject ID and X is the run number.

The events.tsv files, named sub-XXX\_task-respo\_run-X\_events.tsv, contain onsets, durations, trial_types and reward columns for the events of interest in the experiment. Please see the preprint and code on GitHub for details.

More information and material:

The code used to analyse the data and reproduce the results and figures can be dowloaded at: https://github.com/BonnSocialNeuroscienceUnit/ResponsibilityExperiment

# Contact

Johannes Schultz, Johannes.Schultz@ukbonn.de
