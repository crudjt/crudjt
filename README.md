<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="logos/crudjt_logo_white_on_dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="logos/crudjt_logo_dark_on_white.svg">
    <img alt="Shows a dark logo" src="logos/crudjt_logo_dark.png">
  </picture>
  <b>Fast, file-backed, scalable JSON token engine</b>
</p>

CRUDJT is a B-tree–backed persistent token engine for stateful user sessions  
It provides predictable disk usage and low latency across multiple processes    
No external database required        

# Getting Started
Choose your language:  
* [Ruby](https://github.com/crudjt/crudjt-ruby): `gem install crudjt --pre`
* [Python](https://github.com/crudjt/crudjt-python): `pip install crudjt`
* [Java](https://github.com/crudjt/crudjt-java): Use JARs from Maven Central Repository
* [JavaScript](https://github.com/crudjt/crudjt-javascript): `npm install crudjt`
* [Elixir](https://github.com/crudjt/crudjt-elixir): `{:crudjt, "~> 1.0.0-beta.0"}`
* [Erlang](https://github.com/crudjt/crudjt_erlang): Use crudjt_erlang repo from that repo
* [Go](https://github.com/crudjt/crudjt-go): `go get github.com/crudjt/crudjt-go@latest`
* [PHP](https://github.com/crudjt/crudjt-php): `composer require crudjt/crudjt-php:^1.0@beta`

# Scale
CRUDJT includes an embedded gRPC layer for multi-process communication  
Designed for vertical scaling with predictable file-backed storage  
