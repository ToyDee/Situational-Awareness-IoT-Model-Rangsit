# IoT-Based Agent Model for Situational Awareness in the Workplace

An agent-based model that simulates workplace situational awareness, extending Arbaoui et al. (2022) by adding real-time IoT sensor data (Fire, Smoke, Gas) to drive transitions between **Relaxed**, **Focused**, **High Alertness**, and **Tuned-Out** states.

## Files

- `Focused.ipynb` / `Relax.ipynb` / `High.ipynb` / `Tuned_out.ipynb` — simulation notebooks for each awareness state
- `Senior_Project_Journal.pdf` — full project paper (methodology, equations, results)

## Summary

Simulated in Python (NumPy) over 800 time steps, comparing baseline vs. IoT-enhanced scenarios under sustained hazard input (Fire = 0.8, Smoke = 0.5, Gas = 0.2). The IoT-enhanced model reaches High Alertness almost twice as fast as the baseline, with a measurable trade-off: increased Tuned-Out risk from sensor overstimulation.

| Awareness Level | Before IoT | After IoT |
|---|---|---|
| Relaxed | 0.067 | 0.118 |
| Focused | 0.616 | 0.665 |
| High Alertness | 0.302 | 0.636 |
| Tuned-Out | 0.161 | 0.370 |

## Authors

Thi Ha La Min, Htet Myat Tun, Aung Thu Htet — Rangsit University
