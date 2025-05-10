This Python project analyzes global data job postings to uncover salary trends and key skill requirements across roles such as **Data Analyst**, **Data Engineer**, and **Data Scientist**. The dataset is sourced from [HuggingFace Datasets](https://huggingface.co/datasets/lukebarousse/data_jobs).

## Technologies Used

- Python
- pandas
- matplotlib
- datasets (from HuggingFace)

## 💡 Key Insights

### Salary by Country and Role

- **Data Engineers** in **India** and **Germany** enjoy some of the highest median salaries.
- **Data Scientists** earn the most in the **Netherlands**.
- The **United States** offers strong salaries across all three roles.

![Job Posting Across Top 10 Countries](https://github.com/Sofiya-Banmala/Python-Project/blob/main/jobposting.png)

---

### 🧠 Top Skills by Role

| Role | Most In-Demand Skills |
|------|------------------------|
| **Data Analyst** | SQL, Excel, Python, Tableau, Power BI |
| **Data Engineer** | SQL, Python, AWS, Azure, Spark |
| **Data Scientist** | Python, SQL, R, SAS, AWS |

![Top Skills in Data Roles](images/skills_by_role.png)

---

### 💰 Skill Demand vs Salary

- **Python** and **SQL** are highly in-demand and lead to higher salaries.
- **Excel** is commonly listed but linked to lower median salaries.
- Skill combinations like `['python', 'sql']` correlate with high income potential.

![Skill Demand vs Salary](images/skill_vs_salary.png)

---

## 📦 Installation

```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
pip install pandas matplotlib datasets
