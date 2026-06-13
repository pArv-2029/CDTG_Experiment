# CDTG_Experiment
A confidence dynamics based hallucination and error prediction framework for reasoning language models.

## Idea

Instead of using a fixed confidence threshold, CDTG monitors:

- Confidence (Ct)
- Velocity (Vt)
- Curvature (Kt)

to detect upcoming reasoning failures before they occur.

## Experiment

Model:
- DeepSeek-R1-Distill-Qwen-1.5B

Dataset:
- GSM8K

Baselines:
- Absolute Threshold
- MUR (Momentum)

Proposed:
- CDTG (Curvature Gate)

## Metrics

- Advance Warning
- Firing Rate
- False Positive Rate

## Run

```bash
pip install -r requirements.txt
