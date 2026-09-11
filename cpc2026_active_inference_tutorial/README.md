# Active Inference Workshop – Computational Psychiatry Course 2026

Welcome to the repository for the **Active Inference Workshop** at the 2026 Computational Psychiatry Course.  
This repo contains all the materials you will need to follow along with the tutorial sessions.

---

## Installation Guide

Please complete these steps **before** the Practical Tutorial Session.

### 1. Clone or Download the Repository

You can either **clone this repository** with Git or **download it as a ZIP file**.

**Option A — Clone with Git (recommended)**

Cloning makes it easy to pull any last-minute updates before the session.

1. Install Git if you don't already have it ([git-scm.com/downloads](https://git-scm.com/downloads)).
2. On the repository's GitHub page, click the green **Code** button and copy the **HTTPS** URL.
3. Open a terminal (Terminal on macOS/Linux, Git Bash or Command Prompt on Windows), navigate to the folder where you want the materials, and run:
   ```bash
   git clone <paste-the-HTTPS-URL-here>
   ```
4. To grab later updates, `cd` into the folder and run `git pull`.

**Option B — Download the ZIP**

1. On the repository's GitHub page, click the green **Code** button, then choose **Download ZIP**.
2. Locate the downloaded `.zip` file (usually in your Downloads folder) and unzip it.
3. Move the uncompressed folder to your preferred directory.

### 2. Install MATLAB

Make sure you install MATLAB and that you can open and run it:  
👉 [https://www.mathworks.com/products/get-matlab.html](https://www.mathworks.com/products/get-matlab.html)

### 3. Install SPM12 or SPM25

The tutorial scripts require SPM. They are **compatible with either SPM12 or SPM25**, so if you run into errors with one version, try the other.

1. Download SPM from the official download page:  
   👉 [https://www.fil.ion.ucl.ac.uk/spm/software/download/](https://www.fil.ion.ucl.ac.uk/spm/software/download/)
2. Place the uncompressed `spm12` (or `spm25`) folder in your preferred directory.
3. Open MATLAB and add the main SPM folder **and the `toolbox\DEM\` subfolder** to your search path. You can do this from the **Current Folder** window (the column on the left): navigate to the folder in the MATLAB file explorer, right-click it, and select **Add to Path**. Do **not** add all subfolders — only the main SPM folder and `DEM`.

### 4. Confirm the Installation Works

1. In the MATLAB **Command Window**, type `spm` and press Enter. The SPM GUI should open.
2. Do the same with `DEM` — type `DEM` and press Enter. The DEM GUI should open.
3. In the DEM GUI, find the **Active Inference** section near the bottom and click the **+** next to **Habit Learning**, then click **Run demo**.
4. If plots of simulated neural activity appear, you're golden — everything is set up correctly.

---

## Running the MATLAB Scripts

All MATLAB scripts for the workshop are located in:

```
./cpc_tutorial_code
```

To get started:
1. Open MATLAB.
2. Navigate to the `cpc_tutorial_code` folder.
3. Run the provided scripts during the session.

---

## Background Reading (Optional)

If you'd like to dive deeper into the theory and context of active inference, optional background reading is provided here:

```
./optional_background_reading
```

---

## Further Support

If you have trouble getting to this point before the Tutorial Session, please consult the **#tutorial-helpdesk channel on Discord**. You will be given access to the CPC Discord workspace at the beginning of the course. Check if anyone has had the same issue and managed to solve it, and how. If no one else has encountered the same problem, post your question. We will be monitoring the channel and providing support. In addition, given the volume of attendees this year, we would be really grateful if you could assist us by answering queries on Discord yourself if you come across a problem you know and have solved.

---

## Tutors

- Ryan Smith (rsmith@laureateinstitute.org)

- Carter Goldman (cg610@sussex.ac.uk)


