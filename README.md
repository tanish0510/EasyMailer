# EasyMailer

Easymailer is a platform for creating, monitoring, and analyzing email campaigns. It allows you to customize templates, track delivery, and view real-time performance analytics.

## Table of Contents
- [Set Up a Virtual Environment](#set-up-a-virtual-environment-optional)
- [Install Dependencies](#install-dependencies)
- [Configure API Secrets](#configure-api-secrets)
- [Running the Application](#running-the-application)
- [Usage](#usage)
- [Contributing](#contributing)

## Set Up a Virtual Environment (Optional)
For easier dependency management, it’s recommended to create a virtual environment.

```bash
python -m venv venv
source venv/bin/activate       # On macOS/Linux
venv\Scripts\activate          # On Windows
```
### Install Dependencies
Install the project’s dependencies listed in requirements.txt:

```bash
pip install -r requirements.txt
```

### Configure API Secrets
EasyMailer relies on API keys and other sensitive configurations, which are stored in a secrets.toml file for security. Follow these steps to create the configuration:

## Create the .streamlit directory (if it doesn’t already exist):
```bash
mkdir .streamlit
```
## Create the secrets.toml file inside .streamlit:
```bash
touch .streamlit/secrets.toml
```
## Add your API keys in secrets.toml in the following format:
```bash
[default]
api_key = "your_api_key_here"
```
Replace "your_api_key_here" with your actual API key.

## Running the Application
To launch Emaily, use the following command:

```bash
streamlit run app.py
```
This will start a local Streamlit server, typically at http://localhost:8501, where you can access and interact with the app.

## Usage
Open Emaily: Open your browser and go to http://localhost:8501.
Explore Features: Use the dashboard to create, monitor, and analyze email campaigns.
Manage Templates: Customize email templates according to your requirements.
View Analytics: Get real-time insights and analytics on the performance of your campaigns.
## Contributing
We welcome contributions to make Emaily even better! Here’s how you can contribute:

Fork this repository to your GitHub account.

## Create a new branch for your feature or bug fix:
```bash
git checkout -b feature-name
```
Make your changes and commit them with descriptive messages:

```bash
git commit -m "Add feature or fix description"
```
## Push your changes to your forked repository:
