# PC BUILD GUIDE

## Gaming + AI/ML Optimised Build — GPU-Later Strategy

### AMD Ryzen 5 5600G (Now) → Add RTX 3060 12GB (Later)

> **Phase 1 Budget (No GPU):** Rs. 43,500 – 56,000
> **Phase 2 Budget (With GPU):** Rs. 65,500 – 84,000

---

# Why This GPU-Later Strategy?

The **Ryzen 5 5600 has NO integrated graphics** — it cannot run without a GPU. The **Ryzen 5 5600G** includes built-in Radeon Vega graphics, allowing the PC to work immediately without a dedicated GPU. ([Notebookcheck][1])

| Phase 1 — Now (No GPU)                           | Phase 2 — Later (With GPU)           |
| ------------------------------------------------ | ------------------------------------ |
| Ryzen 5 5600G iGPU handles display output        | RTX 3060 12GB slots into PCIe slot   |
| Light gaming, web, Office, YouTube — works great | 1080p Ultra / 1440p High gaming      |
| Python, Jupyter, PyTorch CPU-mode for AI/ML      | Full CUDA AI/ML — runs 7B–13B models |
| Total cost: Rs. 43,500 – 56,000                  | Add Rs. 22,000–28,000 for GPU        |
| B550M + 650W PSU already GPU-ready               | No other parts need to change        |

---

# Complete Parts List with Prices & Links

## CPU — AMD Ryzen 5 5600G *(Changed from 5600)*

![AMD Ryzen 5 5600G](https://rukminim2.flixcart.com/image/1536/1536/krdtlzk0/processor/i/p/g/ryzen-5-5600g-amd-original-imag56jmgyktcrjk.jpeg?q=90)

|                    |                                                                                                               |
| ------------------ | ------------------------------------------------------------------------------------------------------------- |
| **Spec**           | 6 Cores / 12 Threads | 3.9 GHz – 4.4 GHz | AM4 Socket | Radeon Vega 7 iGPU                                    |
| **Why**            | Has built-in graphics so the PC works without a dedicated GPU. Excellent stop-gap CPU until RTX 3060 upgrade. |
| **Important Note** | The 5600G supports PCIe 3.0 instead of PCIe 4.0 because it's an APU design. ([TechSpot][2])                   |
| **Price (India)**  | Rs. 13,000 – 16,000                                                                                           |
| **Amazon**         | [Buy on Amazon India](https://www.amazon.in/s?k=AMD+Ryzen+5+5600G&utm_source=chatgpt.com)                     |
| **Flipkart**       | [Buy on Flipkart](https://www.flipkart.com/q/amd-ryzen-5-5600g?utm_source=chatgpt.com)                        |

---

## GPU — NVIDIA RTX 3060 12GB *(Buy Later)*

![NVIDIA RTX 3060 12GB](https://rukminim2.flixcart.com/image/1536/1536/l1whaq80/graphics-card/u/o/p/geforce-rtx-3060-twin-x2-inno-3d-original-imagdd66whzbcgf8.jpeg?q=90)

|                   |                                                                                                  |
| ----------------- | ------------------------------------------------------------------------------------------------ |
| **Spec**          | 12GB GDDR6 | 192-bit | CUDA Support | PCIe 4.0                                                   |
| **Why**           | Best value NVIDIA GPU for AI/ML. 12GB VRAM is enough for local 7B–13B LLMs and Stable Diffusion. |
| **Price (India)** | Rs. 22,000 – 28,000                                                                              |
| **Amazon**        | [Buy on Amazon India](https://www.amazon.in/s?k=RTX+3060+12GB&utm_source=chatgpt.com)            |
| **Flipkart**      | [Buy on Flipkart](https://www.flipkart.com/search?q=rtx+3060+12gb&utm_source=chatgpt.com)        |

> **Phase 1:** Skip this — the 5600G handles display output.
> **Phase 2:** Plug this into the PCIe slot and install drivers.

---

## RAM — 32GB DDR4 3200MHz (2×16GB)

![32GB DDR4 RAM](https://m.media-amazon.com/images/I/61wCOVcyvFL._SL1500_.jpg)

|                   |                                                                                                                                        |
| ----------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| **Spec**          | DDR4 3200MHz | Dual Channel | CL16                                                                                                     |
| **Why**           | AI workloads and modern multitasking benefit massively from 32GB RAM. APUs also benefit from faster dual-channel memory. ([Reddit][3]) |
| **Price (India)** | Rs. 5,500 – 7,000                                                                                                                      |
| **Amazon**        | [Buy on Amazon India](https://www.amazon.in/s?k=32GB+DDR4+3200MHz+RAM&utm_source=chatgpt.com)                                          |
| **Flipkart**      | [Buy on Flipkart](https://www.flipkart.com/q/32gb-ddr4-3200mhz-desktop-ram?utm_source=chatgpt.com)                                     |

---

## SSD — 1TB NVMe SSD

![1TB NVMe SSD](https://rukminim2.flixcart.com/image/1536/1536/xif0q/internal-hard-drive/m/f/r/wds100t3b0e-western-digital-original-imagtrfa8kzkfyqh.jpeg?q=90)

|                   |                                                                                                                            |
| ----------------- | -------------------------------------------------------------------------------------------------------------------------- |
| **Spec**          | NVMe M.2 SSD | 3000–7000 MB/s                                                                                              |
| **Why**           | Fast boot speeds, faster game loading, smoother AI dataset handling.                                                       |
| **Price (India)** | Rs. 5,500 – 8,000                                                                                                          |
| **Amazon**        | [Buy on Amazon India](https://www.amazon.in/s?k=1TB+NVMe+SSD+M.2&utm_source=chatgpt.com)                                   |
| **Flipkart**      | [Buy on Flipkart](https://www.flipkart.com/internal-ssd/1-tb~capacity/pr?sid=6bo%2Cjdy%2Cdus%2Cgrs&utm_source=chatgpt.com) |

---

## Motherboard — Gigabyte B550M DS3H AC R2

![Gigabyte B550M DS3H AC R2](https://m.media-amazon.com/images/I/61ek0c7+-3L._SX679_.jpg)

|                   |                                                                                                                          |
| ----------------- | ------------------------------------------------------------------------------------------------------------------------ |
| **Spec**          | B550 Chipset | Wi-Fi | Dual M.2 | PCIe x16                                                                               |
| **Why**           | Reliable AM4 motherboard with Wi-Fi and excellent upgrade path for RTX GPUs.                                             |
| **Price (India)** | Rs. 12,000 – 14,500                                                                                                      |
| **Amazon**        | [Buy on Amazon India](https://www.amazon.in/GIGABYTE-B550M-DS3H-AC-Motherboard/dp/B0F2H4JLJM?utm_source=chatgpt.com)     |
| **Flipkart**      | [Buy on Flipkart](https://www.flipkart.com/gigabyte-b550m-ds3h-ac-motherboard/p/itm2e0ce03c63f34?utm_source=chatgpt.com) |

---

## PSU — MSI MAG A650BN 650W

![MSI MAG A650BN](https://m.media-amazon.com/images/I/71pU8A2UE9L._SX679_.jpg)

|                   |                                                                                                                  |
| ----------------- | ---------------------------------------------------------------------------------------------------------------- |
| **Spec**          | 650W | 80+ Bronze | 5-Year Warranty                                                                              |
| **Why**           | Enough power headroom for RTX 3060 and future upgrades.                                                          |
| **Price (India)** | Rs. 4,500 – 6,000                                                                                                |
| **Amazon**        | [Buy on Amazon India](https://www.amazon.in/MSI-A650BN-Gaming-Power-Supply/dp/B09GW3QZLJ?utm_source=chatgpt.com) |
| **Flipkart**      | [Buy on Flipkart](https://www.flipkart.com/search?q=msi+mag+a650bn&utm_source=chatgpt.com)                       |

---

## Cabinet — Airflow RGB Mid-Tower

![Airflow RGB Cabinet](https://m.media-amazon.com/images/I/71ANhRN6eNL._SX679_.jpg)

|                   |                                                                                                           |
| ----------------- | --------------------------------------------------------------------------------------------------------- |
| **Spec**          | Tempered Glass | RGB Fans | ATX/mATX Support                                                              |
| **Why**           | Good airflow and enough GPU clearance for RTX 3060 upgrades later.                                        |
| **Price (India)** | Rs. 3,000 – 4,500                                                                                         |
| **Amazon**        | [Buy on Amazon India](https://www.amazon.in/s?k=Ant+Esports+airflow+mid+tower+RGB&utm_source=chatgpt.com) |
| **Flipkart**      | [Buy on Flipkart](https://www.flipkart.com/q/ant-esports-mid-tower-cabinet-rgb?utm_source=chatgpt.com)    |

---

# Budget Summary

## Phase 1 — Buy Now (No GPU)

| Component                 |           Approx. Price |
| ------------------------- | ----------------------: |
| Ryzen 5 5600G             |     Rs. 13,000 – 16,000 |
| 32GB DDR4 RAM             |       Rs. 5,500 – 7,000 |
| 1TB NVMe SSD              |       Rs. 5,500 – 8,000 |
| Gigabyte B550M DS3H AC R2 |     Rs. 12,000 – 14,500 |
| MSI MAG A650BN PSU        |       Rs. 4,500 – 6,000 |
| Airflow RGB Cabinet       |       Rs. 3,000 – 4,500 |
| **TOTAL**                 | **Rs. 43,500 – 56,000** |

---

## Phase 2 — Add RTX 3060 Later

| Component     |           Approx. Price |
| ------------- | ----------------------: |
| Phase 1 Build |     Rs. 43,500 – 56,000 |
| RTX 3060 12GB |     Rs. 22,000 – 28,000 |
| **TOTAL**     | **Rs. 65,500 – 84,000** |

---

# Smart Buying Tips

* Buy **5600G**, NOT 5600, if you don't have a GPU.
* Always use **dual-channel RAM** for best iGPU performance. ([Reddit][3])
* Prefer **B550 over A520** for better SSD and GPU upgrade support.
* For AI/ML, NVIDIA CUDA support is the main reason for choosing RTX 3060.
* Record unboxing videos for CPU and motherboard purchases.
* Compare Amazon vs Flipkart pricing before ordering.
* Used RTX 3060 cards from trusted sellers can save significant money.

---

# What This PC Can Handle

## Phase 1 — Ryzen 5 5600G Only

| Category                  | Capability                      |
| ------------------------- | ------------------------------- |
| Web / Office / Coding     | Excellent                       |
| YouTube / Streaming       | Excellent                       |
| Valorant / GTA V          | Playable at low-medium settings |
| Python / Jupyter / Pandas | Smooth                          |
| Heavy AI / CUDA Workloads | Not possible yet                |

---

## Phase 2 — RTX 3060 Added

| Category          | Capability                |
| ----------------- | ------------------------- |
| AAA Gaming        | 1080p Ultra / 1440p High  |
| AI / ML           | Local LLMs, CUDA, PyTorch |
| Stable Diffusion  | Excellent                 |
| Blender Rendering | CUDA Accelerated          |
| OBS Streaming     | NVENC Hardware Encoding   |
| Video Editing     | 1080p/4K light editing    |

---

# Community Notes

Many PC builders still recommend the Ryzen 5 5600G in 2026 specifically for “GPU later” builds because it allows a fully working PC immediately without needing a dedicated graphics card. ([Reddit][4])

The main compromise is reduced PCIe support and smaller cache versus the regular Ryzen 5 5600/5600X, but the convenience of integrated graphics makes it an excellent temporary solution. ([Reddit][5])

---

*Prices are approximate as of May 2026. Always compare Amazon and Flipkart prices before purchasing.*

[1]: https://www.notebookcheck.net/AMD-Ryzen-5-5600G-Processor-Benchmarks-and-Specs.598095.0.html?utm_source=chatgpt.com "AMD Ryzen 5 5600G Processor - Benchmarks and Specs - NotebookCheck.net Tech"
[2]: https://www.techspot.com/specs/processors/234936-amd-ryzen-5-5600g.html?utm_source=chatgpt.com "AMD Ryzen 5 5600G Specs | TechSpot"
[3]: https://www.reddit.com/r/buildapc/comments/xdm65l?utm_source=chatgpt.com "Why is my ryzen 5 5600g so slow compared to others"
[4]: https://www.reddit.com/r/ETechBuy/comments/1s9dvw1/is_the_ryzen_5_5600g_still_worth_it_in_2026/?utm_source=chatgpt.com "Is the Ryzen 5 5600G still worth it in 2026?"
[5]: https://www.reddit.com/r/buildapc/comments/wmmmmr?utm_source=chatgpt.com "AMD Ryzen 5 5600G ( is it really slower?) vs AMD Ryzen 5 5600."
