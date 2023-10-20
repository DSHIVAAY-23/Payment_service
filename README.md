# Payment_service

# Rust Payment Service with gRPC

This is a simple payment service implemented in Rust using gRPC. It allows you to make payments through a gRPC interface.

## Prerequisites

Before you get started, make sure you have the following prerequisites installed on your system:

- [Rust](https://www.rust-lang.org/)
- [Cargo](https://doc.rust-lang.org/cargo/)
- [Protocol Buffers](https://developers.google.com/protocol-buffers)
- [gRPC](https://grpc.io/)

## Setup

1. Clone this repository to your local machine:

   ```shell
   git clone https://github.com/yourusername/payment-service-rust-grpc.git
   cd payment-service-rust-grpc

   Install the necessary gRPC Rust dependencies:

cargo install grpcio-compiler
cargo install tonic-build

Running the Payment Service
cargo run --bin payments-server
cargo run --bin payments-client

