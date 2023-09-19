FROM rust:latest

WORKDIR /app

COPY Cargo.toml .

COPY src src

RUN cargo build --release

CMD ["target/release/rust_http_hello_world"]