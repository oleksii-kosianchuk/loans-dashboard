# Disclaimer
This Power BI dashboard is similar to the one I created during my work in a bank. However, all data has been changed and replaced with the fictitious ones in order to not disclose confidential information.

The original dashboard is connected to the database via SQL queries. However, for the purpose of this demonstration the SQL queries have been omitted and only their results represented in Excel tables are being shown.
# Dashboard Location
Please folow [this link](https://app.powerbi.com/view?r=eyJrIjoiMTkxMzZjMGYtYzRlMS00NmVhLWE3ODktYmI5NzMxOWZjYTg1IiwidCI6IjUwYjA5MzA5LTEzMzgtNDRiZi1hODRkLTc1ZTcxYTgzOWFlNSIsImMiOjl9) to the Microsoft Power BI Report Server where the dashboard has been published and where you may fully interact with it.

When you first open the dashboard, it is recommended that you click on the Hints button <img src="https://github.com/oleksii-kosianchuk/loans-dashboard/blob/main/Hints.png" width="19" height="19"> to see the possible interaction options.
# Overview
The original Power BI dashboard is used by Head of Corporate Banking Department, managers and heads of business centers to explore the dynamics of a loan portfolio, both overall and by clients, with extra focus on a new product - factoring.<br>
<i>In Corporate Banking, the term "client" refers to the legal entity or business group (multiple legal entities that are linked together through shared ownership, activity and management), and it is important to monitor both: proper risk and financial health assesment, to offer similar products with the same tariffs, Anti-Money Laundering and Know Your Client requirements etc.</i>

Important definitions used:
- <b>NPL</b>: non-performing loan, i.e. the loan that hasn't been repaid on schedule and has remained overdue for at least 90 days;
- <b>fully secured loan</b>: loan that is covered by cash, SBLC (standby letter of credit) or PCG (parent company guarantee);
- <b>short-term / long-term loan</b>: loan with the original tenor of up to 365 days / more than 365 days;
- <b>loan margin</b>: client rate minus internal funding rate (which, in simple terms, is the weighted average rate at which the bank pays interests on deposits and other borrowed funds and at which it can deposit funds on the market); for NPLs the margin is negative as borrowers don't pay interests.
