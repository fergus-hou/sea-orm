# Actix 4 Beta with SeaORM example app

Edit `.env` to point to your database.

Run server with auto-reloading:

```bash
cargo install systemfd
systemfd --no-pid -s http::8000 -- cargo watch -x run
```