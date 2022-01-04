# db-schema

mysqldump command

```bash
mysqldump -hlocalhost -uroot -proot --databases awsl --no-data | sed 's/ AUTO_INCREMENT=[0-9]*//g' > awsl.sql
```
