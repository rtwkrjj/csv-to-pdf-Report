# csv-to-pdf-Report
Analyze employee salary data from a CSV file and export a styled PDF summary report using pandas and ReportLab.
Employee Salary Report Generator

This project is a Python-based tool that reads employee data from a CSV file, performs salary analysis by department, generates insightful visualizations, and creates a professional PDF report.

🚀 Features

📂 Read data from CSV

📊 Analyze salary statistics (count, average, min, max)

🖼️ Generate visualizations with Matplotlib and Seaborn:

Bar chart (Average Salary per Department)

Box plot (Salary Distribution)

Pie chart (Employee Distribution)

Histogram (Salary Spread)

Scatter plot (Salary vs Age, optional)

📝 Generate a formatted PDF report using ReportLab

📁 Sample CSV Format

Ensure your CSV file follows this structure:

Name,Age,Department,Salary
John Doe,29,Engineering,70000
Jane Smith,34,HR,60000
...

🛠️ Dependencies

Install these with pip:

pip install pandas matplotlib seaborn reportlab

📄 How to Use

Run the Script:

Use the script in a local Python environment or Google Colab.

Upload your CSV:

If using Colab, use files.upload() to import your CSV interactively.

Generate PDF and Visuals:

The script will create both plots and a report.pdf with summary stats.

📈 Sample Visualizations

Visualizations include department-wise summaries and salary distribution insights.
These help in understanding employee compensation patterns at a glance.

📤 Output

report.pdf — A formatted PDF with department salary stats

*.png — Optional saved plots if you use plt.savefig()

🤝 Contributing

Pull requests and suggestions are welcome. For major changes, open an issue first.

📄 License

This project is open-source and free to use under the MIT License.

Happy Reporting! 📊📄

