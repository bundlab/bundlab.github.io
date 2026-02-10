---
layout: post
title: "AI That Cares: Building an Emotion and Fatigue Detector"
date: 2026-02-10 10:00:00 +0100
categories: ai-ml computer-vision
---

In my journey as a developer in Maiduguri, I’ve always been fascinated by how machines can understand human states. My project, **emotion-fatigue-detector_app**, was born from a simple question: *Can AI prevent accidents by knowing when we are tired?*

### The Core Technology
To build this, I focused on three main technical pillars:
1. **Facial Landmark Detection:** Identifying key points around the eyes and mouth.
2. **Eye Aspect Ratio (EAR):** A mathematical formula to detect if eyes are closing for too long (indicating drowsiness).
3. **CNN Models:** Using Convolutional Neural Networks to classify emotions like stress or exhaustion.

### Why This Matters
Whether it's a long-distance driver or a software engineer working late on Ubuntu 24.04, fatigue is a silent risk. By integrating this into mobile and desktop apps, we can create a "safety net" that alerts users before mistakes happen.

### Current Progress
Right now, the app can successfully:
* Detect eye closure patterns in real-time.
* Differentiate between a simple blink and a fatigue-related "micro-sleep."
* Categorize 5 basic emotional states.

Check out the code here: [emotion-fatigue-detector_app](https://github.com/bundlab/emotion-fatigue-detector_app)

**What’s next?** I’m working on optimizing the frame rate for lower-end mobile devices to ensure this safety tool is accessible to everyone.

🚀 *More technical deep-dives coming soon!*