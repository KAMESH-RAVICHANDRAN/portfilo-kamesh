# PC BUILD GUIDE

## Gaming + AI/ML Optimised Build — GPU-Later Strategy

**AMD Ryzen 5 5600G (Now) → Add RTX 3060 12GB (Later)**

> Phase 1 Budget (No GPU): Rs. 35,000 – 42,000
> Phase 2 Budget (With GPU): Rs. 57,000 – 70,000

---

## Why This GPU-Later Strategy?

The **Ryzen 5 5600 has NO integrated graphics** — it cannot run without a GPU. So we swap to the **Ryzen 5 5600G** which has Radeon Vega 7 iGPU built-in. Use the PC right away, save up, then drop in the RTX 3060 12GB later with zero other changes needed.

| Phase 1 — Now (No GPU)                           | Phase 2 — Later (With GPU)           |
| ------------------------------------------------ | ------------------------------------ |
| Ryzen 5 5600G iGPU handles display output        | RTX 3060 12GB slots into PCIe slot   |
| Light gaming, web, Office, YouTube — works great | 1080p Ultra / 1440p High gaming      |
| Python, Jupyter, PyTorch CPU-mode for AI/ML      | Full CUDA AI/ML — runs 7B–13B models |
| Total cost: Rs. 35,000 – 42,000                  | Add Rs. 22,000–28,000 for GPU        |
| B550M + 650W PSU already GPU-ready               | No other parts need to change        |

---

## Complete Parts List with Prices & Links

### CPU — AMD Ryzen 5 5600G *(Changed from 5600)*

![AMD Ryzen 5 5600G](https://m.media-amazon.com/images/I/61iFpOBqKVL._AC_SL1500_.jpg)

|                   |                                                                                                                                                                       |
| ----------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Spec**          | 6 Cores / 12 Threads | 3.9 GHz – 4.4 GHz | AM4 Socket | Radeon Vega 7 iGPU | Wraith Stealth Cooler                                                                    |
| **Why**           | Has built-in Radeon Vega 7 graphics — PC works without a dedicated GPU. Same 6C/12T performance as 5600. When you add RTX 3060 later, iGPU automatically steps aside. |
| **Price (India)** | Rs. 13,000 – 16,000                                                                                                                                                   |
| **Amazon**        | [Click to buy on Amazon.in](https://www.amazon.in/s?k=AMD+Ryzen+5+5600G)                                                                                              |
| **Flipkart**      | [Click to buy on Flipkart.com](https://www.flipkart.com/q/amd-ryzen-5-5600g)                                                                                          |

---

### GPU — NVIDIA RTX 3060 12GB *(Skip for Now — Buy Later)*

![NVIDIA RTX 3060 12GB](https://m.media-amazon.com/images/I/71u4d2GCRBL._AC_SL1500_.jpg)

|                   |                                                                                                                                                                                                           |
| ----------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Spec**          | 12GB GDDR6 | 192-bit | 3584 CUDA Cores | PCIe 4.0 | HDMI + 3x DisplayPort                                                                                                                                 |
| **Why**           | CUDA support is essential for AI/ML (PyTorch, TensorFlow). 12GB VRAM runs 7B–13B AI models. Also excellent for 1080p gaming. B550M + 650W PSU are already ready for it — just plug in when budget allows. |
| **Price (India)** | Rs. 22,000 – 28,000 *(new/used varies)*                                                                                                                                                                   |
| **Amazon**        | [Click to buy on Amazon.in](https://www.amazon.in/s?k=RTX+3060+12GB)                                                                                                                                      |
| **Flipkart**      | [Click to buy on Flipkart.com](https://www.flipkart.com/inno3d-nvidia-geforce-rtx-3060-twin-x2-12-gb-gddr6-graphics-card/p/itmae272b21d60db)                                                              |

> **Phase 1:** Skip this. The 5600G iGPU handles display.
> **Phase 2:** When budget is ready, slot this in — no other changes needed.

---

### RAM — 32GB DDR4 3200MHz (2x16GB)

|                   |                                                                                                             |
| ----------------- | ----------------------------------------------------------------------------------------------------------- |
| **Spec**          | Dual Channel | CL16 | Corsair Vengeance LPX or Kingston Fury Beast                                          |
| **Why**           | 32GB is the minimum for AI/ML — models offload layers to RAM. Also handles gaming + multitasking perfectly. |
| **Price (India)** | Rs. 5,500 – 7,000                                                                                           |
| **Amazon**        | [Click to buy on Amazon.in](https://www.amazon.in/Corsair-Vengeance-PC4-25600-Desktop-Memory/dp/B07RW6Z692) |
| **Flipkart**      | [Click to buy on Flipkart.com](https://www.flipkart.com/q/32gb-ddr4-3200mhz-desktop-ram)                    |

---

### SSD — 1TB NVMe

|                   |                                                                                                                  |
| ----------------- | ---------------------------------------------------------------------------------------------------------------- |
| **Spec**          | M.2 PCIe Gen3/Gen4 | 3000–7000 MB/s Read | WD Blue SN570 / Crucial P310                                          |
| **Why**           | AI models are 4–40GB each. 1TB gives room for OS + games + multiple AI model files without running out of space. |
| **Price (India)** | Rs. 5,500 – 8,000                                                                                                |
| **Amazon**        | [Click to buy on Amazon.in](https://www.amazon.in/s?k=1TB+NVMe+SSD+M.2)                                          |
| **Flipkart**      | [Click to buy on Flipkart.com](https://www.flipkart.com/internal-ssd/1-tb~capacity/pr?sid=6bo,jdy,dus,grs)       |

---

### Motherboard — Gigabyte B550M DS3H AC R2

<img src="https://m.media-amazon.com/images/I/61ek0c7+-3L._SX679_.jpg" alt="Gigabyte B550M DS3H AC R2" width="320"/>

|                   |                                                                                                                                                                                        |
| ----------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Spec**          | AM4 | PCIe 4.0 | Dual M.2 | Wi-Fi 5 | DDR4 up to 4733MHz OC | USB 3.2 Gen1                                                                                                             |
| **Why**           | Rock-solid B550 platform for Ryzen 5600G. PCIe 4.0 M.2 slot gives SSD full speed. Built-in Wi-Fi is handy. PCIe x16 slot is ready and waiting for the RTX 3060 whenever budget allows. |
| **Price (India)** | Rs. 12,000 – 14,500                                                                                                                                                                    |
| **Amazon**        | [Click to buy on Amazon.in](https://www.amazon.in/GIGABYTE-B550M-DS3H-AC-Motherboard/dp/B0F2H4JLJM)                                                                                    |
| **Flipkart**      | [Click to buy on Flipkart.com](https://www.flipkart.com/gigabyte-b550m-ds3h-ac-motherboard/p/itm2e0ce03c63f34)                                                                         |

---

### PSU — Corsair CX650 / MSI MAG A650BN (650W)

|                   |                                                                                                                                                                            |
| ----------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Spec**          | 650W | 80 Plus Bronze | Active PFC | 120mm Fan | 5-Year Warranty                                                                                                           |
| **Why**           | RTX 3060 needs proper headroom when added later. Buying 650W now means zero PSU change needed in Phase 2. MSI MAG A650BN has 5yr warranty + DC-DC for stable power rails.  |
| **Price (India)** | Rs. 4,500 – 6,000                                                                                                                                                          |
| **Amazon**        | [Click to buy on Amazon.in](https://www.amazon.in/MSI-A650BN-Gaming-Power-Supply/dp/B09GW3QZLJ)                                                                            |
| **Flipkart**      | [Click to buy on Flipkart.com](https://www.flipkart.com/antec-csk-650w-80-bronze-certified-psu-continuous-power-120mm-silent-cooling-fan-650-watts-psu/p/itmcf2f48e85a9ad) |

---

### Cabinet — Airflow RGB Mid-Tower

|                   |                                                                                                                                        |
| ----------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| **Spec**          | Mid Tower | Tempered Glass | Pre-installed RGB Fans | ATX/mATX Support                                                                 |
| **Why**           | Good airflow keeps system cool. Spacious enough to fit RTX 3060 (up to 300mm GPU length) when added later. Tempered glass looks great. |
| **Price (India)** | Rs. 3,000 – 4,500                                                                                                                      |
| **Amazon**        | [Click to buy on Amazon.in](https://www.amazon.in/s?k=Ant+Esports+airflow+mid+tower+RGB)                                               |
| **Flipkart**      | [Click to buy on Flipkart.com](https://www.flipkart.com/q/ant-esports-mid-tower-cabinet-rgb)                                           |

---

## Budget Summary

### Phase 1 — Buy Now (No GPU)

| Component                      |   Approx. Price (India) |
| ------------------------------ | ----------------------: |
| CPU — AMD Ryzen 5 5600G        |     Rs. 13,000 – 16,000 |
| GPU — Skip for now             |                   Rs. 0 |
| RAM — 32GB DDR4 3200MHz        |       Rs. 5,500 – 7,000 |
| SSD — 1TB NVMe                 |       Rs. 5,500 – 8,000 |
| Motherboard — B550M DS3H AC R2 |     Rs. 12,000 – 14,500 |
| PSU — 650W 80+ Bronze          |       Rs. 4,500 – 6,000 |
| Cabinet — Airflow RGB          |       Rs. 3,000 – 4,500 |
| **TOTAL Phase 1**              | **Rs. 43,500 – 56,000** |

### Phase 2 — Add GPU Later

| Component               |   Approx. Price (India) |
| ----------------------- | ----------------------: |
| Everything from Phase 1 |     Rs. 43,500 – 56,000 |
| GPU — RTX 3060 12GB     |     Rs. 22,000 – 28,000 |
| **TOTAL Phase 2**       | **Rs. 65,500 – 84,000** |

> **Note:** GPU price depends heavily on market conditions. Buying RTX 3060 12GB during a sale or in good used condition can bring Phase 2 total under Rs. 65,000. Always compare Amazon vs Flipkart prices on the day of purchase.
