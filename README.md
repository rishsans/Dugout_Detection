
# Dugout Detection from Satellite Imagery
### Detect military dugouts in satellite imagery using the YOLOv8 deep learning framework.

## Introduction
Dugouts are vital military structures, providing insights into adversary deployments. Traditional manual detection is time-consuming and labor-intensive, making automation crucial.

### What are Dugouts?

- Underground or partially underground structures.
- Types: unoccupied, occupied, and protective.
- Serve as shelter, storage, and protection.
![ss_dg](https://github.com/rishsans/Dugout_Detection/assets/98217912/d2584475-8473-4b87-a30f-54718734af7f)

## Dataset Overview

- **Source**: Google Earth.
- **Annotations**: Using Roboflow platform.
- **Size**: Augmented to 1,896 images.
- **Splits**: Training (1,600), Validation (152), Testing (100).

## Methodology

1. **Dataset Creation & Augmentation**: Enhanced using techniques like flip, rotation, and shear.
2. **YOLOv8**: Employed for its balance between speed and accuracy. Trained on our dataset for 100 epochs with image size 640x640.
3. **Transfer Learning**: Expedited training and minimized dataset needs by leveraging pre-trained models.
   
![ss_dg1](https://github.com/rishsans/Dugout_Detection/assets/98217912/4f9e28c5-3d4c-4495-a3c6-b5ade832df52)


<img src="https://github.com/rishsans/Dugout_Detection/assets/98217912/1a0bf42f-7fc5-4f26-92f0-46c16b9298fa" width="700" style="display:block; margin-bottom:200px;" />


<img src="https://github.com/rishsans/Dugout_Detection/assets/98217912/48d24315-884d-4f68-aeb7-e6c3b529fa44" width="700" style="display:block;" />

## Result Highlights

- **Precision**: Excels at low confidence thresholds, peaks around 0.9.
- **Recall**: Shows a decrease as the confidence threshold rises.
- **Potential Overfitting Indicators**: Differences noted between training and validation losses.

## Significance & Future Prospects

Automated dugout detection:

- Enhances situational awareness.
- Enables proactive decision-making.
- Holds potential for georeferencing and offline deployment in the future.
  
