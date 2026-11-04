# Plan

## Object
Red jewelry box, matt surface, about 9.6 cm wide and 9.6 cm long with rounded corners, 4.7 cm high. I chose it because it is rigid, matt, high contrast against a light surface, and easy to measure with a ruler.

## Honest starting point
I am a data analyst (Python, SQL, scikit-learn). I have not trained a segmentation model or calibrated a camera before, so I expect to learn these parts as I go.

## Order of work and time budget (8 hours)
1. Calibration (1 h): print a checkerboard, take 20 or more photos, calibrate with OpenCV, save parameters, report reprojection error.
2. Dataset (2 h): take 70 or more photos of the box with the locked camera, undistort them, and fix the 70/20/10 split in a committed file list.
3. Labelling (1.5 h): outline the box in every image with a labelling tool.
4. Model (1.5 h): fine-tune a pretrained segmentation model on Google Colab and evaluate on the test split.
5. Inference command (1 h): image in, mask overlay with width and height in mm out, handling "object not found" and "reference not found".
6. Accuracy check (1 h): measure 10 or more instances by hand with a ruler and compare with the system.

## What I plan to skip
Items 7 to 10 (speed target, breaking condition, refusal threshold, decision record) unless time is left. Anything I do not reach will be listed in the Definition of Done.

## Decisions so far
- Reference object: a rigid flat card, raised to the same level as the top of the box so both lie in the same plane.
- Ground truth: a ruler, not a calliper, so my accuracy numbers will be less precise.
- Model: not a YOLO or Roboflow model. The exact choice will be recorded here once I decide.
