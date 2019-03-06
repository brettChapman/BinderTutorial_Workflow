# Binder Tutorial Workflow
---

## Open in binders:

#### Option 1: Launch the Binder Notebook Dashboard 
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/KevinMMendez/BinderTutorial_Workflow/master)

#### Option 2: Directly launch the BinderTutorial_Workflow Jupyter Notebook
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/KevinMMendez/BinderTutorial_Workflow/master?filepath=BinderTutorial_Workflow.ipynb)

---

## Create a Local Copy:

#### Step 1. Install Jupyter and Python using Anaconda

1. Go to the following website and click 'Download': https://www.anaconda.com/distribution/
2. Press the 'Download' button under 'Python 3.7 version' in Bold (and the Anaconda distribution will start downloading) 
3. Double click the file after downloading, and click continue through the installation process
4. Restart the computer (recommendtation), and the app called Anaconda Navigator is installed

#### Step 2. Create a local copy using the Anaconda Navigator

1. Go to https://github.com/KevinMMendez/BinderTutorial_Workflow 
2. Download a zip copy of the repository using the green 'Clone or Download', and press 'Download zip'
3. Move this folder to a suitable directory 
4. Open the Anaconda Navigator Application
5. Move from the 'Home' tab to the 'Environment' tab on the left 
6. Click import at the bottom 
7. Enter 'BinderTutorial_Workflow' as the name (though any name is suitable)
8. Input the 'environment.yml' file downloaded in step 2 as the specification file
9. Return to the 'Home' tab 
10. Change 'Application on... base(root)' to 'Application on... BinderTutorial_Workflow' 
11. Press the 'Launch' button under the Jupyter Notebook box
12. Using the Notebook Dashboard, locate the folder of the downloaded repository and click on the 'BinderTutorial_Workflow.ipynb'.

#### Step 2. (Alternative) Create a local copy using the Terminal / Command Prompt

```console
git clone https://github.com/KevinMMendez/BinderTutorial_Workflow
cd BinderTutorial_Workflow
conda env create -f environment.yml
source activate BinderTutorial_Workflow
jupyter notebook
