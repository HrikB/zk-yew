# zk-yew

Yew-rs is a react-like framework for creating reactive UIs. It has a macro for declaring HTML using Rust expressions (replacement for jsx) which compiles down to WASM.

This is a testing repo for playing around with zk libraries (mainly zk proof generating libaries) with yew.

## Setup

Install the web assembly target:
`rustup target add wasm32-unknown-unknown`

Install trunk
`cargo install --locked trunk`

Serve the app using trunk
`trunk serve`
