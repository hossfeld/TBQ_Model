# TBQ Model

This Jupyter notebook implements the TBQ model and in particular the transformation of the TBQ model to estimate the *system PoW*. The System PoW is the ratio of users in a system who rate the quality as poor or worse. It is the average of PoW values based on a *QoS–PoW mapping function*. The transformation, however, allows to use an  *QoS-MOS mapping function* instead of the PoW mapping function, since literature often reports MOS mapping functions. 

The TBQ Model is defined in the following article:

> "Industrial User Experience Index vs. Quality of Experience Models" by Tobias Hoßfeld, Anika Seufert, Frank Loh, Stefan Wunderer, John Davies, accepted for publication in IEEE Communications Magazine (2022)

## Abstract
Network operators have an increased interest to understand and quantify the user perceived Quality of Experience (QoE). Appropriate QoE models allow mapping of measurable QoS parameters to QoE metrics like mean opinion scores (MOS) or poor-or-worse (PoW) ratios. Unfortunately, there are no QoE models for all applications available yet and development and standardization is rather time-consuming. For that reason, industry often implements simple, but effective approaches based on expert knowledge to get a user experience index which is capable of delivering high value insights. This index is often defined based on thresholds of measurable QoS parameters to classify the resulting user experience. The question arises whether such a threshold-based user experience index can properly estimate the QoE in a system. We will therefore answer in this work whether the user experience index is able to quantify the expected QoE in a system and if other QoE metrics like PoW ratios can be derived. Furthermore, we discuss the interpretation and the limits of the index. As key contribution, we present a detailed systematic analysis of the threshold-based QoE concept (TBQ) and discuss its usability as QoE estimation methodology for industry. 
