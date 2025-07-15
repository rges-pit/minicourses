<p align="center">
  <a href="https://github.com/AmberLee2427/microlens-submit">
    <img src="./assets/rges-pit_logo.png" alt="logo" width="300"/>
  </a>
</p>

<h1 align="center"> Microlensing Mini Course (2025) </h1>

Welcome to the repository for the **Microlensing Mini Course**, developed by the [Roman Galactic Exoplanet Surveyor Preparatory Investigations Team (RGES-PIT)](https://rges-pit.org/). This minicourse is designed for select students to participate in Roman Space Telescope-related lectures and activities, with a focus on gravitational microlensing science. The virtual lectures were held in May 2025, and all materials are available here and on the [course landing page](https://rges-pit.org/outreach_mini_landing/).

## 📚 Course Structure

Each chapter contains lecture materials, video recordings, example notebooks, and assignments. You can access the web versions and Colab notebooks via the links below:

### [Chapter 1: Introduction & Historical Background](https://rges-pit.org/_pages/outreach_mini_chapter1.html)
- [Lecture Recording](https://rges-pit.org/outreach_mini_ch1_video/)

### [Chapter 2: Introduction to Microlensing Theory](https://rges-pit.org/_pages/outreach_mini_chapter2.html)
- [Lecture Recording](https://rges-pit.org/outreach_mini_ch2_video/)
- [Lightcurve Example Notebook](https://github.com/rges-pit/rges-pit.github.io/blob/main/docs/assets/notebooks/lightcurve_example.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rges-pit/rges-pit.github.io/blob/main/docs/assets/notebooks/lightcurve_example.ipynb)

### [Chapter 3: Intermediate Microlensing Theory](https://rges-pit.org/_pages/outreach_mini_chapter3.html)
- [Lecture Recording](https://rges-pit.org/outreach_mini_ch3_video/)

### [Chapter 4: Practice Tutorial](https://rges-pit.org/_pages/outreach_mini_chapter4.html)
- [Lecture Recording](https://rges-pit.org/outreach_mini_ch4_video/)
- [Fit a PSPL Event Notebook](https://github.com/rges-pit/rges-pit.github.io/blob/main/docs/assets/notebooks/Day_4_homework_fit_PSPL_event.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rges-pit/rges-pit.github.io/blob/main/docs/assets/notebooks/Day_4_homework_fit_PSPL_event.ipynb)
- [Fit a Gould-Loeb Event Notebook](https://github.com/rges-pit/rges-pit.github.io/blob/main/docs/assets/notebooks/Day4_Gould_Loeb_planetary_event.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rges-pit/rges-pit.github.io/blob/main/docs/assets/notebooks/Day4_Gould_Loeb_planetary_event.ipynb)

### [Chapter 5: Mini Data Challenge](https://rges-pit.org/outreach_mini_ch5/)
- [Lecture Recording](https://rges-pit.org/outreach_mini_ch5_video/)
- [Chapter 5 Notebook](https://github.com/rges-pit/rges-pit.github.io/blob/main/docs/assets/notebooks/Chapter5.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rges-pit/rges-pit.github.io/blob/main/docs/assets/notebooks/Chapter5.ipynb)

### [Glossary](https://rges-pit.org/outreach_mini_glossary/)

## 🚀 How to Use

You can run the Jupyter notebooks in two ways:

- **Google Colab**: Click the "Open in Colab" badge next to each notebook link for a one-click, cloud-based experience (no installation required).
- **Locally**: Clone this repository and install the required dependencies (see below).

## 🛠️ Local Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/rges-pit/minicourses.git
   cd minicourses
   ```
2. (Recommended) Create a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```
3. Install dependencies (see `chapter4/requirements.txt`):
   ```bash
   pip install -r chapter4/requirements.txt
   ```
4. Launch Jupyter Lab or Notebook:
   ```bash
   jupyter lab
   # or
   jupyter notebook
   ```
5. Open the desired notebook from the appropriate chapter directory.

## 👩‍🎓 Audience
This minicourse is intended for students and early-career researchers interested in gravitational microlensing and the Roman Space Telescope mission. All are welcome to explore the materials!

## 🤝 Contributing & Contact
If you have suggestions, corrections, or would like to contribute, please open an issue or pull request.

## 🙏 Acknowledgments
This minicourse was developed by the RGES-PIT as part of its outreach and education efforts. Special thanks to all contributors and participants!
