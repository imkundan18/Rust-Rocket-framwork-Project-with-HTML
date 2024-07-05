# Mini Project of Rust using Rocket framework

Using MongoDB for Data Handle

- post - Insert Data
- Get - Get Data
- put - update
- delete -delete
### Html
- Index
- Register
- user Login
- Admin Login
- Add Song
- Delete Song

Using Cargo for Package Manager in Rust
#### [dependencies]
[dependencies]
rocket={version = "0.5.0-rc.2",features=["json"]}
dotenv="0.15.0"
serde = { version = "1.0.136", features = ["derive"] }
tokio = { version = "1", features = ["full"] }
futures = "0.3"

[dependencies.mongodb]
version="2.2.0"
default-features=false
features=["sync"]

Address:- http://localhost:8000/index.html