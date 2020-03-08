(base) Maggies-MacBook-Pro:~ Maggie$ brew install wget
(base) Maggies-MacBook-Pro:~ Maggie$ sudo python /Users/Maggie/Documents/potbot.py
(base) Maggies-MacBook-Pro:maggie Maggie$ conda create --name dhmuse
(base) Maggies-MacBook-Pro:maggie Maggie$ conda activate dhmuse
(dhmuse) Maggies-MacBook-Pro:maggie Maggie$ pip install csvs-to-sqlite
-bash: pip: command not found
(dhmuse) Maggies-MacBook-Pro:maggie Maggie$ pip install datasette
-bash: pip: command not found
(dhmuse) Maggies-MacBook-Pro:maggie Maggie$ help
(dhmuse) Maggies-MacBook-Pro:maggie Maggie$ conda deactivate
(base) Maggies-MacBook-Pro:maggie Maggie$ python -m ensurepip --default-pip
(base) Maggies-MacBook-Pro:maggie Maggie$ conda activate dhmuse
(dhmuse) Maggies-MacBook-Pro:maggie Maggie$ pip install csvs-to-sqlite
(dhmuse) Maggies-MacBook-Pro:maggie Maggie$ pip install datasette
(dhmuse) Maggies-MacBook-Pro:maggie Maggie$ csvs-to-sqlite your-data-table.csv your-database.db
(dhmuse) Maggies-MacBook-Pro:maggie Maggie$ 
(dhmuse) Maggies-MacBook-Pro:maggie Maggie$ csvs-to-sqlite cstm-markers-only.csv CSTM-markers.db
Error: Invalid value for "PATHS...": Path "cstm-markers-only.csv" does not exist.
(dhmuse) Maggies-MacBook-Pro:maggie Maggie$ csvs-to-sqlite cstm-markers-only.csv CSTM-markers.db/Users/Maggie/Downloads/cstm-markers-only.csv /Users/Maggie/Downloads/cstm-markers-only.csv 
(dhmuse) Maggies-MacBook-Pro:maggie Maggie$ csvs-to-sqlite /Users/Maggie/Downloads/cstm-markers-only.csv CSTM-Markers.db 
(dhmuse) Maggies-MacBook-Pro:maggie Maggie$ datasette CSTM-Markers.db
