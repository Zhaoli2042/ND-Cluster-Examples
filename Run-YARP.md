1. Download YARP
```
git clone https://github.com/Savoie-Research-Group/yarp
cd yarp/
```
2. Create conda environment
```
module load conda/24.7.1
conda init
conda env create -f env_linux.yaml
conda activate classy-yarp
```
3. Install yarp and other related packages
```
pip install .
pip install pytest
```
4. Run YARP example by running pytest
```
cd pyTEST_Example/
pytest -s
```
