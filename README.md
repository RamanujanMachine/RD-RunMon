# Ramanujan's Dreams Run Monitor

Locally install this repo to use monitor view of the Ramanujan's Dreams system runs.

## Installation

Run: 
```bash
pip install rich
```

## Usage

To connect and run the monitor use:
```bash
python runmon watch runs/latest                                         # stage, progress, CPU/memory per process, pools, events
python runmon watch ~/work/myrun/runs/latest --ssh user@login.cluster   # a run inside a cluster job
python runmon web runs/latest                                           # the same in your browser (http://127.0.0.1:8765/)
python runmon query runs/latest --level WARNING --since 2h              # search the event log
python runmon demo                                                      # try the monitor on a simulated run
```
