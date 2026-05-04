# ITPM Assignment 1 – Functional and Usability Testing (Option 2)

## 👨‍🎓 Student Details

* **Name**: AHAMED M.A
* **Registration Number**: IT23782822
* **Module**: IT3040 – ITPM
* **Assignment**: Assignment 1 (Option 2)

---

## 📌 Assignment Overview

This assignment focuses on performing **functional testing** and **usability testing** of the website:

👉 https://www.pixelssuite.com/

The objective is to verify whether the features of the system work correctly and evaluate the usability of the interface.

---

## 🎯 Features Tested

The following features were tested:

1. Document Conversion
2. PDF Editing
3. Image Resizing
4. Cropping
5. Compression
6. Image Format Conversion
7. Meme Generation
8. Color Picker
9. Image Rotation
10. Image Flipping

---

## 🧪 Test Scenarios

* Total **36 test scenarios** were created
* Each feature includes:

  * ✅ 1 Positive Test Case
  * ❌ 2 Negative Test Cases

---

## 📊 Manual Testing

Manual test cases are documented in:

📁 `IT23782822_Manual_Test_Cases_for_Option_2.xlsx`

---

## 🤖 Automation Testing

One test scenario was automated using **Playwright** to verify the **image preview functionality**.

### 🔧 Tools Used:

* Python
* Playwright
* VS Code

---

## ▶️ How to Run the Automation Test

```bash
python image_preview_test.py --url "https://www.pixelssuite.com/convert-to-png" --slow-mo-ms 2000
```

---

## 📁 Automation Files

* `image_preview_test.py` – Automation script
* `execution_results.csv` – Test results
* `results/preview_pass.png` – Screenshot proof

---

## ✅ Test Result

* **Preview detected**: True
* **Status**: PASS

---

## 🌐 GitHub Repository

👉 (Paste your GitHub link here)

---

## ⚠️ Notes

* The repository is publicly accessible for evaluation
* All required files are included in the submission
* Automation test was successfully executed

---

## 📌 Conclusion

The system was tested for both functional correctness and usability. Most features worked as expected, while minor usability improvements were identified during testing.

---
