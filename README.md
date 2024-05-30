# Financial-Complaint-Identification
**[Let the model make financial senses: A Text2Text generative approach for financial complaint identification](https://link.springer.com/chapter/10.1007/978-3-031-33380-4_5)**

The proposed model addresses the multi-task problem as a text-to-text generation task by utilizing a generative framework for financial complaint identification. Additionally, we introduce commonsense as external information to draw more informative intuitions and enhance the overall performance of the generative model.


**X-FINCORP Dataset**

We extend a Twitter-based financial complaint dataset(FINCORP), with the rationale or cause annotations for the complaint/non-complaint labels.  The dataset includes 3,133 typed samples of non-complaint and 3,149 complaint-typed samples in English. Each instance in the extended dataset (X-FINCORP) is now associated with five labels: complaint, emotion, polarity, severity, and complaint causal spans.

_Complaint Cause_ is defined as a portion of the text that expresses why the user feels compelled to file a complaint. It is the speech act used by the individual to describe the circumstances in which their expectations have been violated. 


**SOFTWARE**

The software files consist of the proposed model implementation file and the commonsense knowledge inferences files. 


**CITE**

@inproceedings{das2023let,
  title={Let the model make financial senses: A Text2Text generative approach for financial complaint identification},
  author={Das, Sarmistha and Singh, Apoorva and Jain, Raghav and Saha, Sriparna and Maurya, Alka},
  booktitle={Pacific-Asia Conference on Knowledge Discovery and Data Mining},
  pages={58--69},
  year={2023},
  organization={Springer}
}
