#  Idea: Track My CPU’s "Hottest Streak" Using Kadane’s Algorithm

##  What is this?

A small utility app that tracks the **most intense burst of CPU activity** (hottest streak) over the last 24 hours — using the logic behind **Kadane’s Algorithm**.

The goal is not just to monitor CPU usage, but to **identify spikes of unnecessary computation** — encouraging awareness around personal energy efficiency and digital minimalism.

##  Why This Project?

It started with a thought:
> "What if I could use a classic DSA algorithm — Kadane’s — not just for arrays, but for something happening live on my laptop?"

I realized:
- Many background processes silently hog CPU.
- A huge chunk of our battery drain (and energy use) is invisible.
- If I could **track when my system had its most intense CPU usage streak**, I could start questioning:
  - Was it a code run?
  - A tab explosion?
  - Some inefficient idle background process?

It felt like a way to combine:
-  Computer Science (DSA + OS concepts)
  - Sustainability (energy awareness)
-  Practical Utility (insight into personal computing habits)

## ⚙ How Kadane’s Fits In

Kadane’s Algorithm is perfect for:
> Finding the **maximum sum subarray** (i.e., contiguous segment with the highest “activity”)

In this project:
- Input: Stream of CPU usage logs (e.g. % usage over time)
- Apply Kadane’s on that array
- Output: The **streak (time range)** with the most intense sustained usage

##  Dream Features
- Track and visualize CPU usage streaks hourly or daily
- Alert when usage goes beyond a certain threshold
- Estimate potential energy savings if usage was optimized
- Gamify efficiency: “You saved 15 minutes of peak CPU today!”

##  Deeper Angle

This is more than just a monitor.  
It's a way to **make people think about the invisible cost of computing**.  
As we chase performance, we also need to ask:
> "Could I code lighter? Could I browse smarter?"

##  Why it Matters to Me

It’s not about saving watts — it’s about building **awareness**, using **curiosity**, and making **DSA concepts feel alive** in everyday tools.

If this project can help me — or anyone — *notice* their habits a little more, then it's worth every line of code.

