Registration From
# Registration from in Rust by using Rocket framework

Using SQL for Data Handle

- Post - Insert Data
- Get - Get Data

#Use Cargo for Package Manager in Rust
- cargo new <project name>
- cd <project name>
- cargo build
- carho run


#### [dependencies]
rocket={version = "0.5.0-rc.2",features=["json"]}
dotenv="0.15.0"
serde = { version = "1.0.136", features = ["derive"] }
tokio = { version = "1", features = ["full"] }
futures = "0.3"


[dependencies.mongodb]
version="2.2.0"
default-features=false
features=["sync"]