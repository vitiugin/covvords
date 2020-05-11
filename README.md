## COVID-19 Twitter Keywords Extraction

Twitter Keywords Extraction (from Mongo DB server) based on code from https://t.co/69FA0rkKUU

### Installation

Install all modules from pip

`$ pip3 install -r requirements.txt`

Install pre-trained language model for English

`$ python3 -m spacy download en_core_web_sm`

### Using

For using keywords extraction for English, use the next command:

`$ python3 ke_en.py USER PASSWORD SERVER "Mon May 11"`
