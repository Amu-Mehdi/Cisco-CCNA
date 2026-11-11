# Lesson L00 --- Q&A (Quick Review)

---

**Q1: What is the main difference between "asking" and "commanding" in the command line?**
**A1:** Asking (like `ipconfig`) only reads and displays information without changing anything. Commanding changes the device's settings.

---

**Q2: What does the command `ipconfig` do?**
**A2:** It displays the PC's current network settings: IP address, subnet mask, and default gateway.

---

**Q3: Why do we use the command `ping 127.0.0.1` first in troubleshooting?**
**A3:** Because it tests the local network software of the device without touching any cable. If it replies, the device's network stack is healthy.

---

**Q4: What is the meaning of `127.0.0.1`?**
**A4:** It is the "localhost" address. Every device uses it to refer to itself. The packet never leaves the PC.

---

**Q5: What type of cable connects a PC to a switch?**
**A5:** Copper Straight-Through cable.

---

**Q6: What does a green link light on a port mean?**
**A6:** The physical connection is established, and the two devices can see each other at the physical layer.

---

**Q7: If `ping 192.168.10.11` fails, what are the first three things to check?**
**A7:** 
1. Check the cable and green link lights.
2. Verify IP addresses on both PCs using `ipconfig`.
3. Make sure both PCs have the same subnet mask (`255.255.255.0`).

---

**Q8: Why is the default gateway empty in this lab?**
**A8:** Because there is no router in the lab yet. A gateway is only needed to reach devices outside the local network.

---

**Q9: What does the error `'ipconfg' is not recognized` mean?**
**A9:** The device did not understand the command because of a typo. A letter (i) is missing.

---

**Q10: What is the file naming convention for lab files in this course?**
**A10:** `<LessonID>-<Topic>-v<Version>.pkt` --- for example, `L00-intro-v1.pkt`.

---

**Q11: What is the first step when you start troubleshooting a network issue?**
**A11:** Start from the bottom of the OSI model: check the physical connection (cables and link lights) first.

---

**Q12: Why do we save the lab file with a version number?**
**A12:** To keep a history of changes. If something breaks, we can return to a previous working version.

---

**Q13: In the fictional company "Arman-Data", what is your role in this lesson?**
**A13:** A network intern on the first day of work.

---

**Q14: What are the six CCNA exam domains?**
**A14:** 
1. Network Fundamentals (20%)
2. Network Access (20%)
3. IP Connectivity (25%)
4. IP Services (10%)
5. Security Fundamentals (15%)
6. Automation and Programmability (10%)

---

**Q15: What is the goal of this course beyond passing the exam?**
**A15:** To become a network technician/engineer who can design, configure, verify, troubleshoot, and justify decisions independently.