+++
title = "Lower Web-Stack"

[extra]

level = 1

intro = "A strong lower web-stack is important not only to build strong web frameworks on top, but also to allow performance critical systems to reach deeper to squeeze out extra juice. Rust has a good support on HTTP servers, even an HTTP2 implementation, websockets and other protocols."

http = [
  "async-h1",
  "h2",
  "hyper",
  "tiny-http",
  "wtx"
]

websocket = [
  "tungstenite",
  "async-tungstenite",
  "tokio-tungstenite",
  "wtx"
]

protocols = [
  "quinn",
  "sozu"
]

newstag = "stack"

+++
## HTTP Stack

{{ packages(packages='http') }}

## Websocket

{{ packages(packages='websocket') }}

## Other protocols

{{ packages(packages='protocols') }}
