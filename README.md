# MLCyber-BackdoorAttacks

├── data  // Dataset is huge so not uploaded

under cl folder
valid.h5 // this is clean validation data used to design the defense
test.h5  // this is clean test data used to evaluate the BadNet

under bd folder
bd_valid.h5 // this is sunglasses poisoned validation data
bd_test.h5  // this is sunglasses poisoned test data

├── models
bd_net.h5
bd_weights.h5

├── report //Pruned part of repaired network)
pruning_channel_model_acc_decrease_by_2%.h5
pruning_channel_model_acc_decrease_by_4%.h5
pruning_channel_model_acc_decrease_by_10%.h5
pruning_channel_model_acc_decrease_by_30%.h5  

├── Backdoor Attacks.ipynb  // Source code
└── Backdoor attacks - Report .pdf  // Report includes a table with the accuracy on clean test data and the attack success rate
└── README.md  // Lab report
└── model.png  // Main structure of the backdoored network
└── lab2.pdf  // Lab instruction and requirements

Data and model can be downloaded from here [Data](https://drive.google.com/drive/u/1/folders/1r4LWuR5lQZJVm_nnh9r17zYtfH2Xt7DZ)
