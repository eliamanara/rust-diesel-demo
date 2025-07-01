# rust-diesel-demo

This is an example of using the Rust crate "diesel"
to access a PostgreSQL database.

To run it, enter `cargo run`.

## Database Setup

Install `diesel`:
```
curl --proto '=https' --tlsv1.2 -LsSf https://github.com/diesel-rs/diesel/releases/latest/download/diesel_cli-installer.sh | sh
```
or
```
cargo binstall diesel_cli
```
See [here](https://diesel.rs/guides/getting-started) for further details.

Export the database URL:
```
export DATABASE_URL=postgres://postgres:password@192.168.176.1:5432/rusttest
```

Run the initial database setup:
```
diesel setup
```

## Run The Application

Run the application with:
```
cargo run
```