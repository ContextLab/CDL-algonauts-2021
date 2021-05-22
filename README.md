# Introduction and overview

This repository contains the [Contextual Dynamics Lab](http://www.context-lab.com)'s code related to the [CCN Algonauts 2021 challenge](http://algonauts.csail.mit.edu/challenge.html).

## Important dates:

| Description          | Date |
-----------------------|------|
| Training data, test data, and development kit released | May 1, 2021 |
| Challenge submission deadline | August 14, 2021 at 11:59PM (UTC-4) |
| Challenge report submission deadline | August 22, 2021 |
| Challenge results released | August 23, 2021 |
| Virtual session as [CCN 2021](https://2021.ccneuro.org/) | September 7, 2021 |

## Setup instructions

1. Read about the Algonauts 2021 challenge [here](http://algonauts.csail.mit.edu/challenge.html)
2. Follow the setup instructions [here](https://github.com/Neural-Dynamics-of-Visual-Cognition-FUB/Algonauts2021_devkit) to install the Algonauts Developer's Kit on your computer and download the data.  (*TODO: let's make a Docker container to do this part automatically*)
3. Fork this repository and clone the fork to your computer
4. Add yourself to the "Team CDL contributors" list below (you'll need to add yourself to your fork and then submit a pull request).  By adding yourself to the team, you agree to:
    - Maintain clear, open, and regular communications with your fellow team members related to work on this challenge project.  This includes joining the associated [slack channel](https://context-lab.slack.com/archives/C020V4HJFT4) and checking/contributing to it regularly while the project is active.
    - Participate in the hackathons related to the project
    - Take responsibility for the methods, code, and results
    - Assist in writing up and submitting our results

## Team CDL contributors

Note: the tabulated list of team members below is ordered by join date; author order on any publications will be determined based on contributions of:
- Code and writing (using GitHub to track commits)
- Ideas (documented on Slack and/or GitHub)

### Team members:

| Name                   | Join date   | GitHub username | Email address        |
-------------------------|-------------|-----------------|----------------------|
| Jeremy R. Manning      | May 4, 2021 | [jeremymanning](https://github.com/jeremymanning) | jeremy@dartmouth.edu |

# Approach

Some scattered thoughts (expand and refine later...)
- hyperalignment-based decoding, similar to what we used [here](https://arxiv.org/abs/1701.08290)
- some sort of deep learning-based thing-- GAN?  Autoencoder + hyperalignment?  Custom model?
- use TFA and/or timecorr features?
- connect with other datasets (e.g. Huth et al. semantic decoding, neurosynth, etc.)?

# Results

(insert description here, including links to Jupyter notebooks for reproducing any figures)

# Bibliography

1. Cichy RM, Dwivedi K, Lahner B, Lascelles A, Iamshchinina P, Graumann M, Andonian A, Murty NAR, Kay K, Roig G, Oliva A (2021) The Algonauts Project 2021 Challenge: How the Human Brain Makes Sense of a World in Motion. *arXiv*: 2104.13714. [[link](https://arxiv.org/abs/2104.13714)]
