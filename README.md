# bms
- Install `migrate` from here:
- `https://github.com/golang-migrate/migrate/tree/master/cmd/migrate`
- How to migrate database
- `migrate -path db/migration -database "postgresql://user:pass@localhost:5432/simple_bank?sslmode=disable" --verbose up`