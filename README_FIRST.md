# Programming Assignment 1

## From Tableau to Decision: Simplex, Duality, and Sensitivity Analysis

This assignment uses one small production-planning model to connect three ideas:

1. how the simplex method moves from one basic feasible solution to another;
2. how the primal and dual solutions certify optimality; and
3. how sensitivity analysis supports decisions about scarce resources.

No previous programming experience is required. The notebook supplies the Python code. Your job is to run the cells in order, make several simplex pivot choices, examine the results, and explain what those results mean.

## What is in this folder?

- `PA1-students.ipynb` — the assignment notebook.
- `data/` — all data files used by the notebook. Do not rename or move this folder.
- `requirements.txt` — software packages needed only if you run Jupyter on your own computer.
- `TROUBLESHOOTING.md` — solutions to common problems.
- `SUBMISSION_CHECKLIST.md` — a final checklist to use before submitting.

## Required setup: install Python first, then JupyterLab

Complete this setup before beginning the assignment. Install **Python first** because JupyterLab runs using Python and is installed with Python's package installer, `pip`. The `requirements.txt` command below installs JupyterLab and all other software libraries required by the assignment.

Official installation pages:

- [Download Python](https://www.python.org/downloads/)
- [Installing Jupyter](https://jupyter.org/install)

Python 3.12 or 3.13 (64-bit) is recommended for this assignment. Do not choose a beta or prerelease version. You only need to complete the installation once.

### Windows

1. On the Python download page, choose a Windows 64-bit installer for Python 3.12 or 3.13.
2. Run the downloaded installer. If the installer displays **Add Python to PATH** or **Add python.exe to PATH**, select that option, and then choose **Install Now**.
3. When installation finishes, close and reopen the terminal.
4. Unzip the assignment package. In File Explorer, open the assignment folder, right-click an empty area, and select **Open in Terminal**.
5. Check the installation by running:

```text
py --version
```

The result should begin with `Python 3.12` or `Python 3.13`. Install JupyterLab and the other required libraries, verify the JupyterLab installation, and then start it:

```text
py -m pip install --upgrade pip
py -m pip install -r requirements.txt
py -m jupyter lab --version
py -m jupyter lab
```

The installation command may take several minutes. A JupyterLab version number should appear after the third command.

### macOS

1. On the Python download page, choose the macOS 64-bit universal installer for Python 3.12 or 3.13.
2. Run the downloaded package and accept the standard installation choices.
3. Unzip the assignment package and open Terminal. Type `cd` followed by a space, drag the assignment folder from Finder into the Terminal window, and press **Return**.
4. Check the installation by running:

```text
python3 --version
```

The result should begin with `Python 3.12` or `Python 3.13`. Install JupyterLab and the other required libraries, verify the JupyterLab installation, and then start it:

```text
python3 -m pip install --upgrade pip
python3 -m pip install -r requirements.txt
python3 -m jupyter lab --version
python3 -m jupyter lab
```

The installation command may take several minutes. A JupyterLab version number should appear after the third command.

JupyterLab should then open in your web browser. From that page, open `PA1-students.ipynb`. Keep the notebook and the `data` folder together.

If you use a Chromebook, a tablet, or a computer on which you cannot install software, contact your instructor before beginning the assignment.

## How to complete the assignment

1. Start JupyterLab from the assignment folder using the final command shown above.
2. Open `PA1-students.ipynb`.
3. Read the **Academic integrity and permitted help** section.
4. Select the first cell and press **Shift+Enter** to run it.
5. Continue from top to bottom. Never skip a code cell.
6. Type only in places marked **YOUR CHOICE** or **YOUR RESPONSE**.
7. Save often.
8. When finished, select **Kernel > Restart Kernel and Run All Cells** (the exact wording may differ slightly).
9. Confirm that every cell runs without a red error message.
10. Export or download the completed notebook as HTML.
11. Put the completed `.ipynb` and `.html` files into one ZIP and submit that ZIP.

The first notebook cell includes a short orientation for students who have never used Jupyter.

## Expected time

Allow approximately 3–4 hours, including reading, calculations, written explanations, and the final run-through.

## What to submit

Create `Lastname_Firstname_PA1.zip` and submit that one ZIP file using your instructor's learning-management system. It must contain:

- `Lastname_Firstname_PA1.ipynb`
- `Lastname_Firstname_PA1.html`

Replace `Lastname_Firstname` with your own name. The two files inside the ZIP must contain all outputs and all written responses. The data files do not need to be submitted unless your instructor says otherwise.

## Important reminder

The notebook is designed to give immediate computational feedback, but a successful code check is not the same as a complete answer. Credit also depends on your explanations, units, mathematical reasoning, and decision recommendations.
