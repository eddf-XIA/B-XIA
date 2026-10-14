## Houchunxiao (Byron) Xia

I build data pipelines, models and AI systems, and carry them all the way to tools people actually use.

📫 **hxia36@uchicago.edu** · Chicago, IL · [LinkedIn](https://www.linkedin.com/in/%E6%98%A5%E6%99%93-%E5%A4%8F%E4%BE%AF-a50986443)

- M.S. in Applied Data Science (Thesis Track), University of Chicago, expected June 2028
- B.S. in Data Science & Economics, University of Wisconsin–Madison, December 2025
- Seeking **Summer 2027 internships** in data science, data engineering and analytics

---

### Bee Wing Lab: computer vision for bumblebee wing morphometrics
[**eddf-XIA/BeeWingApp-Portfolio**](https://github.com/eddf-XIA/BeeWingApp-Portfolio)

Built for a university entomology lab: ArUco-marker perspective correction, a human-in-the-loop fallback, and DeepLabCut wing-vein landmark detection.

- **Result:** automatically annotated 1,600 bee wing images in 24 minutes (13 anatomical landmarks and 4 reference corners per image). The PI estimated the equivalent manual work at 3–4 undergraduate assistants for a full semester. Manual quality review was kept in the loop.
- **Model training:** a reproducible DeepLabCut training, evaluation and inference pipeline on UW–Madison's CHTC GPU cluster (Linux/SSH, Apptainer, HTCondor).
- **Delivery:** rebuilt as a Windows desktop app (PySide6, PyInstaller) that researchers unzip and run without installing anything, with outputs verified byte-identical to the original Streamlit version on regression fixtures.

### Honey bee pollen colour analysis
[**eddf-XIA/pollen-colour-demo**](https://github.com/eddf-XIA/pollen-colour-demo)

- **Earlier work (v1):** a Python image-processing pipeline that quantified pollen colour composition and diversity across 8,000+ images, with PCA and mixed-effects models comparing sites and years.
- **Refined method (v2):** per-pixel measurement/exclusion classes with reason codes, ColorChecker calibration, CIELAB/CIEDE2000 colour measurement and block-bootstrap uncertainty, applied to 48 research photos. The public repo shows redacted real examples and a runnable synthetic demo with 57 tests.

### DailyScope: AI-powered continuous research for Android
[**eddf-XIA/DailyScope**](https://github.com/eddf-XIA/DailyScope)

- A native Android app (Kotlin, Jetpack Compose) that runs web-grounded LLM research across 7 providers and turns it into source-backed reports separating new developments from updates.
- Strict schema validation, a single bounded repair, and stable event identity across runs. The core was ported from an earlier Python version and is backed by ~1,700 automated tests.

---

**Experience:** Research Technician & Field Technician, Gratton Lab (UW–Madison) · Data Engineering Intern, China Electronics Industrial Internet Co.

**Tools:** Python, SQL, R, Kotlin · pandas, scikit-learn, OpenCV, DeepLabCut, PyTorch · Tableau, Streamlit, PySide6 · Linux, Apptainer, HTCondor, Git · Ktor, PostgreSQL
