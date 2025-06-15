# Lambda Task Scheduler

The Lambda Task Scheduler is a lightweight JavaScript utility that demonstrates how to schedule and execute tasks using functional programming principles, particularly JavaScript's `setTimeout`, `setInterval`, and lambda (arrow function) syntax.

This is Farheen’s first open source contribution using Lambda expressions and time-based logic.

## Features

- Schedule one-time or recurring tasks
- Use lambda expressions to define clean and concise task logic
- Simple, readable architecture with functional patterns
- Time-based execution using JavaScript timers

## Usage

```js
// Schedule a one-time task
scheduleTask(() => {
  console.log("One-time task executed.");
}, 3000);

// Schedule a recurring task
scheduleRecurringTask(() => {
  console.log("Recurring task running every 5 seconds.");
}, 5000);
