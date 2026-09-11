# Julia Installation & Setup Guide

Welcome to the exercises! To complete these tutorials, you will need to run Julia code. We recommend running Julia locally on your machine using **Visual Studio Code (VS Code)**. 

This guide will walk you through setting up your environment to run the interactive Jupyter Notebooks (`.ipynb` files) provided for the workshop. 

If you have trouble installing Jupyter notebook, you have two options:
Copy the code into a plain julia file and run it there.
Create an account at JuliaHub, which has a cloud server where you can run Julia code for free.

Please try to complete the guide, and confirm that you can run the first two or three cells. 

---

## Step 1: Install Julia (via JuliaUp)
The best way to install Julia is through the official version manager, **JuliaUp**. 

**For Windows:**
Open your Command Prompt or PowerShell and paste the following:
```powershell
winget install julia -s msstore
```

**For macOS and Linux:**
Open your Terminal and paste the following:
```bash
curl -fsSL https://install.julialang.org | sh
```

---

## Step 2: Install Visual Studio Code
If you don't have it already, download and install **Visual Studio Code**, a free code editor:
👉 [Download VS Code](https://code.visualstudio.com/)

---

## Step 3: Install VS Code Extensions
Open VS Code. On the left-hand sidebar, click on the **Extensions** icon (it looks like four squares). Search for and install the following two extensions:

1. **Julia** (by julialang) - *Provides language support and the Julia engine.*
2. **Jupyter** (by Microsoft) - *Allows you to open and run `.ipynb` notebook files directly in VS Code.*

---

## Step 4: Open and Run the Notebooks!

We have provided a pre-configured Julia environment, so you don't need to install any packages manually. Julia will do it for you when you open the notebook.

1. Download the workshop folder (containing the `.ipynb` files, `Project.toml`, and `Manifest.toml`) to your computer.
2. In VS Code, go to **File > Open Folder...** and select the folder you just downloaded.
3. In the Explorer pane on the left, click on one of the notebooks (e.g., `HGF_workship_CPC_1.ipynb`) to open it.
4. In the top right corner of the notebook window, click on **Select Kernel**.
5. Choose **Jupyter Kernel** -> **Julia (your installed version)**.
6. **Run the First Cell:** The very first code cell in the notebook will look like this:
   ```julia
   using Pkg
   Pkg.activate(".")
   Pkg.instantiate()
   ```
   Click the "Play" button next to this cell (or press `Shift+Enter`). 
   
> [!NOTE]
> **This first cell will take a few minutes to run.** Julia is reading the `Project.toml` file, downloading the exact versions of the packages needed for the tutorial, and precompiling them. Once it finishes, you are ready to complete the rest of the exercises!

<br>
<br>