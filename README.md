# -Higgs-Boson-Event-Detection
    The Higgs boson is the fundamental particle associated with the Higgs field, a field that gives mass to other fundamental particles such as 
electrons and quarks. A particle’s mass determines how much it resists changing its speed or position when it encounters a force. Not all fundamental particles have mass. The photon, which is the particle of light and carries the electromagnetic force, has no mass at all.
      
      Higgs boson is a fundamental particle, and the classification of Higgs signals is a well-known problem in high energy physics. The identification of the 
Higgs signal is a challenging task because its signal has a resemblance to the background signals,using a deep neural network to build a robust and generalized Higgs boson prediction system to discriminate the Higgs signal from the background noise.


Dataset Details:-Dataset of 250000 events, with an ID column, 30 feature columns, a weight column and a label column.This is a classification problem in which 'Label' is a target variable, we have to predict signal or background noise, 


Some details to get started:
• all variables are floating point, except PRI_jet_num which is integer
• variables prefixed with PRI (for PRImitives) are “raw” quantities about the bunch collision as 
measured by the detector.
• variables prefixed with DER (for DERived) are quantities computed from the primitive features, 
which were selected by the physicists of ATLAS
• it can happen that for some entries some variables are meaningless or cannot be computed; in
this case, their value is −999.0, which is outside the normal range of all variables.
