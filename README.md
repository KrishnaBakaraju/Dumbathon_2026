# Dumbathon 2.0

Welcome to **Dumbathon 2.0**, a hackathon where developers build functional apps with intentionally ridiculous mechanics.

Theme: **Apocalypse**

Teams must build an application while implementing several deliberately frustrating challenges.

---

# Tracks

## App Development Track

Participants must build **one of the following applications**:

* Alarm Clock
* Map Navigation
* E-commerce Barter System
* Survivor Journal / Blogging Platform

The core functionality must remain usable despite the dumb mechanics.

---

# Global Dumb Challenges (Mandatory)

Every application must implement all of the following:

## Face Recognition Lock

The application must only open if **Fariz’s face is detected**.

Requirements:

* Use real-time camera input
* If the face does not match, show a **lock screen with denial message**
* Suggested tools:

  * face-api.js
  * OpenCV
  * TensorFlow.js

---

## Ragebait CAPTCHA

After face unlock, a **frustrating custom CAPTCHA** must appear.

Examples:

* blurry images
* misleading instructions
* moving targets
* impossible looking grids

The CAPTCHA must be **annoying but solvable**.

Example prompts:

* "Select all safe zones"
* "Click all objects NOT on fire"

---

## Random Popup Interruptions

Whenever the user attempts a primary action:

* submit
* navigate
* purchase
* save

A **random popup must interrupt the action first**.

The action should only complete **after the popup is dismissed**.

Popup examples:

* Fake system alerts
* Supply shortages
* Radiation warnings
* Faction broadcasts

---

## Icon-Only Buttons

All interactive buttons must:

* Use **icons only**
* No text labels allowed

Allowed:

* Page headings
* Input placeholders
* Tooltips

---

# App-Specific Dumb Challenges

Each application must implement its assigned mechanic.

### Alarm Clock

To dismiss the alarm the user must complete a random challenge:

Examples:

* solve a math problem
* shake the device
* type a passphrase

Failure must escalate the alarm.

---

### Map Navigation

The map must initially generate a route **10x longer than the optimal path**.

Users must tap a **rhythmic pattern** to calm the GPS and reveal the correct route.

---

### E-commerce Barter System

The **Add to Cart button runs away from the cursor**.

Rules:

* Movement reacts to cursor proximity
* Button must still be trappable
* Must show panic animation

---

### Survivor Journal

Every **5th word typed** is replaced with a random apocalypse word.

Example words:

* shadow
* dust
* ember
* silence
* teeth

A smart autocorrect system must allow restoring the original word.

---

# UI/UX Requirements

The application must visually reflect the **Apocalypse Theme**.

Recommended style:

* dark backgrounds
* hazard orange
* blood red
* ash gray
* distressed fonts

Use apocalypse terminology such as:

* Deploy instead of Submit
* Broadcast instead of Post

---

# Recommended Tech Stack

Frontend

* React
* Next.js
* Vue
* Vanilla JS

Backend (optional)

* Node.js
* Express
* Flask
* Django

Other Tools

* OpenCV
* TensorFlow.js
* face-api.js

---

# Submission Checklist

Teams must demonstrate:

* Core feature working
* Face recognition lock
* Ragebait CAPTCHA
* Random popups interrupting actions
* Icon-only buttons
* App-specific dumb mechanic
* Apocalypse UI theme

Source code must be organized and ready for inspection.

---

Good luck survivors.
