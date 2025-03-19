# acdc-test-analysis
Test analysis for the ACDC project


## 1. Set up python venv
```bash
git clone https://github.com/AustralianBioCommons/acdc-test-analysis.git
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## 2. Create config file 
Replace credentials_path with the path to your gen3 api credentials.json
```bash
echo credentials_path=\"/path/to/credentials.json\" > .env
```

## 3. Load library
```bash
pip install -e gen3-metadata/
```


## 4. Run notebook
- [Lightweight analysis of clinical data](gen3_lightweight.ipynb)

