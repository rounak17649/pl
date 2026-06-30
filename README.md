# PlantSafe AI

A plant disease detection platform. Upload a leaf photo, pick your plant, and get a real AI prediction — plus browse 40+ diseases, take a symptom quiz, and track care tasks.

## Run it

```bash
git clone https://github.com/rounak17649/pl.git
cd index.html
```

## How the AI Scanner works

I trained 6 separate image classification models myself using **Google Teachable Machine**, one per crop, using leaf images from the **PlantDoc Dataset**. Each model runs directly in the browser via TensorFlow.js — no backend server needed.

| Plant | Model |
|---|---|
| 🍅 Tomato | https://teachablemachine.withgoogle.com/models/z2niuamRf/ |
| 🍎 Apple | https://teachablemachine.withgoogle.com/models/X4CmAVvRJ/ |
| 🥔 Potato | https://teachablemachine.withgoogle.com/models/MIMDs8u73/ |
| 🍇 Grape | https://teachablemachine.withgoogle.com/models/67ZHczOkq/ |
| 🌽 Corn | https://teachablemachine.withgoogle.com/models/c45p88bIJ/ |
| 🫑 Bell Pepper | https://teachablemachine.withgoogle.com/models/81ubzV8J9/ |

Each link is the official Teachable Machine sharable export — you can open any of them to see the model's training summary directly on Google's platform.

## Features

- **AI Leaf Scanner** — pick a plant, upload a photo, get real predictions with confidence scores
- **Disease Library** — 40+ diseases, searchable with highlighted matches, filterable by crop
- **Leaf Symptom Quiz** — answer 3 questions, get a likely disease category
- **Care Checklist** — add your own watering/care reminders, saved in browser storage
- **Dark/Light Theme Toggle** — saved across visits
- **FAQ** section

## Stack

HTML · CSS · Vanilla JS · TensorFlow.js · Teachable Machine

## Dataset

Training images sourced from the [PlantDoc Dataset](github.com/pratikkayal/PlantDoc-Dataset).

## Author

[@rounak17649](https://github.com/rounak17649)
