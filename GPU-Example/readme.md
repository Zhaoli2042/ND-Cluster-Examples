1. run an interactive job
```
qrsh -q gpu -l gpu_card=1 -pe smp 1
```
2. to run the example, load nvhpc compiler
```
module load nvhpc
```
3. compile and run
```
chmod 777 COMPILE
./COMPILE
./nvc_main.x
```
