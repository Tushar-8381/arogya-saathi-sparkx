# Arogya Saathi - AI ASHA Worker for the World - 90+ Languages
### Techfest IIT Bombay | SPARKX | Sarvesh Pandey - Durjanpur, Ballia, UP | AICS IIT Patna Hybrid

> **Tagline:** AI should reach the last village, in its own language.

**Live Demo:** Voice-first health companion that listens in ANY language (Bhojpuri, Marathi, Tamil, Bengali, French, Spanish etc), auto-detects with Whisper Large-v3, and guides to nearest PHC.

#### The Problem
Rural families face distance, language, and availability barriers. Gap: Symptoms → Understanding Risk → Reaching PHC.

#### Solution Flow
SPEAK (Any Language) → Whisper Large-v3 Auto-Detect → AI Triage + Vision (Anemia/Oral screening - visual signal only) → Same-language TTS Reply + PHC Map → SAFETY REFERRAL

#### Key Features
- **90+ Languages:** Whisper Large-v3 + Bhashini (22 Indian) + Sarvam AI
- **Voice-first:** No typing needed
- **Vision AI:** Possible anemia indicators (visual only, clinical test required)
- **Safety First:** No diagnosis, No prescription. Only triage: Monitor / Visit PHC / Urgent PHC

#### Tech Stack
- Mobile: Flutter
- Backend: Python FastAPI
- AI: Whisper Large-v3, gTTS/Bhashini TTS
- Map: Google Maps / OSM link for PHC

#### Project Structure
- /backend - FastAPI app.py with /listen endpoint
- /flutter_app - Flutter app with big mic button
- /docs - Arogya_Saathi_SPARKX.pdf (10 slides)

#### Safety Disclaimer
This is a screening/support tool, not a medical device. Does NOT replace doctors/ASHA workers. For emergencies, visit nearest PHC/Ayushman Arogya Mandir immediately.

#### Vision
2026 Prototype → 2027 Supervised Pilot + Validation → Future: 90+ World Language Network + Offline Mode + Open API

**From Durjanpur Ballia to World**
