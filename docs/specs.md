# Workouts Heart Rate Monitor

Build a heart rate monitor for your workouts!

**Maximum heart rate (Tanaka formula):**

```text
hr_max = 208 - 0.7 * AGE
```

**Zones:**

| Zone | Range | Description |
|---|---|---|
| 1 | below 50% | rest |
| 2 | 50%-60% | very light, active recovery |
| 3 | 60%-70% | light, cardio training, improves your general endurance |
| 4 | 70%-80% | moderate, aerobic fitness, improve your efficiency |
| 5 | 80%-90% | hard, raise the anaerobic threshold, improve your speed endurance |
| 6 | above 90% | peak performance, improve your power, only for pros! |

**Goals:**
 - Ask for the user's age
 - Print the hr max
 - Print each training zone in the format 'id, hr min, hr max, description'
 - In loop ask for the current BPM
 - Print the current zone in the format 'id, description'
