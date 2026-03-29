SAMAY DAS — Portfolio Website

I build AI systems that perceive, analyze, and act in the real world.

Senior CS @ University of Toledo · GPA 3.433 · Graduating May 2026
Research Assistant @ UTMC · EEG · fMRI · Multimodal ML

What's in this repo
This is the source for my personal portfolio website — built as a single, self-contained HTML file with no build step, no frameworks, no dependencies to install.
It runs entirely in the browser using:

GSAP + ScrollTrigger — Apple-style scroll animations, pinned sections, word-by-word text reveals
Three.js — animated WebGL particle field background
Raw SVG — every icon, illustration, and 3D isometric project visual is hand-coded SVG (no image files)
Vanilla JS — interactive phone mockups, radar chart, eye-tracking avatar, FIFA card tilt

No npm. No bundler. Just open the file.

Sections
SectionWhat it doesBoot screenFIFA-style loading sequence with progress barHero3D FIFA Ultimate Team gold card with animated Barcelona avatar — eyes follow your cursorSkill RadarInteractive hexagonal spider chart with 3 comparison profilesTech FormationFull football formation board with 11 SVG tech iconsProjectsApple-style horizontal scroll with 9 match cardsYourLawyerLive interactive React Native app mockup (3 screens)CampusConnectLive interactive app mockup with AI scan animationExperience4 role cards from resume + Education with Thapar → UToledo transfer storyContactForm + real links

Projects featured

Tool Tally — Senior design: Raspberry Pi + camera + ML classifier + servo motor sorting system
Multimodal Medical Analysis — EEG/fMRI research at UTMC using Python, MATLAB, R
Policy Navigator — RAG system with Flan-T5, PDF parsing, retrieval pipeline
ML Classification — XGBoost, SVM, Random Forest + SHAP explainability
Brain Tumor CNN — DICOM medical imaging with TensorFlow/Keras
Autonomous Buggy — Self-driving prototype with OpenCV + motor control
CampusConnect — AI-powered lost & found for UToledo with CV classification
VisiSecure — Real-time ATM mask detection with deep learning
YourLawyer (in progress) — Emergency legal assistance app in React Native


Stack used in the site itself
Three.js r128       WebGL particle background
GSAP 3.12           Scroll animations, ScrollTrigger, timelines
Barlow Condensed    Display font (FIFA scoreboard feel)
JetBrains Mono      Monospace / terminal labels
Outfit              Body font
Raw SVG             All icons and project illustrations

Run it
bash# Option 1 — just open it
open samay-portfolio-v9.html

# Option 2 — serve locally
npx serve .
# or
python3 -m http.server 8000
No install needed.

Contact
Email — Samay.Das@rockets.utoledo.edu
LinkedIn — linkedin.com/in/samaydas
Phone — 419-297-4494
Location — Toledo, OH

Built without a framework. Animated without a library of components. Every pixel intentional.
