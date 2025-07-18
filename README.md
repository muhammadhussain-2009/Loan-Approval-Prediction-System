<div id="top">

<!-- HEADER STYLE: CLASSIC -->
<div align="center">


# LOAN-APPROVAL-PREDICTION-SYSTEM

<em>Empowering Smarter Loans with Instant Decision Power</em>

<!-- BADGES -->
<img src="https://img.shields.io/github/license/muhammadhussain-2009/Loan-Approval-Prediction-System?style=flat&logo=opensourceinitiative&logoColor=white&color=0080ff" alt="license">
<img src="https://img.shields.io/github/last-commit/muhammadhussain-2009/Loan-Approval-Prediction-System?style=flat&logo=git&logoColor=white&color=0080ff" alt="last-commit">
<img src="https://img.shields.io/github/languages/top/muhammadhussain-2009/Loan-Approval-Prediction-System?style=flat&color=0080ff" alt="repo-top-language">
<img src="https://img.shields.io/github/languages/count/muhammadhussain-2009/Loan-Approval-Prediction-System?style=flat&color=0080ff" alt="repo-language-count">

<em>Built with the tools and technologies:Python, FASTAPI, POSTMAN, Uvicorn, Joblib, Numpy, Pandas, Scikit-Learn, Jupyter Notebook, VSCode </em>

<img src="https://img.shields.io/badge/Markdown-000000.svg?style=flat&logo=Markdown&logoColor=white" alt="Markdown">
<img src="https://img.shields.io/badge/Python-3776AB.svg?style=flat&logo=Python&logoColor=white" alt="Python">

</div>
<br>

---

## Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
    - [Usage](#usage)
- [Features](#features)
- [Project Structure](#project-structure)
    - [Project Index](#project-index)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

Loan-Approval-Prediction-System is an open-source tool designed to streamline the development and deployment of machine learning models for predicting loan approval outcomes. It combines data science workflows with a ready-to-use API, enabling seamless integration into financial decision-making systems.

**Why Loan-Approval-Prediction-System?**

This project simplifies building reliable loan approval models. The core features include:

- 🧪 **Notebook-based ML Development:** An interactive Jupyter Notebook guides you through data exploration, feature engineering, visualization, and model training.
- ⚡ **Real-time API Endpoint:** `app.py` provides a fast, scalable API for instant loan approval predictions.
- 🔍 **Data Insights & Visualization:** Built-in tools help analyze and visualize data for better model accuracy.
- 🔧 **Easy Integration:** Designed for smooth incorporation into larger applications for automated decision workflows.
- 📜 **Open-Source License:** Encourages collaboration, customization, and community-driven improvements.

---

## Features

|      | Component       | Details                                                                                     |
| :--- | :-------------- | :------------------------------------------------------------------------------------------ |
| ⚙️  | **Architecture**  | <ul><li>Modular ML pipeline with data ingestion, preprocessing, model training, and evaluation</li><li>Separation of concerns via distinct Python scripts/notebooks</li></ul> |
| 🔩 | **Code Quality**  | <ul><li>Consistent Python coding style, likely adhering to PEP 8</li><li>Use of Jupyter notebooks for exploratory analysis and documentation</li></ul> |
| 📄 | **Documentation** | <ul><li>Basic README with project overview</li><li>Inline comments within code/notebooks</li></ul> |
| 🔌 | **Integrations**  | <ul><li>Uses Python libraries such as `scikit-learn`, `pandas`, `numpy` for ML and data processing</li><li>Potential integration with Jupyter notebooks for visualization</li></ul> |
| 🧩 | **Modularity**    | <ul><li>Code split into multiple scripts/notebooks for data processing, modeling, evaluation</li><li>Functions and classes encapsulate key functionalities</li></ul> |
| 🧪 | **Testing**       | <ul><li>Limited explicit testing; possible use of notebooks for validation</li><li>No mention of automated test suites or frameworks</li></ul> |
| ⚡️  | **Performance**   | <ul><li>Uses efficient data handling with pandas/numpy</li><li>Model training likely optimized for small to medium datasets</li></ul> |
| 🛡️ | **Security**      | <ul><li>No explicit security features or measures observed</li><li>Potential vulnerabilities in data handling or deployment not addressed</li></ul> |
| 📦 | **Dependencies**  | <ul><li>Key dependencies include `markdown`, `python`, `jupyternotebook`, `license`</li><li>Minimal external dependencies, primarily data science libraries</li></ul> |

---

## Project Structure

```sh
└── Loan-Approval-Prediction-System/
    ├── LICENSE 
    ├── README.md #Documentation and Instruction For Project
    ├── Loan_Apporval_Predictor.ipynb #Jupyter Notebook with code to build ML Model
    └── requirements.txt #Dependencies for FrontEnd of Project 
    ├── app.py #FASTAPI Client 
    ├── loan_data.csv #Dataset For The Project
    ├── loan_status_predictor.pkl #Saved Model Checkpoints
    └── vector.pkl #Saved Scaled Data 
```

---

### Project Index

<details open>
	<summary><b><code>LOAN-APPROVAL-PREDICTION-SYSTEM/</code></b></summary>
	<!-- __root__ Submodule -->
	<details>
		<summary><b>__root__</b></summary>
		<blockquote>
			<div class='directory-path' style='padding: 8px 0; color: #666;'>
				<code><b>⦿ __root__</b></code>
			<table style='width: 100%; border-collapse: collapse;'>
			<thead>
				<tr style='background-color: #f8f9fa;'>
					<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
					<th style='text-align: left; padding: 8px;'>Summary</th>
				</tr>
			</thead>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/muhammadhussain-2009/Loan-Approval-Prediction-System/blob/master/Loan_Approval_Predictor.ipynb'>Loan_Approval_Predictor.ipynb</a></b></td>
					<td style='padding: 8px;'>- Loan Approval PredictorThis Jupyter Notebook serves as the core component for developing a machine learning model to predict loan approval outcomes<br>- It orchestrates the entire data science workflow—from importing and exploring the dataset, performing feature engineering and visualization, to training and evaluating predictive models<br>- The notebooks primary purpose is to facilitate the creation of an accurate, reliable loan approval prediction system that can be integrated into the broader application architecture for automated decision-making.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/muhammadhussain-2009/Loan-Approval-Prediction-System/blob/master/LICENSE'>LICENSE</a></b></td>
					<td style='padding: 8px;'>- Provides the licensing terms for the project, establishing legal permissions and restrictions for software use, distribution, and modification within the overall architecture<br>- Ensures clarity on rights granted to users and contributors, supporting open-source collaboration and safeguarding intellectual property across the codebase.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/muhammadhussain-2009/Loan-Approval-Prediction-System/blob/master/app.py'>app.py</a></b></td>
					<td style='padding: 8px;'>- Provides an API endpoint for predicting loan approval status based on applicant data<br>- It leverages a pre-trained machine learning model to assess loan applications, enabling automated decision-making within the overall system architecture<br>- This component integrates data preprocessing, model inference, and response generation to facilitate real-time loan eligibility evaluations.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/muhammadhussain-2009/Loan-Approval-Prediction-System/blob/master/README.md'>README.md</a></b></td>
					<td style='padding: 8px;'>- Provides an overview of the Loan Approval Prediction System, emphasizing its role in utilizing machine learning techniques to forecast loan approval outcomes based on customer characteristics<br>- The document highlights the systems purpose within the broader architecture, guiding users on its functionality and integration points to facilitate understanding and effective deployment of the predictive model within the project.</td>
				</tr>
			</table>
		</blockquote>
	</details>
</details>

---

## Getting Started

### Prerequisites

This project requires the following dependencies:

- **Programming Language:** Python, VSCode, FASTAPI, Postman, Uvicorn, Numpy, Pandas, Scikit-Learn, Matplotlib, Seaborn, JupyterNotebook

### Installation

Build Loan-Approval-Prediction-System from the source and install dependencies:

1. **Clone the repository:**

    ```sh
    ❯ git clone https://github.com/muhammadhussain-2009/Loan-Approval-Prediction-System
    ```

2. **Navigate to the project directory:**

    ```sh
    ❯ cd Loan-Approval-Prediction-System
    ```

3. **Install the dependencies:**

   ```sh
    ❯ pip intall -r requirements.txt
    ```

### Usage

Run the project with following command. This provides an Asynchronous Server Getaway Interface and access to Local host to make requests to a functional API client: 

uvicorn app:app --reload
 
## Roadmap

- [ ] **`Task 1`**: Load Dataset with Pandas, Data Cleaning, Inpection, Exploratory Data Analysis and Data Visualisation 
- [ ] **`Task 2`**: Feature Engineering, Build Model, Test and Evaluate Various ML Algorithms, do some hyper paramter tuning 
- [ ] **`Task 3`**: Save Model Checkpoints and scaled data via Joblib.
- [ ] **`Task 4`**: Build FASTAPI Client. Define simple API end point to make POST requests and to recieve input data 
- [ ] **`Task 5`**: Use Uvicorn command for ASGI and to get local host link
- [ ] **`Task 6`**: Create new project with POSTMAN (from website): Configure the client and send requests to API endpoint with sample input data. Check reliability of results

---

## Contributing

- **💬 [Join the Discussions](https://github.com/muhammadhussain-2009/Loan-Approval-Prediction-System/discussions)**: Share your insights, provide feedback, or ask questions.
- **🐛 [Report Issues](https://github.com/muhammadhussain-2009/Loan-Approval-Prediction-System/issues)**: Submit bugs found or log feature requests for the `Loan-Approval-Prediction-System` project.
- **💡 [Submit Pull Requests](https://github.com/muhammadhussain-2009/Loan-Approval-Prediction-System/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.

<details closed>
<summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your github account.
2. **Clone Locally**: Clone the forked repository to your local machine using a git client.
   ```sh
   git clone https://github.com/muhammadhussain-2009/Loan-Approval-Prediction-System
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to github**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.
8. **Review**: Once your PR is reviewed and approved, it will be merged into the main branch. Congratulations on your contribution!
</details>

<details closed>
<summary>Contributor Graph</summary>
<br>
<p align="left">
   <a href="https://github.com{/muhammadhussain-2009/Loan-Approval-Prediction-System/}graphs/contributors">
      <img src="https://contrib.rocks/image?repo=muhammadhussain-2009/Loan-Approval-Prediction-System">
   </a>
</p>
</details>

---

## License

Loan-approval-prediction-system is protected under the [LICENSE](https://choosealicense.com/licenses) License. For more details, refer to the [LICENSE](https://choosealicense.com/licenses/) file.

---

<div align="left"><a href="#top">⬆ Return</a></div>

---

