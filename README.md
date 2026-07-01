## Data Versioning with DVC

The raw dataset files are tracked with DVC and are not stored directly in GitHub.

After cloning the repository, install the requirements and run:

```bash
pip install -r requirements.txt
dvc pull
```

This will download the dataset files into the data/ folder:

data/train_data.csv
data/test_data.csv
data/sample_submission.csv