# Daniil Tchetyrkin (Tessaridis)
> **Developer of ReArmor AI** | Post-stroke Neuro-rehabilitation | Former Pro Hockey Player 🏒 | Amateur Racing Driver 🏎️

![Neuroscience](https://img.shields.io)
![AI/ML](https://img.shields.io)
![Status](https://img.shields.io)

---

## 🦾 Project: ReArmor — AI-Powered Stroke Rehabilitation Trainer

**ReArmor** is an intelligent, closed-loop rehabilitation system designed for post-stroke patients. It focuses on rebuilding neural pathways through **intelligent, adaptive electrostimulation (FES)**.

### 🧠 Clinical Rationale
The project is grounded in the principles of **Hebbian plasticity**:
> *"Neurons that fire together, wire together."*
By precisely synchronizing a patient's volitional movement intent with electrically-evoked muscle activation, the device reinforces targeted neural circuits, fostering neuroplasticity.

---

### 🛠 How It Works
The system operates as a real-time, task-oriented rehabilitation loop:

1. **Vision Module:** Captures the environment to evaluate object shape, geometry, and distance.
2. **ML Inference:** Onboard processor classifies the target and selects the optimal grasp pattern (precision pinch, power grasp, etc.).
3. **FES Controller:** Delivers multi-channel pulses to forearm muscles, dynamically adjusted based on the current task and patient effort.


| Feature | Description |
| :--- | :--- |
| **Adaptive FES** | Task-specific stimulation profiles generated in real-time |
| **Grasp Classification** | ML-driven object identification for grip selection |
| **Volitional Sync** | Stimulation paired with the patient's own motor intent |
| **Minimal Supervision** | Designed for independent use at home or in clinics |

---

### 🏗 System Architecture
```mermaid
graph LR
    A[Camera] --> B[Vision ML Model]
    B --> C[Grasp & Distance Estimation]
    C --> D[Stimulation Profile Generator]
    D --> E[Multi-Channel FES Controller]
    E --> F[Patient's Hand Muscles]
### 🤝 Collaboration & Contacts
The project is currently in the active prototyping stage. I am open to clinical feedback, research collaboration, and partnerships in the fields of neuro-rehabilitation and AI.

    Email: defender.0599@gmail.com
    Location: UTC-12:00
