# C147/247 Final Project
### Winter 2026 

In this project, I trained and evaluated different architectures (GRU and TDS + GRU) versus the baseline TDS Conv Net Model on the single subject, ID \#89335547 from the emg2qwerty dataset. I then analyzed the relationship between the amount of training data and CER using our best model.

Code edits were made in:
  - ```lightning.py``` + ```modules.py``` - Addition of GRU Encoders
  - ```config/model.yaml``` - Added files to configure the model architectures
  - ```config/user.yaml``` - Added files to change the number of user training data sessions
