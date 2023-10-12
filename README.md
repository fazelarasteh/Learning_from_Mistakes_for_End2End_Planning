# Learning_from_Mistakes_for_End2End_Planning

NOTE: We are actively testing and improving our models with Nuplan data. This page is to report our latest results.

| model | data-set  | overall-score | ego-progress-along-expert-route | no-ego-at-fault-collisions | time-to-collision-within-bound |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| UrbanDrive (with augmentation) | private testset (leader board) | 0.6821 | 0.8417 | 0.8952 | 0.8065 |
| IDMPlanner | private testset (leader board) | 0.7243 | 0.8144 | 0.8367 | 0.7762 |
| CS-Tu | private testset (leader board) | 0.9276 | 0.9141 | 0.9879 | 0.9254 |
| SimplePlanner  | public testset | 0.294318 | 0.496391 | 0.732179 | 0.691446 |
| UrbanDrive (without augmentation) |  public testset | 0.388708  | 0.898438  | 0.639957 | 0.57265 |
| IDMPlanner | public testset | 0.702864 | 0.837308 | 0.865385 |  0.752137 |
| LFM-cs | public testset | - | - | - | - | 
