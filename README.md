# ditto-inference



!MPLBACKEND=Agg /workspace/miniconda/envs/ditto/bin/python inference.py \
    --data_root "./checkpoints/ditto_pytorch" \
    --cfg_pkl "./checkpoints/ditto_cfg/v0.4_hubert_cfg_pytorch.pkl" \
    --audio_feat_path "./hubert_gt_features.npy" \
    --audio_path_for_mux "./example/samiulnew.wav" \
    --source_path "./example/image.png" \
    --output_path "./tmp/resulth.mp4"
