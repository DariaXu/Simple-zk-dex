### How to run on Linux
1. Start Ganache, <br>
`ganache-cli`
2. Start a new terminal and run Rust-sc to start listening to events,<br>
`cd rust-sc`
`cargo run`
3. Start a new terminal and run Truffle unit test<br>
`cd ../orderbook`
`truffle test`
4. You should see the caught events on the Rust-sc terminal
