# Running FHIR apps

These are FHIR web applications written in Python and using Flask as the backend. 

## 1. Dependencies
This app depends on Python 3 and a few Python packages outlined in the `requirements.txt` file. 

## 2. Running the Apps

We begin by creating a Python virtual environment using the `venv` module. This is done by running the command below from the "root" of this repo. 

```
python3 -m venv venv                 # create a virtual environment called venv

source venv/bin/activate             # activate our virtual environment

pip3 install -r requirements.txt     # install all our dependencies into the virtual environment
```


After the above steps, we should be able to launch our app using the following command.

```
python3 src/fhir_patient_finder_synthea_ri.py                   # for the patient finder app

python3 src/fhir_condition_finder_synthea_ri.py                 # for the condition finder app
```

This will start the app on port 5000. You can open your preferred browser and see the app running on the URL which displays on the terminal


