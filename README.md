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

## Configuration

Obtain an API Key from AlphaVantage

Then create a local ".env" file and provide the key like this:

```sh
ALPHAVANTAGE_API_KEY="_____"
```

## Usage

Run an example script:

```sh
python app/my_script.py
```
Run the unemployment report

```sh
python -m app.unemployment
```

Run stocks report:

```sh
python -m app.stocks
```
## Testing

Run tests:

```sh
pytest
```