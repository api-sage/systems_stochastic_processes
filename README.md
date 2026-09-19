# systems_stochastic_processes

## FIFO Single-Server Queue Simulation

Located in [`fifo_single_server_queue/`](./fifo_single_server_queue), this module implements a discrete-event simulation of a single-server, FIFO, work-conserving queue (M/G/1-style), used to study how utilization (ρ) and arrival-process variability jointly affect mean waiting time, mean system time, and mean queue length.

**Highlights:**
- Configurable interarrival processes: Poisson/exponential and uniform (matched-mean, reduced-variance) arrivals.
- Little's Law–based queue-length estimation from simulated waiting times.
- Experiment grid across a range of utilization levels (ρ = 0.5–0.95).
- Comparative analysis of how reduced arrival variability affects congestion — demonstrating that utilization alone does not determine system delay, and that misspecifying arrival variability can materially mislead capacity planning near saturation.

See the notebook for full methodology, figures, and detailed discussion of findings.
