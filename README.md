# Belay
Belay: your next slack is not slack but belay ;)
# Run Instruction
## 1 create conda environment for python
Skip this if you are sure you have the correct environment without the help of conda.
### 1.1 create a conda environment with python 3.11.2
```
conda create -n belay python=3.11.2
```
### 1.2 activate the environment
```
conda activate belay
```
## 2 install the requirements
```
python -m pip install -r requirements.txt
```
## 3 Start the backend server
⚠️: **the backend server must be started on port 5000**
```
conda activate belay
cd belay
flask run --reload --port=5000
```
## 3 Access Belay at http://127.0.0.1:5000
Have fun!