## One time venv creation

1. For macOS
    1. Make sure you are in the PetRecognition directory
    2. Set python version, make environment and activate the environment:
        1. If using asdf:
            1. deactivate your current environment (if you are in one) using the following command:
                deactivate
            2. set your python version to 3.10.12 using the following command:
                asdf set python 3.10.12
            3. Create your venv with the following command. The second venv being a placeholder for the environment's name:
                python -m venv venv
            4. Activate the venv using the following command:
                source venv/bin/activate
        2. If using conda:
            1. deactivate your current environment (if you are in one) using the following command:
                deactivate
            2. Create your venv with the following command. The second venv being a placeholder for the environment's name:
                conda create --name venv python=3.10.12
            3. Activate the venv using the following command:
                conda activate venv
    5. Install matplotlib in the venv using the following command:
        pip install matplotlib
    6. Install jupyter in the venv using the following command:
        pip install jupyter
    7. Install numpy in the venv using the following command:
        pip install numpy
    8. Install pandas in the venv using the following command:
        pip install pandas
    9. Install tensorflow in the venv using the following command:
        pip install tensorflow
    10. Install the jupyter kernel editor using the following command:
        pip install ipykernel
    11. Add the venv as a kernel for your version of jupyter, type in your password when prompted using the following command:
        sudo python -m ipykernel install --name=venv --display-name "Python (venv)"
    12. Open jupyter notebooks and then change your current kernel to Python (venv) using the following command:
        jupyter notebook

# NOTE: Always deactivate your venv after using with the following command:
    deactivate



## Daily start-up guide (venv activation)
