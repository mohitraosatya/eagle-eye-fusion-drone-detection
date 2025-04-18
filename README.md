# Project Eagle‑Eye Fusion 

A proof‑of‑concept implementation that extends  
**“Multi‑Sensor Fusion vs. Single‑Instrument Approaches for Drone Detection and Classification”**  
with a lightweight, nature‑inspired attention mechanism.

> **Key idea** – mimic a raptor’s foveated vision:  
> at every time‑step, weight each sensor stream by its instantaneous signal energy (softmax).  
> The model “looks harder” where information is richest, improving robustness to noisy channels.

## Quick‑start (Colab)

```bash
git clone https://github.com/<your‑org>/eagle-eye-fusion-drone-detection.git
cd eagle-eye-fusion-drone-detection
pip install -r requirements.txt
python demo_eagle_fusion.py      # synthetic 3‑sensor example

```

**Author: Satya Mohit Rao Kamkanampati
**Email: saka4331@colorado.edu
**Linkedin: https://www.linkedin.com/in/mohitraosatya/
