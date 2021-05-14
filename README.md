
# covid_IIS:
"covid_IIS" is a Python app developed to predict the outcome of COVID-19 patients in the moment of hospital admission. It is designed to use as less variables as possible (only 20). All such variables as selected between the most common ones, available in many hospitals. It uses machine learning algorithms (XGBOOST). It is released under European Union Public License (EUPL).

## Description:
This project includes:

 - A Jupyter-notebook file containing the App code.
 - A *Pix* folder containing the logos of the different institutions and organizations involved in the project.
 - A *Model* folder containing our best model, selected for the app.
 - A *environment.yml* containing the requirements for creating a conda environment to run the jupyter notebook.
 - A *README.md* file containing the explanations.

## Requirements:
To be able to install the *environment.yml* file, *Anaconda* and *Python* should be installed previously in your computer/server.

## Usage:
Once cloned the repository, allocate on the main folder and execute:
`conda env create -f environment.yml`
This will create the environment *covid_ITA_IIS*. Activate it by executing:
`conda activate covid_ITA_IIS`
With the environment activated, run the app with the command:
`voila VoilaApp.ipynb --VoilaConfiguration.file_whitelist="['.*.(png)']" --MappingKernelManager.cull_interval=120 --MappingKernelManager.cull_idle_timeout=120 --port={port}`
Where `{port}` is the selected port on your server/computer that will give acces to the app.

## Notes:
Shap values are not represented in this demo-app due to privacy and data protection.

## Contributors:

- Rocío Aznar Gimeno - [raznar@itainnova.es](raznar@itainnova.es)
- Rafael del Hoyo Alonso - [rdelhoyo@itainnova.es](rdelhoyo@itainnova.es)
- David Abadía Gallego - [dabadia@gmail.com](dabadia@gmail.com)
- Gorka Labata Lezaun - [glabata@itainnova.es](glabata@itainnova.es)

## Cite:
Pending
