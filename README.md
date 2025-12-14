# DMS-Gas-Analysis-Regression-Classification-Models

### Control model — must be executed before running the wort model

When the ZIP archive with measurements is unpacked, open **`control_model.ipynb`** and update the directory paths.

---

## 1. Update the training directories

Replace the following lines:

base_dirs = [
    r"/Users/artempavlov/Documents/Smart Brewery/Measurements/Measurements 11.11.2025",
    r"/Users/artempavlov/Documents/Smart Brewery/Measurements/Measurements 14.11.2025",
    r"/Users/artempavlov/Documents/Smart Brewery/Measurements/Measurements 21.11.2025",
    r"/Users/artempavlov/Documents/Smart Brewery/Measurements/Measurements 28.11.2025"
]
with:

base_dirs = [
    r"/your_path/Measurements/Measurements 11.11.2025",
    r"/your_path/Measurements/Measurements 14.11.2025",
    r"/your_path/Measurements/Measurements 21.11.2025",
    r"/your_path/Measurements/Measurements 28.11.2025"
]

And this part:

base_dir_14 = r"/Users/artempavlov/Documents/Smart Brewery/Measurements/Measurements 14.11.2025"
base_dir_21 = r"/Users/artempavlov/Documents/Smart Brewery/Measurements/Measurements 21.11.2025"
base_dir_28 = r"/Users/artempavlov/Documents/Smart Brewery/Measurements/Measurements 28.11.2025"

with:
base_dir_14 = r"/your_path/Measurements/Measurements 14.11.2025"
base_dir_21 = r"/your_path/Measurements/Measurements 21.11.2025"
base_dir_28 = r"/your_path/Measurements/Measurements 28.11.2025"

And lastly, this part:
output_dir = r"/Users/artempavlov/Documents/Smart Brewery/Boiling_Measurements_clean"

with:
output_dir = r"/your_path/Boiling_Measurements_clean"


