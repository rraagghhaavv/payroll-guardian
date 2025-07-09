# Payroll Guardian 🧾🛡️

A complete Python-based payroll compliance tool that:

✅ Validates salary data from Excel  
✅ Flags PAN, PF, TDS, HRA, and DOJ issues  
✅ Highlights non-compliant rows in red  
✅ Generates summary reports in PDF and TXT  
✅ Emails final outputs automatically

---

## 💼 Features

- 🧮 Excel parsing with `pandas`
- ✅ Rule-based validation: PAN, PF ≥ 12%, TDS, DOJ, HRA limits
- 🟥 Highlighting rows using `openpyxl`
- 📄 PDF report using `reportlab`
- 📧 SMTP email integration

---

## 📂 Files

| File | Purpose |
|------|---------|
| `payroll_guardian_colored.xlsx` | Final validated sheet with highlights |
| `payroll_guardian_summary.pdf` | Professional summary report |
| `payroll_guardian_summary.txt` | Text version for logs or backups |
| `project5.py` | Complete Python script |

---

## 🛠️ Tech Stack

- Python 3.10+
- `pandas`, `openpyxl`, `reportlab`
- Gmail SMTP (App Password)

---

## 🚀 Usage

```bash
python project5.py
# payroll-guardian
A Python-based payroll compliance automation tool with Excel validations, PDF reports, and email integration.
