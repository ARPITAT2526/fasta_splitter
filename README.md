# FASTA Splitter Script

This Python script reads multiple sheets from an Excel file containing FASTA-format sequences, splits each sequence, and saves them into individual `.fasta` files — organized by sheet name.

---

## 📂 How It Works

- Takes an Excel file like `boladatabase.xlsx` with sheets named `DRB3`, `DQA`, etc.
- Each sheet contains FASTA data (headers starting with `>`).
- Splits and writes each sequence to a separate `.fasta` file in its respective folder.

---

## 🧪 Example Excel Structure

| Column A                        |
|--------------------------------|
| >Header1                       |
| ACTGACGTAGCATGCA               |
| >Header2                       |
| TGCACTGACTGACTGA               |

---

## ✅ Usage

### 1. Place your Excel file:
Save your Excel file in the appropriate path (update in the script):

```python
excel_path = '/path/to/boladatabase.xlsx'
