# hw2.md
## Task Data
| Task | Description | Duration (days) | Predecessor |
|------|--------------|----------------|--------------|
| 1 | Project planning | 1 | - |
| 2 | Task allocation | 4 | 1 |
| 3 | Obtain hardware | 17 | 1 |
| 4 | Program development | 70 | 2 |
| 5 | Install hardware | 10 | 3 |
| 6 | Program testing | 30 | 4 |
| 7 | Write user manual | 25 | 5 |
| 8 | File conversion | 20 | 5 |
| 9 | System testing | 25 | 6 |
| 10 | User training | 20 | 7,8 |
| 11 | User acceptance test | 25 | 9,10 |

## PERT/CPM Diagram
Critical Path: **1 → 2 → 4 → 6 → 9 → 11**  
Total Duration: **155 days**

## Gantt Chart
![Gantt Chart](gantt_chart.png)

## Notes
- Tasks on the critical path have zero slack.
- The project will take a total of 155 days.
