# DMS-Gas-Analysis-Regression-Classification-Models

Control model - run before the wort model

When the ZIP-file with the measurements is unpacked, open control_model.ipynb, and change this lines:
base_dirs = [
    r"/Users/artempavlov/Documents/Smart Brewery/Measurements/Measurements 11.11.2025",
    r"/Users/artempavlov/Documents/Smart Brewery/Measurements/Measurements 14.11.2025",
    r"/Users/artempavlov/Documents/Smart Brewery/Measurements/Measurements 21.11.2025",
    r"/Users/artempavlov/Documents/Smart Brewery/Measurements/Measurements 28.11.2025"
]

base_dir_14 = r"/Users/artempavlov/Documents/Smart Brewery/Measurements/Measurements 14.11.2025"
base_dir_21 = r"/Users/artempavlov/Documents/Smart Brewery/Measurements/Measurements 21.11.2025"
base_dir_28 = r"/Users/artempavlov/Documents/Smart Brewery/Measurements/Measurements 28.11.2025"

output_dir = r"/Users/artempavlov/Documents/Smart Brewery/Boiling_Measurements_clean"

TO:
base_dirs = [
    r"/your_path/Measurements/Measurements 11.11.2025",
    r"/your_path/Measurements/Measurements 14.11.2025",
    r"/your_path/Measurements/Measurements 21.11.2025",
    r"/your_path/Measurements/Measurements 28.11.2025"
]

base_dir_14 = r"/your_path/Measurements/Measurements 14.11.2025"
base_dir_21 = r"/your_path/Measurements/Measurements 21.11.2025"
base_dir_28 = r"/your_path/Measurements/Measurements 28.11.2025"

output_dir = r"/your_path/Boiling_Measurements_clean" <---- This is the name of the folder, where processed boiling data will be saved.

After that you will be able to apply this data to wort model.
