# FDIA-dataset
The exact values of false data (and signal type) injected and the actual nominal value of the signal are in the above nine files. For example, the file of LOT-LLPF indicates the data generated under line outage topology and lower lever power fluctuation. In the LOT-LLPF file, data_LLPF_LOT_FDIA_collected.mat represents the FDIA data generated in IEEE 30-bus system, and data_LLPF_LOT_selected.mat indicates the normal data generated in IEEE 30-bus systems. In addition, if the IEEE_118 suffix is added after the mat file, it indicates that the data was generated in the IEEE 118-bus system.

The grid parameters used for training and testing are in case30.m and case118.m.

The br_means_inx.mat, inj_means_inx.mat and v_means_idx.mat are measurement vector index of IEEE 118-bus systems for state estimation and can be observed by attackers. LRT_branch_index.mat is used for generated LRT data. features_br_idx.mat is the remaining feature for model input.
