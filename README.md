# db-schema

mysqldump command

```bash
mysqldump -hlocalhost -uroot -proot --databases awsl --no-data --skip-comments --no-create-db | sed 's/ AUTO_INCREMENT=[0-9]*//g' | sed 's/USE [.*?]*[;]*//g' > awsl.sql
```
