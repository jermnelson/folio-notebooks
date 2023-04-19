# Jupyter Notebooks and FOLIO
Repository contains [Jupyter][JPTY] notebooks for interacting with the [FOLIO][FOLIO] Library
Systems Platform along with a corresponding Library Data Platform.


## Environmental Variables 
After cloning/copying this repository, create a local .env file and add the following variables
to use in your notebook (you can rename the `.example-env` to `.env` and update the variables)

```bash
export OKAPI_URL=https://okapi-url
export OKAPI_USER=username
export OKAPI_PASSWORD=password
export TENANT=tenant
export METADB_URL=metadb_url
export METADB_USER=metadb_user
export METADB_PASSWORD=metdatadb_user_password
```

## Installation
To run these examples, you'll need a version of Python 3.10 or later installed on your local
machine.

1. Copy or clone this repository `git clone ...`
1. Create a Python virtual environment `python3 -m venv folio-env`
1. Activate the virtual environment `source folio-env/bin/activate`
1. Source the .env file `source .env`
1. Install the dependencies using pip, `pip install -r requirements.txt`
1. Launch Jupyter lab `jupyter lab`

[JPTY]: https://jupyter.org/
[FOLIO]: https://www.folio.org/
