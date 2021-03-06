# Supplementary Material and Replication Package for Paper "Bounties on Technical Q\&A Sites: A Case Study of Stack Overflow Bounties"

* [Appendix](https://github.com/SAILResearch/supportmaterial-18-jiayuan-SO_bounty/blob/master/appendix.pdf)

We provide the studied data (i.e., bounty and non-bounty questions and their corresponding studied factors) below. We also provide the scripts to build the models that were used in this study. Note that the data is stored as R objects and can be imported directly by using the provided scripts. 

* Data: 
  * [data_solvingLikelihood](https://github.com/SAILResearch/supportmaterial-18-jiayuan-SO_bounty/blob/master/data_model/data_solvingLikelihood) data (R object) for studying the solving-likelihood of bounty questions (i.e., Section 5).
  * [data_solvingLikelihood_nonBounty](https://github.com/SAILResearch/supportmaterial-18-jiayuan-SO_bounty/blob/master/data_model/data_solvingLikelihood_nonBounty) data (R object) for studying the solving-likelihood of the sampled non-bounty questions (i.e., Section 5.3).
  * [data_solvingTime](https://github.com/SAILResearch/supportmaterial-18-jiayuan-SO_bounty/blob/master/data_model/data_solvingTime) data (R object) for studying the solving-time of bounty questions (i.e., Section 6).


* Models:
  * [SolvingLikelihoodModel.R](https://github.com/SAILResearch/supportmaterial-18-jiayuan-SO_bounty/blob/master/data_model/SolvingLikelihoodModel.R) script for building the model to understand the association between the studied factors and the solving-likelihood of bounty questions (i.e., Section 5)
  * [SolvingLikelihoodNonBountyModel.R](https://github.com/SAILResearch/supportmaterial-18-jiayuan-SO_bounty/blob/master/data_model/SolvingLikelihoodNonBountyModel.R) script for building models to understand the important factors for the solving-likelihood of non-bounty and bounty questions(i.e., Section 5.3).
  * [SolvingSpeedModel.R](https://github.com/SAILResearch/supportmaterial-18-jiayuan-SO_bounty/blob/master/data_model/SolvingSpeedModel.R) script for building the model to understand the association between the studied factors and the solving-time of bounty questions (i.e., Section 6)
