# Day 4 (July 21st 2026)

## 📌 Overview

Today's session was one of the most challenging and rewarding learning experiences I've had throughout this project so far. I designed the halo, front and rear wings, bargeboards, and exhaust of the Formula One car. However, the session was also marked by a major setback that forced me to rebuild a significant portion of the model.

Although the setback was incredibly frustrating at the time, it ultimately became one of the most valuable learning experiences of the project. I learned more from troubleshooting, recovering from my mistake, and rebuilding the model than I would have learned from a completely smooth modeling session.

## 📈 Progress

- Designed the front and rear wing.
- Modeled and attached the halo.
- Added the bargeboards.
- Designed the exhaust system.
- Rebuilt and recovered the model after a major modeling error.

## 📝 Documentation
I documented the entire modeling process in a timelapse video. Check it out!

🎥 **Watch here:**  
https://youtu.be/krzykkJIj-4

📸 **Final Look of Today**

<img alt="스크린샷 2026-07-21 165534" src="https://github.com/user-attachments/assets/b6a722d1-f99e-462c-b903-cf6c9e49156b" />

## 🛠️ Skills & Techniques Learned
- `Offset Surface, Extend Surface & Cut with Surface` — Using surface bodies to extend existing geometry and cut solid bodies based on surface intersections.
- `Variable Size Fillet` — Creating fillets with different radii along the same edge.
- `Face Fillet` — Applying fillets between selected faces to create smooth transitions.
- `Dome` — Creating domed geometry on selected faces.
- `Version Control & Backup` — Understanding the importance of regularly saving and uploading work to GitHub to protect against major modeling failures.
- `Technical Troubleshooting` — Diagnosing complex geometry problems by investigating the underlying cause rather than simply modifying dimensions.

## 💭 Reflection
Today's session was one of the `most devastating yet rewarding learning experiences` I've had throughout this project. After how smoothly Day 3 went, I expected today's session to follow a similar pattern. Instead, I encountered one of the most serious setbacks I've faced while learning 3D modeling.

The session started smoothly. I was introduced to the concept of creating an offset or copied surface and converting it into a separate surface body. I then learned how to extend that surface and use it as a reference for the Cut with Surface feature. Although the concept was initially unfamiliar, I was able to understand it relatively quickly and successfully applied it while modeling the halo.

The real challenge, however, began when I attempted to extend a surface created from the side of the Formula One car's nose.

<img alt="image" src="https://github.com/user-attachments/assets/fa10a327-c5f3-4231-834b-6138298fccd1" />

As shown in the image above, the `extended surface did not follow the surface on the right`. This created a problem because I could not correctly use the Cut with Surface feature. I spent approximately an hour trying to identify the cause of the problem. I repeatedly checked the dimensions and alignment of the surrounding geometry, but nothing appeared to explain the issue. Usually, the reference tutorial provides enough information to identify where I have deviated from the intended process. However, this time, the problem was not caused by an incorrect dimension or missing relation. Eventually, I began to consider that the issue might be related to the geometry of the surface itself rather than the sketch controlling it.

After examining the model more carefully, I discovered that `the side of the nose was not perfectly straight`. Although the deviation was almost impossible to notice visually, the surface was slightly tilted.

<img alt="image" src="https://github.com/user-attachments/assets/9840037c-02b1-421b-8888-e400f77c536b" />

This explained why the extended surface gradually diverged from the surface on the right. I eventually traced the cause back to `a fillet I had created on the nose` earlier in the project. The fillet had subtly altered the geometry of the side surface, creating the slight curvature that was causing the extension to diverge.

<img alt="image" src="https://github.com/user-attachments/assets/612c11b6-a293-4958-a8f0-b86f7ad7d32a" />

After finally identifying the source of the problem, I immediately went to remove the fillet. Unfortunately, I was so relieved to have finally found the cause that I acted without thinking. This particular fillet was not an isolated feature but was the `feature that connected several important components of the main body`. Once I deleted it, `almost every component I had created during Days 2 and 3 began to show errors`. The damage was done.

The model was suddenly reduced to a state similar to where I had been at the end of Day 2. Hours of work appeared to have disappeared because of a single careless decision. I was `extremely frustrated` and, honestly, felt like giving up. The thought of rebuilding the entire model from scratch was incredibly discouraging.

After taking a long break to clear my head, I returned to the project and began thinking about how I could recover. Fortunately, I remembered that I had `uploaded a previous version of the model to GitHub at the end of Day 3`. Instead of rebuilding everything from scratch, I was able to download the previous version and continue from there. This immediately taught me my first major lesson of the day: `Always save and back up your work regularly.`

The backup saved me hours of unnecessary work and allowed me to continue the project without losing all of my previous progress. It also reinforced `the importance of version control in engineering and software development.` GitHub was no longer just a place to showcase my finished work. It became an essential part of my workflow. With the previous version restored, I recreated the features I had lost. Since I had already modeled them once before, `the process was considerably faster the second time`. I also corrected the geometry that had caused the surface extension problem and successfully used the Cut with Surface feature. After finally solving the issue, I felt an `enormous sense of relief.`

I then continued with the remaining components of the car, including the bargeboards and front wing. Unfortunately, I encountered another documentation problem. Because I was eager to continue after being delayed by the earlier setback, I `forgot to check whether my recording was still running.` As a result, I failed to record part of the modeling process. This led to my second lesson of the day: `Always check the recording before beginning a new stage of the project.`

The latter half of the session was considerably smoother. I learned several new techniques, including `Dome, Variable Size Fillet, and Face Fillet`. These features introduced me to new ways of creating smooth and complex geometry, and I hope to experiment with them more extensively in future projects. Despite the difficult start, I eventually `completed the front wing, rear wing, exhaust, halo, and bargeboards`. Considering the setbacks I encountered at the beginning of the session, I was extremely satisfied with the progress I was able to make.

Today's experience taught me that `engineering projects are rarely as predictable as they appear from the outside`. A finished model can make the process look straightforward, but the actual design process is often filled with small errors, unexpected interactions between features, and decisions that have consequences much later in the workflow.

Most importantly, I learned that `failure can be incredibly valuable`. If I had not made the mistake of deleting the critical fillet, I would not have learned how `important it is to maintain regular backups`. If I had not struggled with the surface extension, I would not have developed `a deeper understanding of how Offset Surface, Extend Surface, and Cut with Surface interact with one another`. If I had not forgotten to check my recording, I might not have `developed a habit that guarantees a more reliable documentation workflow for future sessions`. I also learned the importance of `stepping away when frustration begins to affect decision-making`. Taking a break allowed me to return with a clearer mind and recognize that my previous work was not necessarily lost forever. Sometimes, the most important part of solving a problem is giving yourself enough time to think clearly about it. Although this was one of the most frustrating sessions I've had so far, it was also `one of the most rewarding`. I recovered from a major setback, learned several new SolidWorks techniques, improved my backup and documentation workflow, and gained `more confidence in my ability to troubleshoot complex problems independently`. The model may have temporarily gone backwards today, but my engineering skills definitely moved forward. 

⬅️ [Previous](Day_3.md) | 🏠 [Home](../) | ➡️ [Next](Day_5.md)
