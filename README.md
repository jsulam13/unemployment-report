# unemployment-report


## Setup

Create and activate a virtual environment:

```sh
conda create -n unemployment-env python3.8

conda activate unemployment-env
```

Install package dependencies:

```sh
pip install -r requirements.txt
```

##Usage

Run an example script:

```sh
python app/my_script.py
```
Run the unemployment report

```sh
python app/unemployment.py

#Or pass env var from command line:
ALPHAVANTAGE_API_KEY="_____" python app/unemployment.py
```