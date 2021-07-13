<p align="center">
    <img src="https://raw.githubusercontent.com/recognai/rubrix/master/docs/images/rubrix_logo.svg" alt="drawing" width="225"/>
</p>

# Rubrix Streamlit demo app
[Rubrix](https://github.com/recognai/rubrix) is a free and open-source tool for tracking, exploring, and labelling data for AI

This demo will show you how can Rubrix be integrated into third-party applications to collect predictions and user feedback. To do this, we are going to use streamlit, an amazing tool to turn Python scripts into beautiful web-apps.

# Installing and launching Rubrix

For the Python library, use the package manager [pip](https://pip.pypa.io/en/stable/) to install **Rubrix**

```bash
pip install rubrix
```

If you have Docker installed, create a folder:

```bash
mkdir rubrix && cd rubrix
```

and launch the docker-contained web app with the following command:

```bash
wget -O docker-compose.yml https://raw.githubusercontent.com/recognai/rubrix/master/docker-compose.yaml && docker-compose up
```

For more details check the [Setup and installation guide](https://docs.rubrix.ml/en/stable/getting_started/setup%26installation.html)

# Web App Dependencies

This demo web app uses a few other Python libraries. You can install all dependencies by running:

```bash
pip install -r requirements.txt
```

# Running the app
After launching **Rubrix**, you can run this Streamlit app from the root directory with

```bash
streamlit run docs/examples/streamlit-live/app.py
```

