### Functions signatures changes when upgrading PostgreSQL versions.

Based on [pg-proc table](https://www.postgresql.org/docs/12/catalog-pg-proc.html)

[Upgrade from pg 9.6](./from-9.6.md)
[Upgrade from pg 10](./from-10.md)
[Upgrade from pg 11](./from-11.md)
[Upgrade from pg 12](./from-12.md)
[Upgrade from pg 13](./from-13.md)

**Attention!**
[EXTRACT](https://www.postgresql.org/docs/12/functions-datetime.html#FUNCTIONS-DATETIME-EXTRACT) function in pg 14 has changed the result type from **double precision** to **numeric**.
