# 🧠 Local 20B LLM Boot — On the Edge of Capacity

This repository documents a rare, high-risk attempt to locally run a **20B parameter language model (gpt-oss:20b)**  
on a mid-spec **Panasonic Let's Note** laptop — fully offline, with almost no free RAM or SSD space.

---
---

## 🎥 Boot Attempt Recording

This short video captures the moment I attempted to run `gpt-oss:20b`  
under extreme conditions:  
- 92% RAM usage  
- Less than 5GB SSD free  
- No Wi-Fi  
- i5 CPU with integrated GPU

<video src="girigiriOSSkido.mp4" controls width="600">
  Your browser does not support the video tag.
</video>

🔗 [Click here to download or view the video directly](./girigiriOSSkido.mp4)

## ⚙️ Hardware Specs

| Component     | Details                        |
|---------------|--------------------------------|
| CPU           | Intel(R) Core i5-10310U @ 1.70GHz |
| RAM           | 16.0 GB DDR4 (92% used at runtime) |
| GPU           | Integrated Intel UHD (128MB shared) |
| Storage       | 236GB SSD (4.89GB free at runtime) |
| OS            | Windows 11 Pro |
| Network       | **Wi-Fi OFF (Air-gapped)** |
| LLM Framework | Ollama (v0.1.30) |
| Model         | `gpt-oss:20b` |

---

## 🔐 Offline Proof

This was a **true local execution**.  
The system was completely disconnected from the internet at the time of model launch:

### 🔒 No Wi-Fi  
![Wi-Fi off](wifioff.png)

### 💽 SSD Nearly Full  
![SSD usage](girigiriSSD.png)

### 🧠 RAM Near Capacity  
![Memory usage](memorigirigiri.png)

### 🖥 System Specs  
![System info](spec.png)

---

## 🚨 Execution Attempt Log

```powershell
ollama run gpt-oss:20b

📜 Why This Matters
In a world where most LLMs depend on the cloud,
this attempt proves that a laptop with modest specs, limited storage, and no network
can still fight to host a massive model like a 20B LLM — locally.

It’s not about winning. It’s about proving it can be tried.
It’s about reminding ourselves:

"You don’t need perfect conditions to try impossible things."

✍️ Notes
Model loading partially succeeded

RAM limit likely triggered runtime crash (exit status 2)

Execution was monitored with no other major processes running

This was done intentionally without freeing space, to prove the threshold

🧠 Authored by
KGNINJA
https://x.com/FuwaCocoOwnerKG

“I chose a machine not because it was strong,
but because it would make the story stronger.”

🏷 Tags
#OfflineLLM #20Bboot #LimitBreak #KGNINJA
