# singer

## install

mkvirtualenv singer --python=$(which python3)

pip3 install tap-postgres tap-exchangeratesapi target-csv

## setup

Read docs (if any) in github projects for tap-postgres, target-csv, etc...

## run

bin/postgres-singer
