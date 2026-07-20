# Day 2 (July 19th 2026)

## 📌 Overview

Focused on refining the work completed on Day 1 by fixing issues with the main chassis and modeling the side extensions (side pods) attached to the body. The session challenged me to think creatively when troubleshooting unexpected modeling problems while introducing me to several important concepts that will become essential for more advanced SolidWorks projects.

## 📈 Progress
- Corrected issues with the lofted main chassis.
- Modeled the side extensions of the main body.
- Improved the overall geometry and continuity of the chassis.

## 📝 Documentation
I documented the entire modeling process in a timelapse video. Check it out!

🎥 **Watch here:**  
https://youtu.be/KGZ6YAmMoVg

📸 **Final Look of Today**
<img width="2875" height="1706" alt="스크린샷 2026-07-19 173927" src="https://github.com/user-attachments/assets/198ce65a-016d-4add-9673-63ed0ae2e620" />

## 🛠️ Skills & Techniques Learned
- **Separate Bodies** — Creating independent solid bodies to allow more flexible operations such as cuts, extrusions, and fillets on individual components.
- **Loft Troubleshooting** — Understanding how guide curves and pierce relations influence loft quality and surface continuity.
- **Problem Solving** — Diagnosing modeling errors and developing solutions without relying solely on tutorials.

## 💭 Reflection
Compared to Day 1, `today's workflow was much smoother`. I spent significantly `more time designing and modeling` rather than preparing my workspace or troubleshooting recording issues. Although the workflow improved, the CAD work itself was considerably more challenging. There were numerous occasions where I had to `rethink my approach, rebuild features, and solve problems independently`. Looking back, these challenges ended up being the `most valuable part of today's session` because they strengthened both my technical skills and my confidence.

The first issue I encountered involved the main chassis that I had created using the Loft feature. The chassis was generated from three profile sketches connected by multiple guide curves. However, after examining the model more closely, I noticed that `the top and bottom surfaces contained noticeable gaps`. After investigating the problem, I realized that while the outer guide curves were properly constrained, there were `no guide curves controlling the loft along the centerline of the chassis`. To resolve this, I `reused one of the sketches` I had previously created on the midplane and added the `necessary Pierce relations` so that the guide curves correctly intersected the loft profiles. This forced the loft to follow the centerline more accurately and eliminated the unwanted gaps. Although the fix itself was relatively simple, it was `an incredibly rewarding moment`. It was the first modeling issue that I discovered, diagnosed, and solved entirely on my own `without consulting the tutorial or any external references`. Most of my previous CAD projects involved following detailed instructions where unexpected issues rarely occurred. This experience reminded me that real engineering projects often `require independent thinking` rather than simply following a set of steps, and successfully solving the problem gave me a significant boost in confidence.

The side extensions introduced an even greater challenge. Initially, there was `a small gap between the extension and the main body` that wasn't present in the reference model. After carefully inspecting the sketches, I adjusted several dimensions and realigned portions of the geometry until the transition became smooth. However, the most difficult obstacle came later when I needed to `apply cuts exclusively to the side extension`. I noticed that the reference model could modify the extension without affecting the main chassis, but every cut I created altered the entire body because `my side extension had been merged into the chassis as a single solid`. After researching different resources and experimenting with several approaches, I learned the importance of `creating separate solid bodies` during the modeling process. Once I understood this concept and rebuilt the feature accordingly, I was finally able to apply cuts, extrusions, and fillets to the side extension independently without modifying the chassis. This was easily `one of the most satisfying moments` I've experienced since I started learning CAD. It took a considerable amount of `experimentation, research, and persistence` before I found the solution, but `solving it entirely through my own reasoning made the accomplishment far more meaningful`. More importantly, I learned a fundamental SolidWorks concept that will undoubtedly be useful in future projects.

Today's experience reminded me that engineering is `rarely a straightforward process`. Behind every finished model are countless small decisions, unexpected obstacles, and iterative improvements. Success often depends less on knowing the correct answer immediately and more on `having the patience and determination` to investigate problems until a solution is found. By the end of today's session, I felt noticeably `more confident` than when I started. Every challenge I overcame reinforced the idea that engineering is a skill developed through `persistence, curiosity, and continuous learning`. With each session, I feel myself becoming more comfortable tackling increasingly complex CAD projects, and I'm `excited to carry this momentum` into the next stage of building the Formula One car.

⬅️ [Previous](Day_1.md) | 🏠 [Home](../) | ➡️ [Next](Day_3.md)
