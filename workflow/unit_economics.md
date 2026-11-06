# Unit economics and rollout assumptions

## Base case (planning estimate, not measured operational data)
- Volume: 500 live classes/week (assignment assumption)
- Manual review: 25 minutes/class
- AI-assisted process including human verification: 7 minutes/class
- Loaded reviewer cost: ₹500/hour
- Usable-clip yield: 20% of classes = 100 clips/week (assumption)

| Metric | Manual | AI-assisted |
|---|---:|---:|
| Hours/week | 500 × 25 / 60 = 208.3 | 500 × 7 / 60 = 58.3 |
| Weekly review labour | ₹104,167 | ₹29,167 |
| Cost/usable clip at 100 clips | ₹1,042 | ₹292 |
| Estimated weekly labour saving | — | ₹75,000 |
| Time saved | — | 150 hours / 72% |

Excludes software costs, setup, final editing, and paid media. Replace assumptions with a two-week time study.

## Sensitivity
If the AI-assisted review takes 10 minutes/class, time is 83.3 hours/week and savings versus 25 minutes/class are 125 hours/week (60%). If yield is 10%, cost per usable clip doubles. Track both median and 90th percentile review time.

## 30/60/90
- Days 1–30: baseline, prompt pilot, editor calibration, full human review; target >=60% acceptance among shortlisted candidates.
- Days 31–60: sheet and notifications, rejection reason taxonomy, geography-specific review; target >=70% acceptance and >=40% time reduction.
- Days 61–90: automate intake/row creation, maintain 100% human review of sensitive material; target >=75% acceptance, >=60% time reduction, 100% consent completion.
Targets are proposed pilot goals, not observed results.
