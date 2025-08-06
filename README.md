# Just-barely-started-gpt-oss-20b
Low spec startup record
# 🧠 Local 20B LLM Boot — On the Edge of Capacity

This repository documents a rare, high-risk attempt to locally run a **20B parameter language model (gpt-oss:20b)**  
on a mid-spec **Panasonic Let's Note** laptop — fully offline, with almost no free RAM or SSD space.

---

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
![Wi-Fi off](img/wifioff.png)

### 💽 SSD Nearly Full  
![SSD usage](img/girigiriSSD.png)

### 🧠 RAM Near Capacity  
![Memory usage](img/memorigirigiri.png)

### 🖥 System Specs  
![System info](img/spec.png)

---

## 🚨 Execution Attempt Log

