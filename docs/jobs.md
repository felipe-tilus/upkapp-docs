# Jobs

**Jobs** are the engine of Upkapp's automation. A Job is a set of recurring rules attached to an Item that answers three critical questions: *What needs to be done?*, *How often should it happen?*, and *Who should do it?*

Instead of manually adding tasks to a calendar every month, you configure a Job **once**, and Upkapp takes care of the rest—automatically generating actionable Work Orders forever.

---

## The Anatomy of a Job 

When you create a Job, you define the parameters that Upkapp will use to monitor your assets and operations. Every Job consists of:

* **Task Details:** A clear title and instructions describing the work that must be performed.
* **Trigger Types:** The rule that determines *when* a new task is due. This can be based on calendar time, usage data via [Meters](meters.md), or both.
* **Scheduling Mode:** Choose between standard calendar logic or Upkapp's advanced [Dynamic Scheduling](dynamic-scheduling.md) engine.
* **cost control:** You can set a cost for the job, and Upkapp will track the cost of each work order.  

## Types of Job Triggers

Upkapp offers complete flexibility by letting you automate tasks using two distinct trigger methods:

### 1. Time-Based Triggers (Calendar)
Triggers a task based on a fixed time interval. 
* *Examples:* Check fire extinguisher validity **every 30 days**; file corporate tax returns **every 3 months**; conduct an executive strategy review **annually**.

### 2. Counter/Meter-Based Triggers (Usage)
Triggers a task based on real-world usage metrics rather than calendar dates. You link the Job to an independent counter (like mileage or hours of operation). 
* *Examples:* Change engine oil **every 5,000 miles**; service an air compressor **every 500 operating hours**. 
* *Note:* Upkapp features a lightning-fast, 5-second quick-update interface specifically designed to keep these counters effortless to maintain.

---

## How to Configure a Job

1.  Navigate to **Items** and select the specific Item you want to set up a task for.
2.  Inside the Item's dashboard, click the **add new Job** button.
3.  **Name the Job:** Use an action-oriented title (e.g., `Deep Clean A/C Filters`).
4.  **Set the Trigger:** * Choose **Time Interval** and input the frequency (days/weeks/months/years), OR
    * Choose **Meter Counter** and select the pre-configured [Meter](meters.md) and target interval.
5.  **Select Scheduling Mode:** Choose between Standard or [Dynamic Scheduling](dynamic-scheduling.md).
6.  **Assign User (Optional):** Select a team member to automatically receive this task.
7.  Click


Job Configured ──> (Auto-Generates) ──> Active Work Order
│
New Work Order <── (Instantly Calculates) <── Marked Complete


When a user completes that active Work Order, Upkapp immediately archives it for your compliance history, evaluates the Job's rules again, and seamlessly schedules the next Work Order. No manual rebuilding required.