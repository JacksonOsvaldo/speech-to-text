# Speech to text using Google API

## Create Virtualenv

```bash
virtualenv -p python3.8 env && source env/bin/activate && pip install -U pip
```

## Install dependences

```bash
pip install -r requirements.txt
```

## Get API Key
Access cloud.google.com and get your Key for API.

## Configure

Insert your key in:

```python
os.environ['GOOGLE_APPLICATION_CREDENTIALS']= 'google_secret_key.json'
```

Or save in google_secret_key.json file.

## Run

```bash
python main.py
```

## Running Example

```
Transcript:  The Birch canoes slid on the smooth planks.
Transcript:  Glue the sheet to the dark blue background.
Transcript:  It is easy to tell the death of a well.
Transcript:  These days, a chicken leg is a verb dish.
Transcript:  Rice is often served in round bowls.
Transcript:  The juice of lemons makes find punch.
Transcript:  The box was down beside the park truck.
Transcript:  The Hogs of food shop, corn and garbage.
Transcript:  4 hours of study work Facebook.
Transcript:  A large size in stockings is hard to sell.
```

