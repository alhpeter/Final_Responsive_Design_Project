# ⚠️🚨 PLEASE READ BEFORE GRADING 🚨⚠️

Welcome! This repository contains the code for my **Responsive Photo Gallery Project**. You can also view the live website here:

👉👉👉 [Live Website](https://alhpeter.github.io/Final_Responsive_Design_Project/) 👈👈👈  

Please click the link above to experience the actual site in action.

---

## Important Notes for Reviewers

### Scroll Behavior / Smooth Scrolling
- By default, most systems have **smooth scroll animations enabled**.  
- The code implements the `prefers-reduced-motion` media query, which **disables the smooth scroll** for users who have turned on "Reduce Motion" in their system settings.  
- If you are **seeing the scroll animation still working**, this is **not a code error** — it simply means your system currently has animations enabled.  
- To test the reduced-motion functionality:
  - **macOS / iOS**: System Settings → Accessibility → Display → Turn on **Reduce Motion**  
  - **Windows**: Settings → Accessibility → Visual Effects → Turn off **Show animations in Windows**  
- After testing, you can turn animations back on normally.  

---

### Dark Mode / Light Mode
- The site respects your system’s **color scheme**:  
  - If your system is in **dark mode**, the page automatically shows the **dark color scheme**.  
  - Otherwise, the page defaults to **light mode**.  
- This behavior uses the `prefers-color-scheme` media query in CSS.  

---

### Accessibility / WAVE Notes
- If you have a **dark mode browser extension** enabled, WAVE may report **false positive errors**. These are caused by the extension, **not the website**.  
- Disable dark mode extensions before running WAVE to get accurate results.  

---

Thank you for reviewing! Enjoy exploring the gallery. 😺🐶
