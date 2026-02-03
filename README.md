conda create -p <env_name> python==3.10 -y

.....
conda activate <path of the env>

...
pip install -r requirements.txt

...

# git commands

git init
....

git add .
....

git commit -m "< first meggsecommit>"

...
git push 
git push -u origin main

....
to install steup.py write 
( pip install -e .)


# if you won't see env1 kernal to attach notebook use this steps below
....
conda activate C:\Users\parsi\Downloads\Document_portal\env1
.....
pip install ipykernel
.....
STEP 3 — Register env1 as a kernel for Jupyter

Run inside env1:
python -m ipykernel install --user --name env1 --display-name "Document Portal (env1)"
....
🧪 STEP 4 — Verify registration
jupyter kernelspec list
.....
You should now see something like:
env1     C:\Users\parsi\AppData\Roaming\jupyter\kernels\env1
.....
STEP 5 — Open Jupyter Notebook and switch kernel

In Jupyter:

Kernel → Change Kernel → Document Portal (env1)