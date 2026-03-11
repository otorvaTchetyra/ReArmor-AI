# ReArmor AI — Powered Stroke Rehabilitation Trainer

> Restoring neural connections between the brain and paretic hand through intelligent, adaptive electrostimulation.

---

## Overview

**ReArmor** is a multifunctional rehabilitation device designed for post-stroke patients recovering upper limb motor function. The core goal is to rebuild neural pathways between the brain and the affected hand with minimal dependency on a therapist or specialist — empowering patients to train independently, consistently, and effectively.

---

## The Problem

After a stroke, the motor pathway between the brain and the hand is damaged or disrupted. Traditional rehabilitation requires frequent specialist-supervised sessions, which are expensive, logistically demanding, and often insufficient in volume. Without repetitive, high-frequency practice, neural recovery stalls.

---

## How It Works

ReArmor combines three core components into a closed-loop rehabilitation system:

### 1. Vision Module (Camera)
A camera continuously captures the patient's hand and the target object in the environment. Using computer vision and machine learning, it evaluates:
- **Distance** from the hand to the object
- **Object shape and geometry** — determining the optimal grasp type (precision pinch, lateral grip, power grasp, etc.)

### 2. ML Inference Processor
An onboard processor runs real-time inference to:
- Classify the target object and select the appropriate grip pattern
- Estimate the required finger and wrist activation sequence
- Generate a stimulation profile matched to the intended movement

### 3. Electrical Stimulator (FES — Functional Electrical Stimulation)
The stimulator delivers precisely timed, multi-channel electrical pulses to the forearm and hand muscles. Stimulation parameters (intensity, timing, sequence) are dynamically adjusted by the ML model based on the current task.

---

## The Patient's Role

The patient is **actively engaged**, not passive:

1. **Focus** on the target object
2. **Initiate the movement intention** — consciously attempt to move the hand
3. The device detects the movement attempt and **co-activates the muscles in sync** with the patient's effort

This synchronized volitional + electrical activation is the key to neuroplasticity. The brain learns to re-associate intention with movement outcome.

---

## Key Features

| Feature | Description |
|---|---|
| **Adaptive FES** | Multi-channel stimulation profiles generated per task |
| **Grasp Classification** | ML model identifies object type and selects grip pattern |
| **Distance Estimation** | Real-time spatial awareness for stimulation scaling |
| **Volitional Sync** | Stimulation paired with patient's own motor intent |
| **Minimal Supervision Required** | Designed for home and clinic use without constant therapist input |
| **Session Logging** | Tracks progress over time for clinical review |

---

## Architecture
```
[Camera] → [Vision ML Model] → [Grasp & Distance Estimation]
                                         ↓
                            [Stimulation Profile Generator]
                                         ↓
                           [Multi-Channel FES Controller]
                                         ↓
                              [Patient's Hand Muscles]
```

---

## Clinical Rationale

ReArmor is grounded in the principles of **motor learning** and **Hebbian plasticity**:

> *"Neurons that fire together, wire together."*

By repeatedly pairing the patient's motor intention with electrically-evoked movement, the device reinforces the targeted neural circuits — the same mechanism underlying evidence-based approaches like EMG-triggered FES and robot-assisted therapy, but made accessible, portable, and autonomous.

---

## Target Users

- Post-stroke patients with partial or full upper limb paresis
- Neurological rehabilitation clinics
- Home rehabilitation programs
- Occupational therapists seeking adjunct tools

---

## Status

🚧 **In development** — hardware prototyping & ML model training in progress.

---

## Contributing

Contributions, clinical feedback, and collaboration proposals are welcome. Open an issue or reach out directly.

---

## License

MIT License — see `LICENSE` for details.
