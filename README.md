# Kenya Employee Salary Analysis

Advanced SQL case study: 22 graded exercises analyzing a 420-person payroll for a fictional Nairobi company, plus a CEO-facing summary.

## Scenario
Acting as People Analyst at Savanna Tech Group, tasked with answering a CEO's pay questions ahead of a board meeting: who earns what, where the money goes, and which departments are over budget.

## Dataset
Two CSV files: an employee register (420 rows: department, job title, county, hire date, salary, age, performance rating) and a departments table (8 rows: head, annual budget, office county, founding year).

## Skills Covered
Filtering and sorting, aggregation (GROUP BY, HAVING), subqueries (including correlated subqueries), window functions (ROW_NUMBER, DENSE_RANK, LAG, running totals), joins, common table expressions (CTEs), conditional aggregation (CASE), anti-joins (NOT EXISTS), and median calculation (PERCENTILE_CONT).

## Key Findings
- Average monthly salary ranges from KES 268,801 (Engineering) to KES 86,120 (Customer Support), a more than threefold gap
- 182 employees (43% of the company) earn above the overall average
- The largest gender pay gap is in Data, where women earn KES 33,575 more per month on average than men; women out-earn men on average in 6 of 8 departments
- Every department is spending more than 100% of its approved annual budget on salaries alone, Sales is most exposed at 226.7% of budget

## Files
- 22 individual query result CSVs, one per graded exercise
- `project-summary.md` — the CEO-facing summary with findings and a recommendation

## Tools
SQL (PostgreSQL), analyzed via Data Lab's SQL workspace
