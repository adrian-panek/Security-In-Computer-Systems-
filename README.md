# 🐛 SAST Scanners Comparison

The following project was created during Security In Computer Semester course which I took at Southern Denmark University where I had an opportunity to be an exchange student for a year. Code contains purposefully vulnerable Django application and main of this work was to compare SAST Scanners mentioned in the list below.


## ✨ Technologies

- `Python`
- `Django`
- `SonarCloud`
- `Aikido Security`
- `Snyk`
- `Bandit`
- `Horusec`

- ## ☣️ Containing Vulnerabilities

- SQL Injection
- CSRF Token Bypass
- Secret key exposed in source code
- Cross-Site Scripting

- ## 📍 The Process
After establishing the list of tools, each one was compared against the other participants of the study with regard to the identified vulnerabilities. The full findings of the study can be found in the PDF file attached to this repository.


## 🚦 Running the Project

1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Run development server: `python3 manage.py runserver` (NOT ADVISED)
4. (alternative step) Setup another SAST Scanning tools and verify performance
