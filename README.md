# AssemblyVision — Manual Assembly Activity Detector

AssemblyVision is a polished two-page React prototype for exploring computer-vision-assisted manual assembly monitoring.

**Live Demo:**  
https://assemblyvision-prototype.common-dugong.workers.dev/

## Pages

### 1. Assembly Monitor

A synthetic engine assembly workstation featuring:

- Simulated camera feed
- Object-detection bounding boxes
- Current assembly activity and confidence
- Five-step assembly progress
- Completed and in-progress states
- Interactive activity simulation:
  1. Component detection
  2. Tool interaction
  3. Activity completion
- Simulated PLC event:
  `ACTIVITY_03_COMPLETE → Production / PLC System`

### 2. CV Evaluation

Synthetic comparison of:

- Object Detection
- Detection + Tracking
- Pose Estimation
- Action Recognition

Evaluation metrics include:

- Accuracy
- Inference time
- Robustness
- Training-data requirement

Users can change lighting, camera angle, and occlusion conditions to update the synthetic benchmark results.

## Technology

- React
- TypeScript
- Vinext
- Tailwind CSS
- Lucide icons
- Cloudflare Workers
- Wrangler
