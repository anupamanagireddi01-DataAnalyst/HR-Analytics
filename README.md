# HR-Analytics
An interactive HR Analytics Dashboard built to analyze employee attrition, work-life balance, income distribution, and departmental retention trends using Power BI.



🧭 What is this project about?


People are the heartbeat of any organization — and when they leave, they take knowledge, culture, and momentum with them. This project is my attempt to understand why employees leave, and more importantly, what patterns hint at it before it happens.


The HR Analytics Dashboard is an interactive Power BI report that digs into employee attrition data across departments, income groups, job roles, and promotion histories. It's built for HR teams, people managers, and business leaders who want to move from gut feeling to data-driven retention strategies.


🔍 What questions does it answer?


When I built this, I kept asking myself the kind of questions an HR manager would genuinely lose sleep over:

Which departments are bleeding talent the fastest?

Are employees leaving because they haven't been promoted in years?

Does monthly income actually correlate with who stays and who goes?

Which job roles report the worst work-life balance — and does it show up in attrition?

Is attrition uniform across genders and education backgrounds, or are certain groups more at risk?

The dashboard is designed to answer all of these — interactively, visually, and without needing to run a single SQL query.

📌 Key Metrics at a Glance

MetricValue


👥 Total Employees               50,000


📉 Average Attrition Rate        50.21%


💰 Average Monthly Income        $26,020


🗓️ Average Working Years         20.5 years


🏆 Highest Attr                  Dept.Research & Development   (51.21%)
   
   
📅 Longest Retention Risk        Employees with 21–30 years since promotion







📊 Dashboard Sections Explained :



1. 🔢 KPI Cards

The top row gives you the headline numbers instantly — total headcount, attrition rate, and hourly rate breakdowns. No scrolling, no hunting. Just the numbers that matter.

2. 📅 Attrition Rate by Promotion Gap

This is my favourite chart in the whole dashboard. It answers a question that most orgs ignore: "Are we losing people because we forgot to recognize them?"
Employees who haven't been promoted in 21–30 years show the highest attrition (~51.23%), while recently promoted employees sit just below 50%. The gap isn't massive — but the trend is real.

3. 🍩 Attrition Rate vs Monthly Income

The donut chart breaks down attrition across three income groups — High, Medium, and Low. Spoiler: the distribution is surprisingly even, which tells us income alone isn't the retention silver bullet most people assume it is.

4. 📋 Job Role vs Work-Life Balance (Matrix Table)

A clean matrix showing how each job role scores on work-life balance (rated 1–4). Sales Executives and Manufacturing Directors show notable imbalances. This is the chart you'd show a department head before a team review.

5. 🗂️ Average Working Years by Department (Treemap)

A visual breakdown of tenure across Software, Sales, Support, Hardware, Human Resources, and R&D. Values hover around 20–21 years, suggesting a relatively tenured workforce across the board.

6. 📊 Average Attrition Rate by Department (Bar Chart)

Clean, simple, and honest. R&D leads at 51.21%, followed by Software at 50.54%. Hardware is the most stable at 49.44%. This chart is the starting point for any department-level intervention.


🛠️ Tools & Technologies

ToolPurpose


Power BI Desktop                              :         (Dashboard design & interactivity)



Microsoft Excel / CSV                         :         (Data source & preprocessing)



DAX (Data Analysis Expressions)               :         (Custom measures & calculated columns)



Power Query                                   :          (Data cleaning & transformation)



🎛️ Filters & Interactivity

The dashboard supports dynamic filtering across:


Department — Drill into any specific team

Education Field — See if attrition patterns differ by academic background

Gender — Compare Male vs Female retention trends

All charts update in real time when filters are applied — so you can slice the data any way you need.


💡 What I Learned Building This :


This wasn't just a data exercise — it made me think differently about people problems:


Attrition is rarely about one thing. Income, promotion gaps, work-life balance, and department culture all play a role simultaneously.

Visualizing HR data requires sensitivity. These are real patterns about real people's decisions.

A dashboard is only as good as the questions it makes someone ask. My goal was to spark conversations, not just display numbers.

## Key Insights:


📉 Attrition Rate — 50.21% attrition, 3× above industry average of 15–18%

💸 Monthly Income — Lower income employees show slightly higher tendency to leave

🏢 Department Turnover — R&D (51.21%) and Software (50.54%) have the highest attrition

⏳ Promotion Gap — Employees unpromoted for 21–30 years leave the most

⚖️ Work-Life Balance — ~50% of workforce rates balance as Poor or Fair

👥 Job Role — Sales Executives and Manufacturing Directors report the worst balance scores

📅 Tenure — Avg tenure is 20.5 years yet attrition remains critically high

🏆 Most Stable Dept — Hardware has the lowest attrition at 49.44%

💼 Workforce Size — 50,000 employees, ~25,000 at risk of leaving annually



Power BI Dashboard: ![preview]()





