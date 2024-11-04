```python
class Bio:
    def __init__(self):
        self.name = "Rajbeer Kohli"
        self.role = "Data Engineer"
        self.location = "Melbourne"
        self.company = "Mercedes-Benz Australia Pacific"
        self.experience = {
            "years": 3,
            "skills": [
                "Databricks",
                "Azure",
                "Git",
                "AWS",
                "CI/CD DevOps",
                "Power BI",
                "Terraform",
                "dbt",
                "Airflow",
                "Snowflake",
                "BigQuery"
            ],
            "certifications": [
                "Databricks Data Engineer Associate",
                "Azure Data Engineer Associate",
                "SQL(Advanced) HackerRank",
            ]
        }

# Instantiate and print bio
bio = Bio()
print(bio)

