# environment setup
You can recreate the conda environment with environment_rtSynth_rt.yml file by running:

`conda env create -f environment.yml`

# data
subject's data can be found in [here](https://doi.org/10.5061/dryad.kd51c5bg2) and [here](https://drive.google.com/drive/folders/17_5b6a3SgqmiMrLh_W8ZxehfKvAt_mTB?usp=sharing) and should be stored in the ./data folder

# preprocessing
data_preprocess and prepare data for plotting fig2c, fig4b and fig5
`data_preprocess/data_preprocess.py`

# analysis and figure plotting
adaptive threshold analysis code  # fig2b
`fig2b/fig2b.py`


X Y co-activation analysis code  # fig2c
`fig2c/fig2c.py`


behavioral categorical perception analysis code  # fig3c
`fig3c/fig3c.py`


behavioral categorical perception analysis code - statistical analysis  # fig3d
`fig3d/fig3d.py`


hippocampus subfield integration analysis code
`fig4b/fig4b.py`


geometric analysis for hippocampus. fig5
`fig5/fig5.py`

