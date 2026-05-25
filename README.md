# ArachneData

This data is for Arachne project: https://github.com/SleepySoft/Arachne

# Usage

## Import

In Arachne project:

```commandline
cd data
git clone https://github.com/SleepySoft/ArachneData.git
cd ..

python backend/scripts/import_db.py --clear --input-dir data/ArachneData/newest
```

## Export

```commandline
python backend/scripts/export_db.py --no-company-view --output-dir data/ArachneData/newest
```



