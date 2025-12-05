# 🏐 Volleyball Real-Time Action Detection (Single Camera)

Lightweight, real-time volleyball analytics system that runs on **one regular camera** (phone, webcam, or broadcast feed).  
No multi-camera setup · No external sensors · No Hawk-Eye · Affordable for youth clubs, schools, and developing federations.

Live demo:  
https://www.linkedin.com/posts/omar-aloweidi-06201424b_volleyballanalytics-sportsai-performanceanalyst-ugcPost-7400956213649166336-uw8i

## ✨ Features (as of December 2025)
| Action                  | Detected Live? | Details                              |
|-------------------------|----------------|--------------------------------------|
|Action Detection         | Yes            | Serve/Reception OverHead             |
| Set tempo               | Yes            | Tempo 1 / High ball        |
| Ball detection          | Yes            |Capture Ball In Video        |

## 🚀 Quick Start (Tested on Windows/Linux/Mac)

```bash
# 1. Clone the repo
git clone https://github.com/Deyalking/Volleyball.git
cd Volleyball

# 2. Create virtual environment (recommended)
python -m venv venv
source venv/bin/activate    # Linux/Mac
venv\Scripts\activate       # Windows

# 3. Install requirements
pip install -r requirements.txt

# 4. Run live demo on webcam
python main.py --source 0

# Or run on a video file / YouTube / RTSP stream
python main.py --source path/to/match.mp4
