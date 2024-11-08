# Midway3-Examples

To get an interactive session:
```
salloc --nodes=1 --time=01:00:00 --partition=amd --account pi-rstevens
```
To get an interactive session with 10 nodes:
```
salloc --nodes=10 --time=01:00:00 --partition=amd --account pi-rstevens

```
module load mpich
mpiexec -n 10 -ppn 1 hostname
```
midway3-0516.rcc.local
midway3-0519.rcc.local
midway3-0520.rcc.local
midway3-0522.rcc.local
midway3-0524.rcc.local
midway3-0525.rcc.local
midway3-0517.rcc.local
midway3-0521.rcc.local
midway3-0523.rcc.local
midway3-0518.rcc.local
```

```
salloc --nodes=10 --time=01:00:00 --partition=amd --account pi-rstevens
srun -n 10 hostname
srun -n 10  python ./test.py

