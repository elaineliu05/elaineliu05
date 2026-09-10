**1. Which of our open ML Research Engineer roles are you interested in, in order?**

General, model eval, then applied research. I'm most interested in taking

**2. Describe an ML idea you were initially excited about but later decided was wrong or unimportant.**

I was recently tested using time-series foundation models for forecasting-based anomaly detection. But benchmarking showed they performed comparably to a 1D CNN with ~1,000× fewer parameters. Investigating the predictions showed that our high-frequency, volatile telemetry made short-horizon forecasting inherently difficult, which taught me to prioritize empirical evidence over the novelty of new models.

**3. Describe a time when you embarked on a sidequest / took initiative outside your core job responsibilities.**

At MBARI, I built a pipeline to benchmark object detection and tracking on deep-sea video. I took a sidequest to turn it into an end-to-end video analysis platform so non-technical users could explore footage without understanding ML metrics. I was driven by seeing that a useful research tool could have much broader value if it were accessible.

**4. How could better accuracy fail to translate into more useful forecasts for a weather model?**

A model can have better average accuracy while producing less useful forecasts. This is because accuracy can also hide errors in timing, spatial structure, or uncertainty that matter more to downstream decisions. For example, it may improve easy, common conditions while performing poorly on rare but important events, or be poorly calibrated and overconfident.

**5. Describe a time you changed how you use LLMs in your work — switching models, tools, or workflows. What did you observe that prompted the change?**

I initially used LLMs primarily for code generation, but noticed they often made unstated assumptions about my data or environment. Now, I use them more as a reasoning partner: I ask them to break down approaches, identify tradeoffs, and surface assumptions before writing code. This keeps me in control while still making iteration much faster.
