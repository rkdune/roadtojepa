# roadtojepa
trying to make a simple jepa-based model bit by bit

most recent progress: [in this notebook](https://github.com/rkdune/roadtojepa/blob/main/predictor_with_two_encoder_road_2_jepa.ipynb)
- 90% of the way to JEPA. MLPs instead of transformer, noise instead of masking.
- allenbrainobservatory dataset
- (signal + noise) --> Enc(x) --> Pred(s_x) --> MSE <-- Enc(y) <-- signal

![image](https://github.com/rkdune/roadtojepa/assets/96749303/9e71f849-e9b9-4dba-9b67-680e83a505f7)
