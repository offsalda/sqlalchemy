# SQLAlchemy ORM Tutorial for Python Developers


## Useful Commands

```bash
# starting a dockerized instance of PostgreSQL
docker run --name sqlalchemy-orm-psql \
    -e POSTGRES_PASSWORD=dbpassword \
    -e POSTGRES_USER=dbuser \
    -e POSTGRES_DB=sqlalchemy-orm-tutorial \
    -p 5432:5432 \
    -d postgres

# running basic example
python -m examples.basic

# running one to one example
python -m examples.onetoone
```
