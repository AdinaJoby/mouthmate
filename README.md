# 💄😮 Mouth Open Soundboard

## Team Name

**[Team Name]**

### Team Members

* **Team Lead:** Adina Joby - St. Joseph's college of engineering and technology , palai
* **Member 2:** Angel John Shaje - St. Joseph's college of engineering and technology , palai
* 
# Project Description

Have you ever noticed that people mysteriously open their mouths while applying eye makeup?

We noticed it.

We questioned it.

We decided to do absolutely nothing about it — except make it embarrassing.

**Mouth Open Soundboard** uses the webcam to detect when someone opens their mouth while doing eye makeup and immediately plays an embarrassing sound effect.

Because apparently, **your mouth needs to stay shut while your eyeliner is doing its job.** 💄😮🔊

---

# The Problem (that doesn't exist)

When applying eye makeup, many women unconsciously open their mouths.

Does opening the mouth help apply eyeliner?

**No.**

Does keeping the mouth closed make the eyeliner better?

**Also no.**

Is anyone asking us to fix this?

**Absolutely not.**

But we found this completely unnecessary phenomenon and decided that it deserved an even more unnecessary solution.

---

# The Solution (that nobody asked for)

Our system watches the user through the webcam while they apply makeup.

### Mouth closed:

💄🙂

**Everything is fine.**

### Mouth opens:

💄😮

🔊 **EMBARRASSING SOUND**

The system detects the mouth opening and immediately plays a funny sound effect.

The user then realizes:

> **“WHY IS MY MOUTH OPEN?”**

And proceeds to close it.

For approximately three seconds.

Then it happens again.

🔊 **BONK.**

---

# Technical Details

## Technologies/Components Used

### For Software:

**Language**

* Python

**Libraries**

* OpenCV
* MediaPipe
* Pygame

**Tools**

* Visual Studio Code
* Python
* Laptop webcam
* GitHub

### For Hardware:

No special hardware is required.

* 💻 Laptop/PC
* 📷 Built-in/external webcam
* 🔊 Laptop speakers or headphones

---

# Implementation

## For Software

The webcam continuously captures the user's face.

Facial landmarks are detected using MediaPipe, and the system monitors the mouth area.

When the mouth opens beyond the defined threshold:

**Mouth Open → Sound Effect Plays**

When the mouth is closed:

**Mouth Closed → Silence**

### The extremely important algorithm:

```text
       📷 WEBCAM
           ↓
     👤 FACE DETECTION
           ↓
     👄 MOUTH DETECTION
           ↓
     IS MOUTH OPEN?
        ↙       ↘
      NO         YES
      ↓           ↓
   😌 SILENCE   🔊 EMBARRASSMENT
```

---

# Installation

Make sure Python is installed.

Open the project folder in the terminal and run:

```bash
pip install opencv-python mediapipe pygame
```

---

# Run

Inside the project folder, run:

```bash
python "Mouth_open_soundboard.py"
```

Then:

1. Turn on the webcam.
2. Start applying eye makeup.
3. Open your mouth naturally.
4. Listen.
5. Become self-aware.
6. Continue applying makeup.
7. Open your mouth again.
8. Repeat.

---

# Project Documentation

## For Software

### Screenshot 1 — Peaceful Makeup

<img width="386" height="310" alt="image" src="https://github.com/user-attachments/assets/75ca3e60-55c1-491f-b055-681d94bff00e" />


**Caption:** The user is applying eye makeup with their mouth closed. Everything is peaceful. For now.

---

### Screenshot 2 — The Moment

<img width="389" height="317" alt="Screenshot 2026-09-12 005645" src="https://github.com/user-attachments/assets/1a794ef8-9e47-40f6-8563-5d1286e1a756" />

**Caption:** The system detects the user's mouth opening while applying eye makeup.

---

### Screenshot 3 — Consequences

<img width="386" height="310" alt="Screenshot 2026-09-12 005710" src="https://github.com/user-attachments/assets/4433fd03-fdef-4a1f-ae75-5053010145ec" />


**Caption:** The mouth-opening event triggers the embarrassing sound effect.

---

# Diagrams

**Caption:** The system detects the face, monitors the mouth, determines whether it is open, and triggers a sound effect.

```text
💄 APPLY EYE MAKEUP
          ↓
      📷 WEBCAM
          ↓
   👤 FACE DETECTION
          ↓
   👄 MOUTH DETECTION
          ↓
    MOUTH OPEN?
      ↙       ↘
    NO         YES
    ↓           ↓
 😌 SILENCE   🔊 SOUND
                ↓
          😳 SELF-AWARENESS
                ↓
          CLOSE MOUTH
                ↓
       💄 CONTINUE MAKEUP
                ↓
          😮 MOUTH OPENS
                ↓
             🔊 AGAIN
```

---

# For Hardware

**Caption:** No external circuit is required. The laptop webcam acts as the input and the laptop speaker acts as the output.

### Schematic

**Caption:** Webcam input → facial landmark detection → mouth-state detection → sound output.



**Components shown:**

* Laptop
* Webcam
* Speakers

---

### Build
<img width="334" height="319" alt="image" src="https://github.com/user-attachments/assets/9c83e371-546f-40fb-a4ae-97bd6e9ac3d7" />

<img width="457" height="391" alt="image" src="https://github.com/user-attachments/assets/88b1683e-56d4-478e-b6f2-36f62d06e240" />


**Build process:**

1. Set up Python.
2. Install the required libraries.
3. Connect the webcam.
4. Implement mouth detection.
5. Add embarrassing sound effects.
6. Test with natural mouth movements.
7. Question why people open their mouths while applying eyeliner.

---

### Final Product
<img width="386" height="310" alt="Screenshot 2026-09-12 005710" src="https://github.com/user-attachments/assets/5c51aef7-cb62-46bc-98c3-7cec144f11e0" />


**Final build:**
A webcam-based system that detects mouth opening during eye-makeup application and responds with an embarrassing sound effect.

---

# Project Demo

## Video

https://drive.google.com/file/d/1MMhlibnA19jZPHGujb5Pj5fC6RbZLGsr/view?usp=sharing

### What the video demonstrates

The video shows a user applying eye makeup.

At first, everything is normal.

Then, without realizing it, the user opens their mouth.

**🔊 EMBARRASSING SOUND**

The user realizes what happened and closes their mouth.

A few seconds later...

😮

**🔊 AGAIN.**

The system successfully detects the mouth opening and triggers the sound effect.

---
 additions:

https://github.com/AdinaJoby
# Team Contributions

**[Adina Joby]:**
Developed the mouth detection and webcam functionality.

**[Angel John Shaje]:**
Implemented the sound effects and tested different mouth-opening conditions.


---

# 🤡 Why Does This Exist?

Because apparently...

### 👁️ Eye makeup requires concentration.

### 👄 The mouth opens for absolutely no reason.

### 🔊 And now there are consequences.

---

# The Final Question

### Does keeping your mouth closed help you apply eye makeup?

**NO.**

### Does opening your mouth help?

**ALSO NO.**

### Will our system make you keep your mouth closed?

**Probably not.**

### Is there any practical reason for this project?

**Absolutely not.**

### Did we make it anyway?

**YES.**

---

# 💄😮 FINAL VERDICT

## **KEEP YOUR MOUTH SHUT.**

Not because it helps your makeup.

Not because it makes your eyeliner straighter.

Not because science told us to.

### **Because otherwise the soundboard will expose you.** 🔊😭

---

Made with ❤️, eyeliner, questionable decisions, and absolutely no practical purpose at **TinkerHub Useless Projects**.
