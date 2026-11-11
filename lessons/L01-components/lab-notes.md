# Lab Notebook — Lesson L01

- **Experiment Title:** ArmanData — Small Room — Star Topology — Version 1
- **Lesson ID:** L01
- **Date and Time:** November 11, 2026 — 21:00
- **Author:** Mohammad Mahdi Ganji
- **Organizational Role:** Network Intern — ArmanData

---

## 1. Objective

To understand network components and implement a star topology with standard naming.

---

## 2. Devices and Experiment Map

One 2960 switch, two computers, and one server; all connected to the central switch.

| Standard Name | Device Type |
|---|---|
| `SW1` | 2960 Switch |
| `PC1` | Computer |
| `PC2` | Computer |
| `SRV1` | Server |

---

## 3. Addressing Table

None; addressing was prohibited in this lesson.

---

## 4. Prerequisites and Packet Tracer Version

- **Packet Tracer Version:** Version 8.2.2
- **Prerequisites:** Lesson Zero prerequisites (installation, straight-through cable, saving with version number, Git) have been confirmed.

---

## 5. Configurations Performed

Standard naming: `PC1`, `PC2`, `SW1`, `SRV1`

| From Device / Port | To Device / Port | Cable Type |
|---|---|---|
| `PC1` / `FastEthernet0` | `SW1` / `FastEthernet0/1` | Straight-through |
| `PC2` / `FastEthernet0` | `SW1` / `FastEthernet0/2` | Straight-through |
| `SRV1` / `FastEthernet0` | `SW1` / `FastEthernet0/3` | Straight-through |

---

## 6. Verification Method

- Both ends of the cables showing green dots;
- Names matching the naming table;
- Checking cable type and ports by hovering the mouse over the cable;
- The map being star-shaped (everything connected only to the switch).

---

## 7. Evidence

An image of the star map with standard naming; attached.

---

## 8. Analysis and Interpretation of Evidence

The green dots indicate that the physical layer is healthy and the cables are connected correctly; standard naming ensures the map is consistent with the course documentation.

---

## 9. Errors and How They Were Fixed

No errors were observed.

---

## 10. Conclusion and Limitations

The star map was built; at this stage, addressing and pinging were not performed and were deferred to later lessons.

---

## 11. Risk or Security Note

A device that does not follow the naming convention gets lost in the map and may not be noticed as an unknown device.

---

## 12. Retest Method

Open the file and re-check the four verification items.

---

## 13. Final Status

Completed.

---

## 14. Attachments

```mermaid
flowchart TD
    SW1["SW1"]
    PC1["PC1"] --- SW1
    PC2["PC2"] --- SW1
    SRV1["SRV1"] --- SW1