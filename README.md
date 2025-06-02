# HW4  -Image Restoration with PromptIR: Rain and Snow Removal

This repository implements an image restoration pipeline using a deep learning model based on the PromptIR architecture. The goal is to recover clean RGB images from inputs degraded by **rain** or **snow** using supervised learning.

---

## 📁 Folder Structure

Your working directory should look like this:

```
HW4/
├── HW4_code.ipynb
├── hw4-data/hw4-realse-dataset/
│   ├── train/
│   │    ├── degraded
│   │    └── clean
│   └── test/
│        └── degraded

```

---

## Set up

### 1. Find the code 

```bash
(https://colab.research.google.com/drive/1o2dy5LYqROhQ_50fB1KZmWrqDUBOxPF2?usp=sharing)
```

### 2. Set up the environment

Use Python 3.9 or higher. You can install the dependencies using pip:

```bash
pip install -r requirements.txt
```


---

## 📂 Where to Change the Path 

You should update the paths inside the notebook to match the path of your folder.

Under "Load the data and change the paths HERE":

```python
# Define paths
hw4_folder_path = "/content/drive/MyDrive/NYCU/HW4" # CHANGE THIS TO YOUR OWN PATH

```

---

## Submission

After running inference, a prediction file is generated:

```
pred.npz
```

---

## 📊 Evaluation

- Here a snapshot of the competion result:
<img width="1157" alt="snapshot" src="https://github.com/user-attachments/assets/3f43d49a-455c-4f41-8e4c-824d2b69284f" />


---

## ✍️ Author

Marie P.  
Student ID: 313551818  
