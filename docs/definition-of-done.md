# Definition of Done

Written before starting. Each box is ticked at the end with evidence beside it.

- [ ] Camera calibrated with 20 or more checkerboard images. Reprojection error reported, with the image count.
  Evidence:
- [ ] Test split file list committed before any training started.
  Evidence (commit link):
- [ ] 70 or more images of the jewelry box taken with the calibrated camera, undistorted, and labelled with masks.
  Evidence:
- [ ] Segmentation model trained or fine-tuned on my own images (not YOLO, not Roboflow). Test metrics reported (IoU, mAP, precision, recall).
  Evidence:
- [ ] One command runs on a new image and prints width and height in mm, and handles "object not found" and "reference not found".
  Evidence:
- [ ] Accuracy table for 10 or more instances measured with a ruler, with mean, median and worst-case error. Raw outputs saved.
  Evidence:
- [ ] Measurement target (MO-1) met, or missed with the reason written down.
  Evidence:
- [ ] Random seed, library versions and training config pinned. Weights linked with SHA-256 hash in the README.
  Evidence:
- [ ] Loom recording of 5 minutes or less, with the four questions answered.
  Evidence:
- [ ] Everything I did not finish is listed here, with the reason.
  Not finished:
