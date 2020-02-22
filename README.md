# flappy-bird-cnn

🐦Build a controlled neural network to allow an ai to win every time at flappy bird 🐤

## Getting Started

1. Install Python 3.x (recommended) 2.x from [here](https://www.python.org/download/releases/)

2. Install pip3 if it is not already installed

    ```bash
    sudo apt-get -y install python3-pip
    ```

3. Install [pipenv](https://pipenv.readthedocs.io/en/latest/)

    ```bash
    sudo -H pip3 install -U pipenv
    ```

4. Initialize the submodule

    ```bash
    git submodule init
    ```

5. Update the submodule to make sure it is the using the most latest pull on your local environment

    ```bash
    git submodule update
    ```

## Run the Application

1. Install the python packages from the Pipfile

    ```bash
    cd FlapPyBird
    pipenv install
    ```

    If you are having trouble with running the `pipenv install` command check your python version, because the *FlapPyBird* project will only run with python 3.7. To change version you can update your alternatives

    ```bash
    $ python3 --version
    Python 3.8.0
    $ sudo apt-get install python3.7
    $ sudo update-alternatives --install /usr/bin/python3 python3 /usr/bin/python3.7 2
    $ sudo update-alternatives --config python3
    There are 3 choices for the alternative python3 (providing /usr/bin/python3).

    Selection    Path                Priority   Status
    ------------------------------------------------------------
    0            /usr/bin/python3.7   3         auto mode
    1            /usr/bin/python3.6   1         manual mode
    2            /usr/bin/python3.7   3         manual mode
    * 3            /usr/bin/python3.8   2         manual mode

    Press <enter> to keep the current choice[*], or type selection number: 2
    update-alternatives: using /usr/bin/python3.7 to provide /usr/bin/python3 (python3) in manual mode
    $ python3 --version
    Python 3.7.5
    ```

    Then re-run the installation command. `Note you might need to reinstall pipenv after changing your python version to an alternative`

2. Run the project's virtualenv

    ```bash
    pipenv shell
    ```
