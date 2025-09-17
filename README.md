## Instances
Instance 1

|   |   |   |   |
|---|---|---|---|
| 1 | · | · | 4 |
| · | 3 | · | · |
| · | · | 2 | · |
| · | · | · | 3 |

Instance 2

|   |   |   |   |
|---|---|---|---|
| · | · | 2 | · |
| 4 | · | · | · |
| · | 4 | · | · |
| · | · | · | 1 |

Instance 3

|   |   |   |   |
|---|---|---|---|
| 2 | · | · | 4 |
| · | 4 | · | · |
| · | · | 4 | 1 |
| 4 | · | · | · |



## Quick start
```bash
# (Optional) create a venv
python -m venv .venv && source .venv/bin/activate

# Solve an instance
python run_csp.py examples/futoshiki4x4.csp

# Try another
python run_csp.py examples/tiny_schedule.csp
python run_csp.py examples/send_more_money.csp
```