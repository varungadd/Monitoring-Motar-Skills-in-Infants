# Monitoring Motor Skills in Infants

This project aims to monitor the motor skills in infants using Infant Pose Estimation.

## Introduction

Infant Pose Estimation is a computer vision project that detects and tracks the poses of infants. It provides valuable insights into their motor skills development. Currently, this project uses the [Infant-Pose-Estimation](https://github.com/ostadabbas/Infant-Pose-Estimation) repository, with additional enhancements and upgrades.

## Installation

To use this project, follow these steps:

1. Clone the [Infant-Pose-Estimation](https://github.com/ostadabbas/Infant-Pose-Estimation) repository.
2. Install the required dependencies as mentioned in the repository's README.
3. Copy the contents of the `Infant-Pose-Estimation` folder from this project into the cloned repository.


## Additional Scripts

Use these scripts to download the models and dataset. This also organizes them into specific folders.

```python
python Infant-Pose-Estimation/download_pretrained_fidip.py
```

```python
python Infant-Pose-Estimation/download_pretrained_hrnet.py
```

```python
python Infant-Pose-Estimation/download_syrip_data.py
```
#### Run the model
To run the model on a single picture use `Infant-Pose-Estimation/tools/predict_v6.py` and to run model on videos use `Infant-Pose-Estimation/tools/predict_video_v2.py`
