# Tag-ProbeMethod-CMS
This code is on the tag & probe technique which is used in calculating the CMS detector efficiency by studying the Z boson decay into muon and antimuon pairs.
The programme works first by analyzing the root files and creating a list of events containing dimuon events' lists at the begining of the iteration.
Analyzing the list of events it segregates the tag muons which are those muons that pass the tight selection criteria and pairing them with other left muons which are probe muons using the random shuffling.
It then calculates the invariant mass from both of the transverse momentum of tag and probe muons. 
