# Market-Floor-project
The Market floor will organise task and time management by the user who will use it and help to solve many problems that face in site-shoping strategies


# Market Floor

A browser-based simulation of a market store. Shoppers search the aisles for products on their list, buy them, and pay at a till, while a clerk restocks the shelves. The dashboard shows how stock levels and shelf layout affect sales.

## Project goal

Show how shoppers search for products, how stock changes, and how empty shelves cause lost sales, so a store owner can see the effect of stock and layout on sales.

## Objectives

| # | Objective | How to measure it |
|---|---|---|
| 1 | Show a live animated store with shoppers, shelves, tills, and a clerk | Runs at about 60 frames per second with 12 shoppers |
| 2 | Change shelf stock when shoppers buy and when the clerk restocks | Table numbers match the canvas, and no quantity goes below 0 |
| 3 | Track business results on a dashboard | Shows shoppers in store, served, missed items, sales, and average search time |
| 4 | Let the user control the simulation | Open or close, auto restock, speed, send a shopper, and manual restock all work |
| 5 | Deliver the project with documentation | Report, diagrams, test results, demo, and GitHub link ready by Day 30 |

## Scope

**In scope**
- One store with 8 products, 2 tills, 1 clerk, and up to 12 shoppers
- Shopper behavior: enter, search for items, pick, queue, pay, leave
- Automatic and manual restocking
- Dashboard and a store activity feed
- A layout that works on desktop and phone
- Report, architecture diagram, flowchart, and a demo

**Out of scope**
- Real payments, barcode scanners, or hardware
- Several stores, or accounts for many users
- A server or database (an optional extension only)
- 3D graphics or sound

## Technology

HTML5, CSS3, JavaScript (ES6), and the Canvas API. No installation is needed. It runs in current Chrome, Edge, and Firefox.

## How to run

1. Download or clone this repository.
2. Open `index.html` in your browser.

## Deliverables

1. Source code (HTML, CSS, JavaScript)
2. Requirements list and acceptance criteria
3. Architecture diagram and shopper flowchart
4. Test results table
5. Project report with screenshots
6. A 5-minute demo

## Success criteria

- Runs for 10 minutes with no errors or freezing
- Shoppers never walk through shelves
- Turning auto restock off makes missed items rise
- The sales total matches the sum of all purchases
- Report and demo are finished and uploaded

## Optional goals

- Restock cost and profit figures
- Drag-and-drop shelf layout to test which arrangement shortens search time
- Daily sales report
- A backend with a database to save history

## Timeline

30 days, about 1.5 to 2 hours a day (roughly 50 hours). See `docs/market-floor-30-day-plan.pdf` for the daily task list.
