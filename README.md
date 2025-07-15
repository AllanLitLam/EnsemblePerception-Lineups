# Ensemble Averaging in Simultaneous and Sequential Lineups

**How does the **way information is presented** (i.e., all at once vs. one at a time) affect our ability to form mental summaries and make accurate decisions?**  
This project investigates that question in the context of police lineups using the concept of **ensemble perception**, which is the ability to extract summary information from a group of similar items.

---

## 🎯 Project Summary

This research explored how **presentation format (simultaneous vs. sequential)** influences the formation of **ensemble face representations** and the resulting **discriminability** in an eyewitness identification task.

Across four experiments, participants studied a group of six faces presented either **all at once (simultaneously)** or **one at a time (sequentially)**. Later, they were tested on their ability to distinguish an **ensemble morph** (average of studied faces) from a **new morph** (average of unseen faces). 

✅ We found that participants were **significantly better at identifying the correct morph** when faces were presented **simultaneously**, suggesting a more precise ensemble representation under that format.

---

## 🧠 UX Implications

As a UX researcher-in-training, I approach experimental psychology as a foundation for studying:
- **Information architecture**: How the arrangement of elements impacts memory, attention, and choice  
- **Cognitive load**: The hidden costs of sequential vs. parallel information processing  
- **Perceptual grouping**: How users form mental summaries or patterns from UI components

This project directly informs UX domains like:
- **Dashboards**: Should we show multiple data streams together or one at a time?
- **Visual search tasks**: Do users perform better when all options are visible?
- **Memory-based decisions**: When is working memory overloaded by presentation design?

---

## 🧪 Experimental Details

- **Independent Variable**: Presentation format (simultaneous vs. sequential)
- **Dependent Variable**: Discriminability between studied ensemble morph vs. new morph
- **Design**: Between- and within-subjects (depending on experiment)
- **Analyses**: Signal Detection Theory, ROC, t-tests across conditions

🧬 Scripts included:
- `Exp1.Rmd`
- `Exp2.Rmd`
- `Exp3a.Rmd`
- `Exp3b.Rmd`

---

## 💡 Key Findings

- Simultaneous face presentation resulted in **higher ensemble sensitivity**.
- Sequential face presentation disrupted ensemble encoding, likely due to **working memory limitations**.
- These results support the **Ensemble model** of lineup perception, which predicts that diagnostic features are easier to detect when a more accurate ensemble is formed.

---

## 🔍 Theoretical Insight

This project supports the **diagnostic feature-detection theory**, where users judge unfamiliar items by comparing them to a mental average. In lineups, this ensemble average is **better formed when all items are seen together**, enabling higher decision accuracy.

---

## ✨ Impact Statement

Our ability to summarize information quickly is a core feature of visual cognition. When systems present information **sequentially** rather than **simultaneously**, they place a burden on working memory, impairing our ability to detect meaningful patterns.  

This has direct implications for **UX design**, especially in tasks where **recognition**, **comparison**, and **pattern detection** are critical.

---

## 🚀 UX-Relevant Takeaways

- Simultaneous layouts improve pattern perception and reduce memory burden  
- Sequential layouts require users to reconstruct context, increasing cognitive effort  
- When designing interfaces involving **multiple similar elements**, consider showing them **side-by-side** to enhance ensemble encoding

---
