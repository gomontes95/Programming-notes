### El schema pertenece al owner

`ALTER SCHEMA public OWNER TO db_owner;`

---

### Permisos para app_user

`GRANT CONNECT ON DATABASE nicasia TO app_user;  GRANT USAGE ON SCHEMA public TO app_user;  GRANT SELECT, INSERT, UPDATE, DELETE ON ALL TABLES IN SCHEMA public TO app_user;`

Y para el futuro:

`ALTER DEFAULT PRIVILEGES IN SCHEMA public GRANT SELECT, INSERT, UPDATE, DELETE ON TABLES TO app_user;`