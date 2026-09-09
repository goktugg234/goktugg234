## Göktuğ Gümüş

**AI & Computer Vision engineer.** I train deep-learning vision models and put
them into production on edge hardware — currently vehicle detection, traffic
scene analysis and licence plate recognition inside an intelligent transportation
platform, plus the LLM assistant that lets operators ask it questions in plain
language.

Ankara, Turkey · [LinkedIn](https://www.linkedin.com/in/goktuggumuss/) ·
[goktugg.gumuss@gmail.com](mailto:goktugg.gumuss@gmail.com)

---

### What I build

**[llm-traffic-assistant](https://github.com/GoktuGumus/llm-traffic-assistant)**
— a self-hosted RAG and tool-calling service. Ten JSON-schema tools whose schemas
are generated from their function signatures, multi-turn sessions, SSE streaming,
and a grounding checker that traces every number in an answer back to a tool
result before returning it. Scored by a held-out evaluation set that includes
questions it must **refuse**.

**[traffic-vision-pipeline](https://github.com/GoktuGumus/traffic-vision-pipeline)**
— detect, track and count vehicles, with the frame budget measured stage by
stage. Benchmarked on an RTX 5090: at batch 1 the pipeline is bound by fixed
per-call overhead rather than by the model, and batching 16 frames is worth
2.6–5.6×. The counting logic is verified against scenes whose answer is known
before the pipeline runs.

**[cat-irt-engine](https://github.com/GoktuGumus/cat-irt-engine)** — a Rasch
adaptive testing engine. Reaches the accuracy of a 45-item fixed exam in 27
items, and states the information bound that makes anything shorter impossible.
No dependencies.

**[autonomous-vtol-uav](https://github.com/GoktuGumus/autonomous-vtol-uav)** —
onboard detection, tracking and follow control for a VTOL UAV. First place at the
16th R&D Project Market.

---

### Tools

`Python` `C#` `C++` · `PyTorch` `TensorFlow` `YOLOv8` `Detectron2` `OpenCV` ·
`llama.cpp` `Qdrant` `RAG` `function calling` · `FastAPI` `Flask` `.NET` ·
`Jetson` `STM32` `ROS` `PX4` · `PostgreSQL` `Docker` `Git`

---

<sub>Every repository above documents what it measured, and what it did not. If a
number appears in a README here, there is a script in the same repository that
reproduces it.</sub>
