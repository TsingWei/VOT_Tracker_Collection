# Archive of Classical Visual Trackers
- Least modifications are made on these trackers to benchmarking their runing speed (on PyTorch).
- :alien: Some trackers here may fall behind the original repo. (I finished this work before ~2023.09)
- All codes are tested on Python 3.8 and PyTorch 1.12.0. You may install other necessary packages by yourself.

## ARTrack
- Config of 384x384 added.
- Speed test: `ARTrack/tracking/profile_model.py`.

## ETTrack
- Set `params.use_gpu = True` in `ettrack/pytracking/parameter/et_tracker/et_tracker.py`. 
- Modification: Directly feed the z_feature instead of z_image in `ettrack/tracking/basic_model/et_tracker.py`.
- Speed test: `ettrack/profile_.py`.

## FEAR
- Speed test: `FEARTracker/evaluate/macs_params.py`.
- Due to possible network issue, you may need to set the proxy.

## GRM
- Speed test: `GRM/tracking/profile_model.py`.

## HCAT
- Speed test: `HCAT/pysot_toolkit/pytorch2onnx.py`

## HiFT
- Speed test: `HiFT/profile_.py`

## HiT
- Speed test: `HiT/tracking/profile_model_*.py`

## LightTrack
- Speed test: `LightTrack/tracking/FLOPs_Params.py`

## PyTracking
### ATOM
- Speed test: `pytracking/profile_atom.py`
### ECO, DiMP series, ToMP
- Only implemented the End-to-End testing (including video file reading), you have to prepare a video file as input.
- Speed test: `pytracking/pytracking/profile_model.py`

## SimTrack
- Speed test: `SimTrack/tracking/profile_model.py`

## TMT(TrDiMP)
- Only implemented the End-to-End testing (including video file reading), you have to prepare a video file as input.
- Speed test: `TransformerTrack/pytracking/profile_model.py`

## TransT
- Speed test: `TransT/profile.py`