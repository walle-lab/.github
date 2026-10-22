<p align="center">
  <img src="https://raw.githubusercontent.com/DigitalMechanobiologyLab/.github/main/profile/assets/lab-banner.svg" alt="Digital Mechanobiology Lab · University of Calgary · Radiology" width="720">
</p>

<p align="center"><strong>Medical imaging → quantitative structure → mechanics → tissue adaptation</strong></p>
<p align="center">
  <a href="https://digitalmechanobiology.ca">Lab website</a> ·
  <a href="https://digitalmechanobiology.ca/#research">Research</a> ·
  <a href="https://digitalmechanobiology.ca/#publications">Publications</a> ·
  <a href="https://github.com/orgs/DigitalMechanobiologyLab/repositories">All repositories</a>
</p>

We combine medical imaging, computational modelling, and machine learning to study how mechanical forces shape tissue behaviour. Our research spans cancer–bone mechanobiology, spinal alignment, and bone adaptation.

This is the software home of the **Digital Mechanobiology Lab**, led by **Matthias Walle** in the Department of Radiology at the **University of Calgary**.

## Where to start

- **Prefer a visual interface?** Start with the [Bone Imaging Toolbox for 3D Slicer](https://github.com/DigitalMechanobiologyLab/SlicerBoneImagingToolbox).
- **Working with repeated HR-pQCT scans?** Start with [TimelapsedHRpQCT](https://github.com/DigitalMechanobiologyLab/TimelapsedHRpQCT).
- **Building a Python workflow?** Choose a focused package below; each repository documents its own installation, inputs, and outputs.

## HR-pQCT

Longitudinal imaging, image quality, registration, and segmentation. [Browse HR-pQCT repositories →](https://github.com/orgs/DigitalMechanobiologyLab/repositories?q=topic%3Ahrpqct)

| Repository | What it does |
| --- | --- |
| [TimelapsedHRpQCT](https://github.com/DigitalMechanobiologyLab/TimelapsedHRpQCT) | Registration and longitudinal analysis of bone formation and resorption. |
| [MotionScoreHRpQCT](https://github.com/DigitalMechanobiologyLab/MotionScoreHRpQCT) | Deep-learning-supported motion grading and image quality assessment. |
| [MultistackRegistration](https://github.com/DigitalMechanobiologyLab/MultistackRegistration) | Correction of stack-shift artefacts in multistack acquisitions. |
| [hrpqct-geodesic-contour](https://github.com/DigitalMechanobiologyLab/hrpqct-geodesic-contour) | Geodesic active-contour segmentation of fractured distal radii. |

## CT analysis and segmentation

Tools for quantitative CT workflows. [Browse CT repositories →](https://github.com/orgs/DigitalMechanobiologyLab/repositories?q=topic%3Act-analysis)

| Repository | What it does |
| --- | --- |
| [spine-segment](https://github.com/DigitalMechanobiologyLab/spine-segment) | Vertebral CT localisation, identification, and segmentation. |
| [nnUNetManager](https://github.com/DigitalMechanobiologyLab/nnUNetManager) | Management and execution of configurable nnU-Net segmentation workflows. |
| [bone-contouring](https://github.com/DigitalMechanobiologyLab/bone-contouring) | Bone contours and compartment masks, including optional HR-pQCT U-Net segmentation. |

## Bone structure and microarchitecture

Measurements from bone images and segmentations. [Browse microarchitecture repositories →](https://github.com/orgs/DigitalMechanobiologyLab/repositories?q=topic%3Abone-microarchitecture)

| Repository | What it does |
| --- | --- |
| [bone-microarchitecture](https://github.com/DigitalMechanobiologyLab/bone-microarchitecture) | Microarchitecture measurements from masks and calibrated image arrays. |
| [bone-plate-rod-thinning](https://github.com/DigitalMechanobiologyLab/bone-plate-rod-thinning) | Topology-preserving trabecular plate/rod thinning and morphometry. |
| [voidspace](https://github.com/DigitalMechanobiologyLab/voidspace) | Spacing-aware voidspace analysis for HR-pQCT segmentations. |

## Modelling and mechanobiology

From image-derived mechanics to bone adaptation. [Browse modelling repositories →](https://github.com/orgs/DigitalMechanobiologyLab/repositories?q=topic%3Acomputational-modelling)

| Repository | What it does |
| --- | --- |
| [parosol-py](https://github.com/DigitalMechanobiologyLab/parosol-py) | Python interface and runtime wrapper for the ParOSol micro finite element solver. |
| [BoneMechanoregulation](https://github.com/DigitalMechanobiologyLab/BoneMechanoregulation) | Downstream analysis linking TimelapsedHRpQCT remodelling outputs with mechanical stimuli. |

## Imaging tools and shared infrastructure

Reusable interfaces, file formats, and workflow conventions. [Browse imaging tools →](https://github.com/orgs/DigitalMechanobiologyLab/repositories?q=topic%3Aimaging-tools)

| Repository | What it does |
| --- | --- |
| [SlicerBoneImagingToolbox](https://github.com/DigitalMechanobiologyLab/SlicerBoneImagingToolbox) | A 3D Slicer interface connecting bone-imaging and analysis packages. |
| [aimio-py](https://github.com/DigitalMechanobiologyLab/aimio-py) | Python bindings for Scanco image I/O, including AIM and related formats. |
| [ScancoAIMreader](https://github.com/DigitalMechanobiologyLab/ScancoAIMreader) | ITK ScancoIO-based AIM reading, conversion, and alignment. |
| [bone-imaging-derivatives](https://github.com/DigitalMechanobiologyLab/bone-imaging-derivatives) | Shared models and helpers for interoperable bone-imaging derivative manifests. |
| [BoneQuantMRI](https://github.com/DigitalMechanobiologyLab/BoneQuantMRI) | MATLAB application for ROI-based bone MRI analysis and calibration. |

## Using and contributing

Check the individual repository for its documentation, licence, release status, and citation guidance. To report a problem or discuss a contribution, open an issue in the relevant repository. Please cite the associated software and methods when using them in research.

## Earlier projects

These repositories are archived and retained for reproducibility: [TimelapsedHRpQCTv1](https://github.com/DigitalMechanobiologyLab/TimelapsedHRpQCTv1), [MotionScoreCNN](https://github.com/DigitalMechanobiologyLab/MotionScoreCNN), [SlicerMotionScoreHRpQCT](https://github.com/DigitalMechanobiologyLab/SlicerMotionScoreHRpQCT), [ImageGuidedStrain](https://github.com/DigitalMechanobiologyLab/ImageGuidedStrain), and [ScatterRad](https://github.com/DigitalMechanobiologyLab/ScatterRad). Start with the current packages above for new work.
