+++
title = "Web Frameworks"

[extra]

level = 1

intro = "When building a modern web-application you don't want to bother on how to parse the http-header or where the route is supposed to be dispatched to. Frameworks offer exactly those features and make it quick'n'easy to build your specific app on the web-stack. Rust has many backend server frameworks, as well as frontend frameworks for building client apps with webassembly."

server = [
  "actix-web",
  "gotham",
  "iron",
  "nickel",
  "rocket",
  "tide",
  "thruster",
  "warp",
  "axum",
  "poem",
  "viz"
]

frontend = [
  "dioxus",
  "iced",
  "mogwai",
  "percy",
  "sauron",
  "seed",
  "sycamore",
  "yew"
]

newstag = "frameworks"
+++

<h2 id="server">Server</h2>

{{ packages(packages='server') }}

<h2 id="frontend">Frontend (WebAssembly)</h2>

{{ packages(packages='frontend') }}
