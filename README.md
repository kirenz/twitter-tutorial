# Twitter tutorial

In this tutorial you will learn how to setup Twitter to obtain tweets using the Python library tweepy.

---


## Step 1: Twitter setup

- Follow the instructions in the file [twitter-setup.md](twitter-setup.md).

---

## Step 2: Create Anaconda environment


> On *Windows* open the Start menu and open the "Anaconda Command Prompt". 


> On *macOS*: Open your terminal 


Create a new Anaconda environment (we call it `twitter`):

```bash
conda create -n twitter python=3.11 pip --y
```


Activate the environment: 

```
conda activate twitter
```

Install some packages:

```bash
pip install tweepy pandas altair jupyter ipykernel
```

<!-- - For Mac-users: If you get this error: `zsh: no matches found: tweepy[async]` try this code instead: 



```bash
pip install 'tweepy[async]' pandas altair jupyter ipykernel
```

-->

## Step 3: Download repo and open VS Code

- Click on the green "Code" button at the top of this page

- Choose `Download ZIP` 

- On your machine: unzip `twitter-tutorial` in a folder of your choice.

- Start VS Code and open the folder `twitter-tutorial` with "Open Folder":


![](/img/vscode.png)

- This opens the VS Code Explorer und you should see all files in `twitter-tutorial`

- Proceed with the next step

---


## Step 4: Insert Twitter keys in keys.py


- In your VS Code Explorer, open the file `keys.py`


- Insert your Twitter keys in the Python file [`keys.py`](keys.py)


---

## Step 5: Use tweepy to obtain some tweets

- In your VS Code Explorer, open the file [`tweepy-setup.ipynb`](tweepy-setup.ipynb)


---
