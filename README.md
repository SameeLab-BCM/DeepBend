# DeepBend


## How to get started
1. Clone our GitHub repository into your local machine and then enter into the cloned directory.
```bash
git clone https://github.com/SameeLab-BCM/DeepBend.git
cd DeepBend
```
2. Make sure you have virtualenv installed.
3. Create virtual environment.
```bash
virtualenv deepbend-env
source deepbend-env/bin/activate
```
4. Install all dependencies.
```bash
pip install -r requirements.txt
```
5. Train the DeepBend model.
```bash
 python src/train.py --model model35 --train-dataset data/dataset_9_train.txt \
  --validation-dataset data/dataset_9_test.txt --hyperparameters parameters/parameter.txt
 ```