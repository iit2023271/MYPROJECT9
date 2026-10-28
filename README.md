# Cash Change Calculator (Pay Role Management)

Enter the bill amount and the cash given by the customer, and it works out the minimum number of notes to return as change.


## Features

- Bill amount and cash-given inputs
- Greedy note breakdown across **2000 / 500 / 100 / 20 / 10 / 5 / 1** notes
- Results shown in a "Return Change" table
- Error messages for a negative bill or cash less than the bill

## Tech Stack

- HTML
- CSS
- JavaScript (single self-contained file)

## How to Run

Just open `index.html` in any browser. No build step, no server needed.

```bash
# or serve it locally
python3 -m http.server
# then open http://localhost:8000
```

## Example

Bill ₹500, cash ₹2000 → change ₹1500, returned as **3 × ₹500 notes** (as shown in the screenshot).
