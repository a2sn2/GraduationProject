## Object Tracking System (Graduation Project)

**Platform:** Ubuntu (Linux) • **Core:** Python, OpenCV  
Real-time object tracking using classical CV + ML, evaluated on recorded streams and webcam input.

**Docs**
- Final Report: [docs/FinalALHassanALShamiObjectTrackingAlgorithms.pdf](docs/FinalALHassanALShamiObjectTrackingAlgorithms.pdf)
- Transcript: [docs/Transcript_8_Semesters.pdf](docs/Transcript_8_Semesters.pdf)
- Specialization Plan: [docs/BSc_Specialization_Plan.pdf](docs/BSc_Specialization_Plan.pdf)
- Degree Proof (EN): [docs/BSc_English_StudyProof.pdf](docs/BSc_English_StudyProof.pdf)
- Recommendations: in [/recommendations](recommendations/)
- Photos: in [/media](media/)


**How to run (sketch)**
```bash
python3 -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
python src/run_tracker.py --source 0
