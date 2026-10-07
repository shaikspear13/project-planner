# Assessment Project Planner

A browser-based planning tool for assessment and development centre projects. Pick what the project includes, and it builds the full delivery plan, a Gantt chart and a client-ready Excel file in seconds.

**Live demo:** `https://<your-username>.github.io/<repo-name>/`

## The problem

Assessment projects are planned in spreadsheets that are copied and edited by hand for every client. Dates are typed in or chained to fixed rows, so adding a task or changing scope breaks the timeline. When a client asks for a faster delivery date, there is no quick way to see how much compression is needed or where it can come from.

## What it does

- **Scope set-up:** choose online assessments, 360, development centre (in-person or virtual), competency framework creation, leadership interviews, branding and 1:1 feedback. Only the relevant tasks are switched on.
- **Dependency-driven dates:** every task starts after the task(s) it depends on, skipping weekends and holidays. Change one duration and everything after it moves.
- **DC dates up front:** enter the DC start date and number of days; the tool shows the earliest possible start and flags a date that is too early.
- **Compression check:** enter the client's target date to see the standard finish, the compression needed (working days and %), and whether the revised plan meets it.
- **Reduced TAT:** shorten individual tasks and see the days saved.
- **Gantt chart:** weekly view coloured by owner (delivery team, client, joint), with milestones and today's date.
- **Client view:** only client-facing tasks, ready to copy or export.
- **Excel export:** one file with an internal view (all columns) and a client view (task, owner, dates, TAT, status, remarks), each with a Gantt.
- **Add and reorder tasks:** add tasks to any section and move them up or down.

## How to use

Open the page, set the start date and scope, then work in the Plan, Gantt and Client view tabs. Edits are saved in your own browser only. Nothing is sent to a server.

## Notes

- Task list and turnaround times are an illustrative template, not any organisation's actual process.
- Single HTML file, no build step. The Excel export loads ExcelJS from a CDN when the button is clicked.

## Author

Moina Shaik
