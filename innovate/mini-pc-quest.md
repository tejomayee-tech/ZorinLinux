It's great to compare these specific models, as they represent different iterations and feature sets within Minisforum's lineup that are highly relevant for AI tasks.

Based on the latest information from Minisforum's official website and detailed reviews, here's a breakdown:

* **Minisforum UM790 Pro:** Uses the Ryzen 9 7940HS, which was a flagship in the 7040 series, featuring the Radeon 780M. It's a proven performer.
* **Minisforum AI X1 (Ryzen 7 260):** This model (often simply referred to as AI X1 with the 260 CPU) is a direct competitor to the UM790 Pro in terms of iGPU performance (Radeon 780M) but distinguishes itself with the OCuLink port and confirmed 100W USB-C PD input. The "Ryzen 7 260" is effectively a re-badged/tweaked version of a Ryzen 8040-series chip like the 8845HS, offering similar CPU/iGPU performance to the 7940HS.
* **Minisforum AI X1-US with AMD Ryzen™ 7 255:** This is another variant of the AI X1 line. Minisforum's product pages explicitly list the Ryzen 7 255 alongside the 260 for the AI X1. The key difference appears to be a slightly lower max boost clock for the CPU and a slightly lower TDP, but it still utilizes the same Radeon 780M iGPU and offers similar overall TOPS. Some sources suggest the 255 might be a binning of the same silicon as the 260/8845HS with minor adjustments.

Here's the comparison table:

### Minisforum Mini PC Comparison: UM790 Pro vs. AI X1 (Ryzen 7 260) vs. AI X1-US (Ryzen 7 255)

| Feature             | Minisforum UM790 Pro                                       | Minisforum AI X1 (Ryzen™ 7 260)                                            | Minisforum AI X1-US (Ryzen™ 7 255)                                         |
| :------------------ | :--------------------------------------------------------- | :------------------------------------------------------------------------- | :------------------------------------------------------------------------- |
| **Processor** | AMD Ryzen™ 9 7940HS                                        | AMD Ryzen™ 7 260                                                           | AMD Ryzen™ 7 255                                                           |
| **Cores/Threads** | 8 Cores / 16 Threads                                       | 8 Cores / 16 Threads                                                       | 8 Cores / 16 Threads                                                       |
| **Max. Boost Clock**| Up to 5.2 GHz                                              | Up to 5.1 GHz                                                              | Up to 5.1 GHz (some sources state 4.9 GHz)                                 |
| **Integrated GPU** | AMD Radeon™ 780M (2800MHz)                                 | AMD Radeon™ 780M (2700MHz)                                                 | AMD Radeon™ 780M (2700MHz)                                                 |
| **Overall TOPS** | Up to 33-35 TOPS (via NPU + CPU + GPU combined on 7940HS) | Up to 38 TOPS (Explicitly stated by Minisforum for NPU + CPU + GPU)       | Up to 38 TOPS (Explicitly stated by Minisforum for NPU + CPU + GPU)       |
| **RAM Type/Max.** | DDR5-5600MHz, Max 64GB (SO-DIMM x2)                        | DDR5-5600MHz, Max 64GB (SO-DIMM x2)                                        | DDR5-5600MHz, Max 64GB (SO-DIMM x2)                                        |
| **Storage Slots** | 2x M.2 2280 PCIe 4.0 SSD                                   | 2x M.2 2280 NVMe SSD (PCIe 4.0 x4, up to 4TB per slot)                     | 2x M.2 2280 NVMe SSD (PCIe 4.0 x4, up to 4TB per slot)                     |
| **USB4 Ports** | 2x USB4 (40Gbps, Alt PD)                                   | 2x USB4 (40Gbps; 1 rear with PD-in 100W & PD-out 15W; 1 front with PD-out 15W) | 2x USB4 (40Gbps; 1 rear with PD-in 100W & PD-out 15W; 1 front with PD-out 15W) |
| **OCuLink Port** | No                                                         | Yes                                                                        | Yes                                                                        |
| **Video Output** | 2x HDMI 2.1, 2x USB4 (DP Alt Mode)                         | 1x HDMI 2.1, 1x DP 2.0, 2x USB4 (DP Alt Mode)                              | 1x HDMI 2.1, 1x DP 2.0, 2x USB4 (DP Alt Mode)                              |
| **Ethernet** | 1x 2.5G RJ45                                               | 1x 2.5G RJ45                                                               | 1x 2.5G RJ45                                                               |
| **Wireless** | Wi-Fi 6E, Bluetooth 5.3                                    | Wi-Fi 7, Bluetooth 5.4                                                     | Wi-Fi 7, Bluetooth 5.4                                                     |
| **Power Input** | DC 19V Barrel Jack (120W)                                  | DC 19V Barrel Jack (120W) / **100W USB-C PD Input (Rear USB4)** | DC 19V Barrel Jack (120W) / **100W USB-C PD Input (Rear USB4)** |
| **Dimensions (LWH)**| 130 x 126 x 52.3 mm                                        | 128 x 126 x 52 mm                                                          | 128 x 126 x 52 mm                                                          |
| **Weight** | ~0.67 kg                                                   | ~0.6 kg                                                                    | ~0.6 kg                                                                    |
| **Unique Features** | Cold Wave 2.0 cooling, Active SSD/RAM cooling              | OCuLink port, USB-C PD Input, Wi-Fi 7, more compact                        | OCuLink port, USB-C PD Input, Wi-Fi 7, more compact                        |

**Key Takeaways for your purpose:**

1.  **AI Performance (iGPU):** All three models utilize the **Radeon 780M** (or its slight variant like the 2700MHz clock on the AI X1). This means their raw integrated graphics performance for tasks like Stable Diffusion image generation will be **very similar and excellent** for integrated graphics.
2.  **Overall TOPS:** The AI X1 models (260 and 255) explicitly advertise **38 TOPS**, indicating a slightly more capable (or better integrated/advertised) NPU contribution compared to the UM790 Pro's typical ~33-35 TOPS. For current Gen AI use, a higher TOPS number is always better, especially for CPU/NPU-offloaded tasks.
3.  **Portability & Power:** The **AI X1 (both 260 and 255 variants) are superior for portability** due to their slightly smaller/lighter form factor and, critically, their **explicit support for 100W USB-C Power Delivery input**. This makes them genuinely usable with high-wattage power banks, which the UM790 Pro can *sometimes* do but isn't officially advertised for its primary power input.
4.  **Future Proofing (OCuLink):** The **AI X1 models (both 260 and 255)** have the significant advantage of an **OCuLink port**. This allows for a much higher bandwidth connection to an external dedicated GPU (eGPU) than USB4/Thunderbolt, offering near-desktop GPU performance if you ever decide to expand your AI capabilities with a full-sized graphics card.
5.  **Connectivity:** The AI X1 models also benefit from **Wi-Fi 7** and **Bluetooth 5.4**, which are newer standards than the UM790 Pro's Wi-Fi 6E and BT 5.3.

**Recommendation:**

For your specific goal of Gen AI (image/video generation) with a focus on affordability and the ability to be powered by a power bank, the **Minisforum AI X1 (Ryzen 7 260 or Ryzen 7 255)** would be the more compelling choice over the UM790 Pro. The slight difference in CPU boost clock between the 260 and 255 is unlikely to be noticeable in most AI workloads, as the bottleneck will typically be the iGPU or NPU.

The **OCuLink port and confirmed 100W USB-C PD input** make the AI X1 series a more versatile and portable option for AI enthusiasts.
