```mermaid
flowchart TD
    Start["School Starts in 5 minutes, but you aren't sure if you'll make it in time"]
    Start -->|It's probably better to go in late than never| School["Turns out there's an exam today"]
    Start -->|You're already late, what's the point in going?| Stay["You choose to sleep in, the sleep feels nice"]
    School-->|Review the material|Study[The Material is familiar, but you haven't mastered it]
School-->|Don't review the material|Enter[You walk into the exam confident, but you didn't study any of the materials]
    
Enter--> End
Stay --> End["You did not pass the exam."]
Study--> Win[You pass the exam]
```
### The begining of the adventure is labeled "Start" this entity branches into two possibilities, those are labeled "**School**" and "**Stay**."

The reason for these options is because usually people choose to either sleep in or go to school despite being late
* **Stay** leads to **End**
   * Skipping school is very unhealthy, especially in this context where you had an important exam you forgot about
* **School** leads to two possibilities, those being "**Study**" or "**Enter**"
  * **Enter** leads to **End**. Even if you're confident in yourself, you should still study
  * **Study** leads to **Win**. Studying has been proven to improve grades and is important if you want to become a better student
