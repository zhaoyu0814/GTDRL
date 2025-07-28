# Game-Theoretic-Deep-Reinforcement-Learning

This is the code of paper, named "Joint Task Offloading and Resource Optimization in NOMA-based Vehicular Edge Computing: A Game-Theoretic DRL Approach", and the proposed solution and comparison algorithms are implemented.

## Environment
The conda environment file is located in `environment.yml`.    
It can be used to create the environment by:    
```bash
conda env create -f environment.yml
```

## File Structure

### Main Function
The main() function of the repo is located in `Experiment/experiment.py`.

### Algorithms

- Multi-agent distributed distributional deep deterministic policy gradient (MAD4PG): `Experiment/run_mad4pg.py`
- Multi-agent deep deterministic policy gradient (MADDPG): `Experiment/run_maddpg.py`
- Distributed distributional deep deterministic policy gradient (D4PG): `Experiment/run_d4pg.py`
- Optimal resource allocation and task local processing only (ORL): `Experiment/run_optres_local.py`
- Optimal resource allocation and task migration only (ORM): `Experiment/run_optres_edge.py`

### Didi Dataset

The vehicular trajectories for November 16, 2016, generated in Chengdu and extracted from the Didi GAIA Open Data Set, can be found on [Vehicular-Trajectories-Processing-for-Didi-Open-Data](在上一层文件夹中).
