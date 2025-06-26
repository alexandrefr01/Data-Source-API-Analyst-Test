# Data-Source-API-Analyst-Test
Homework assignment for Data Source API Analyst role


## Objective

Demonstrate hands-on experience with data extraction using the **GitHub REST API**, focusing on:
- Public repositories
- Commits
- File contents


## Repository Structure

Data-Source-API-Analyst-Test/

README.md


Content/

- api_documentation.md

- github_api_report.py

- error_handling.md

- pagination.md


Postman_Collection/

- GitHub API Test.postman_collection.json


Colab_Notebook/

- github_report_colab.ipynb


## How to Use

### Clone the Project

```bash
git clone https://github.com/your-username/Data-Source-API-Analyst-Test.git
cd Data-Source-API-Analyst-Test
```

### Run the Notebook (Google Colab)
- Open the notebook under Colab_Notebook/github_report_colab.ipynb
- Insert your GitHub personal access token
- Run the cells to extract and generate the .csv report


### Technologies Used
- Python 3.10+
- Google Colab
- Postman
- GitHub REST API v3
- requests, pandas
- Token-based authentication


### API Endpoints Used
- GET /users/{user}/repos
- GET /repos/{user}/{repo}/commits
- GET /repos/{user}/{repo}/contents

See full API details in:

- Content/api_documentation.md
- Content/error_handling.md
- Content/pagination.md


### Output
The final dataset is:

- Saved as github_report.csv
- Collected using the Colab Notebook
- Exported Postman collection is available under Postman_Collection/

### Reflection
During this project:

- Explored different authentication and rate limiting scenarios
- Implemented pagination to collect all commits efficiently
- Documented every step with clarity for reuse and transparency
