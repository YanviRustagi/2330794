# 2330794
For Afford Medical Technologies
# Campus Notification System

## Project Overview

This project is a Campus Notification System developed as part of the Campus Hiring Evaluation.

The system manages and prioritizes notifications related to:

* Placements
* Results
* Events

---

## Stage 1 - Priority Inbox

### Features

* Notification prioritization based on notification type
* Priority order:

```text
Placement > Result > Event
```

* Recency-based sorting
* Top N notifications retrieval

### Files

```text
stage 1/
├── priorityInbox.js
├── Notification_System_Design.md
└── output.png
```

### Algorithm

1. Assign priority score to each notification.
2. Sort notifications by priority.
3. If priorities are equal, sort by timestamp.
4. Return top N notifications.

### Complexity

```text
Time Complexity: O(n log n)
```

### Optimization

For large-scale systems, a Min Heap can be used to maintain the top N notifications efficiently.

---

## Stage 2 - Frontend Application

### Technologies Used

* Next.js
* TypeScript
* Material UI

### Features

* Responsive User Interface
* Notification Cards
* Filter Tabs

  * All
  * Placement
  * Result
  * Event
* Priority Inbox Display

### Project Structure

```text
stage-2/
├── app/
├── public/
├── package.json
├── tsconfig.json
└── ...
```

---

## Installation

Navigate to the stage-2 folder:

```bash
cd stage-2
```

Install dependencies:

```bash
npm install
```

Run the application:

```bash
npm run dev
```

Open:

```text
http://localhost:3000
```

---

## Screenshots

The repository includes screenshots demonstrating:

* Stage 1 output
* Stage 2 frontend UI

---

## Author

Campus Hiring Evaluation Submission
