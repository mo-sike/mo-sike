### Hi, I'm Mohammed Saqlain 👋

Software Engineer at **HARMAN International** (Bengaluru), working on **test automation for Android automotive infotainment**.
I build Robot Framework / pytest frameworks and Jenkins CI/CD pipelines, and I use computer vision and ML to make UI tests self-healing.

- 🔁 Led a C# → Python migration of our test automation framework
- 🚗 Automate HMI, API, OCR and hypervisor testing; run CTS / VTS on AWS
- 🧠 Exploring CV/ML for testing: YOLOv8, CLIP, graph matching

---

#### ⭐ Featured project

**[Visual Self-Healing UI Test Automation](https://github.com/mo-sike/SelfHealing_UI_Automation)**
Screenshot-only change detection and locator healing for mobile UI tests, with no DOM, XPath or network access needed.

- YOLOv8 trained on the RICO dataset (66k Android screens) to detect 10 UI element classes
- Each screen is modelled as a KNN spatial graph and matched using pHash, colour, OCR text, CLIP ViT-B/32 embeddings and neighbour structure
- A tree-ensemble classifier labels each change type and scores its severity to give PASS/FAIL regression verdicts
- Confidence triage sorts every locator into **AUTO-HEAL / REVIEW / CANNOT-HEAL**, so low-confidence fixes never silently break tests

`Python` `YOLOv8` `CLIP` `PyTorch` `scikit-learn` `OpenCV` `NetworkX` `Tesseract`

---

#### 🛠️ Tech I work with

**Languages:** Python · C++ · SQL · Shell / Batch
**Test automation:** Robot Framework · pytest · Selenium · Appium · uiautomator2 · Allure
**ML & CV:** YOLOv8 · CLIP · PyTorch · scikit-learn · OpenCV · Tesseract OCR
**DevOps & cloud:** Jenkins · Git · Gerrit · GitHub · AWS · GCP
**Platforms & protocols:** Android · Linux · Windows · ADB · CAN · UART · SSH

---

#### 📫 Find me

[LinkedIn](https://www.linkedin.com/in/mohammed-saqlain-49bb18172/) · [X / Twitter](https://x.com/noxto88)
