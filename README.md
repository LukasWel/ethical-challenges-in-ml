# Ethical Challenges in Machine Learning

This repository contains the full text of my master's thesis *"Ethical Challenges in Machine Learning: Bias, Fairness, and Self-Fulfilling Predictions"*, along with the accompanying interactive Jupyter notebook and relevant datasets.

## Repository Structure

- `Thesis/`: Final thesis in PDF format
- `Fairness_Notebook/`: All materials related to the interactive notebook
  - `User_Guide/`: PDF user guide for navigating and using the notebook
  - `Notebooks/`: All Jupyter notebooks and the images used within them
  - `Data/`: Preprocessed and raw datasets used in the notebook

## Usage Notes

To run the notebook effectively, it is recommended to download the repository and maintain the **same folder structure** locally.  
File paths in the notebooks need to be adjusted depending on your local setup.

Please make sure to merge the contents of `UTKFace 1` & `UTKFace 2` into a **single folder named `UTKFace`** inside  
`Fairness_Notebook/Data/GenderClassification_Study/` for the notebooks to work correctly.

> **Note on Python version**: Notebook 5 uses TensorFlow, which is officially supported only for Python versions **3.8 to 3.11**.
> Please ensure you are using a compatible Python version when running this notebook.

---

## Referenced Datasets and Resources

- **FairFace dataset and labels**  
  https://github.com/joojs/fairface?tab=readme-ov-file

- **UTKFace dataset**  
  https://www.kaggle.com/datasets/jangedoo/utkface-new

- **UTKFace Adjusted**  
  A custom selection derived from the original UTKFace dataset.

- **Student Dataset**  
  https://archive.ics.uci.edu/dataset/697/predict+students+dropout+and+academic+success

- **Berlin Crime Data (2018–2023)**  
  https://www.berlin.de/polizei/service/kriminalitaetsatlas/  
  *Note: The version included in this repository has been filtered to include only sub-district-level data, yearly frequencies (2018–2023), and selected relevant features.*

- **LOR Shapefiles (Berlin Sub-districts)**  
  https://www.berlin.de/sen/sbw/stadtdaten/stadtwissen/sozialraumorientierteplanungsgrundlagen/lebensweltlich-orientierte-raeume/

- **OpenCV Gender Classification Models**  
  - Prototxt: https://github.com/spiorf/deepdream/blob/master/models/cnn_age_gender_models_and_data.0.0.2/deploy_gender.prototxt  
  - Caffe Model: https://github.com/smahesh29/Gender-and-Age-Detection/blob/master/gender_net.caffemodel

---

## Disclaimer

This repository is intended for academic use only. All datasets and models are used in accordance with their respective licenses.

## License

This repository and all associated materials are licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).  
Please attribute any reuse to **Lukas Welikat** and link to this repository.
