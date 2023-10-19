# Learning_from_Mistakes_for_End2End_Planning

NOTE: We are actively testing and improving our models with Nuplan data. This page is to report our latest results.

## Closedloop metrics on Nuplan Scnearios: 

| model | data-set  | overall-score | ego-progress-along-expert-route | no-ego-at-fault-collisions | time-to-collision-within-bound |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| UrbanDrive (with augmentation) | private testset (leader board) | 0.6821 | 0.8417 | 0.8952 | 0.8065 |
| IDMPlanner | private testset (leader board) | 0.7243 | 0.8144 | 0.8367 | 0.7762 |
| CS-Tu | private testset (leader board) | 0.9276 | 0.9141 | 0.9879 | 0.9254 |

| model | data-set  | overall-score | ego-progress-along-expert-route | no-ego-at-fault-collisions | time-to-collision-within-bound |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| SimplePlanner  | public testset | 0.294318 | 0.496391 | 0.732179 | 0.691446 |
| UrbanDrive (without augmentation) |  public testset | 0.388708  | 0.898438  | 0.639957 | 0.57265 |
| IDMPlanner | public testset | 0.702864 | 0.837308 | 0.865385 |  0.752137 |
| LfM-cs | public testset | - | - | - | - | 

## Sample performance on Nuplan Scnearios (videos from our non-reactive simulator): 

| Visual | Meaning |
| ------------- | ------------- | 
| White Dots| Candidate targets (samples from the centerlines that reach the target) | 
| Dark Green Rectangle | Expert |
| Light Green Rectangle | Ego |
| Blue Rectangle | Other tracks | 
| Red Dot | Ego action with high probablity | 
| Blue Dot | Ego acition with low probablity | 


https://github.com/fazelarasteh/LfM-4e2e-Planning/assets/32936159/46789ba2-e7e5-409d-a86c-9ed48711516e

https://github.com/fazelarasteh/LfM-4e2e-Planning/assets/32936159/47bd9055-5efa-4e96-9af0-d2a7044408b8

https://github.com/fazelarasteh/LfM-4e2e-Planning/assets/32936159/6977e49a-e9e0-4de2-81ff-f7df4829c14f

https://github.com/fazelarasteh/LfM-4e2e-Planning/assets/32936159/29317a20-0278-42a9-92a7-031259fce395

https://github.com/fazelarasteh/LfM-4e2e-Planning/assets/32936159/1f72359c-f912-4723-9713-5f440ed64b2f

https://github.com/fazelarasteh/LfM-4e2e-Planning/assets/32936159/5e5c4ee8-e9e1-485b-a173-c8b2c9802876

https://github.com/fazelarasteh/LfM-4e2e-Planning/assets/32936159/ed2bd682-bf69-412e-9998-6978d346ac91

https://github.com/fazelarasteh/LfM-4e2e-Planning/assets/32936159/f64c7270-c953-4714-9903-0d2d65a22684

https://github.com/fazelarasteh/LfM-4e2e-Planning/assets/32936159/1a8a1a59-0882-4b54-be40-8cda2dd5f5ea

https://github.com/fazelarasteh/LfM-4e2e-Planning/assets/32936159/e7fb43a1-f500-486d-90c0-128597119ac5







