<p align="center">
  <img src="logos/crud_jt_logo_black.png#gh-light-mode-only" alt="Logo Light" />
  <img src="logos/crud_jt_logo.png#gh-dark-mode-only" alt="Logo Dark" />
</p>

<p align="center">
  <b>Fast, file-backed, scalable JSON token engine</b>
</p>

CRUDJT is a high-performance persistent token store for stateful user sessions  
It maintains authentication and authorization across multiple processes with predictable disk usage and low latency  

No external database required  

# Getting Started
Choose your language:  
* [Ruby](https://github.com/Cm7B68NWsMNNYjzMDREacmpe5sI1o0g40ZC9w1y/crudjt-ruby): `gem install crudjt`
* [Python](https://github.com/Cm7B68NWsMNNYjzMDREacmpe5sI1o0g40ZC9w1y/crudjt-python): `pip install crudjt`
* [Java](https://github.com/Cm7B68NWsMNNYjzMDREacmpe5sI1o0g40ZC9w1y/crudjt-java): Use JARs from Maven Central Repository
* [JavaScript](https://github.com/Cm7B68NWsMNNYjzMDREacmpe5sI1o0g40ZC9w1y/crudjt-javascript): `npm install crudjt`
* [Elixir](https://github.com/Cm7B68NWsMNNYjzMDREacmpe5sI1o0g40ZC9w1y/crudjt-elixir): `{:crudjt, "~> x.x"}`
* [Erlang](https://github.com/Cm7B68NWsMNNYjzMDREacmpe5sI1o0g40ZC9w1y/crudjt_erlang): `deps get crudjt`
* [Go](https://github.com/Cm7B68NWsMNNYjzMDREacmpe5sI1o0g40ZC9w1y/crudjt-go): `go get crudjt`
* [PHP](https://github.com/Cm7B68NWsMNNYjzMDREacmpe5sI1o0g40ZC9w1y/crudjt-php): `composer require crudjt`

# Performance
Benchmarks across supported languages:  
* [Ruby](https://github.com/Cm7B68NWsMNNYjzMDREacmpe5sI1o0g40ZC9w1y/crudjt-ruby?tab=readme-ov-file#performance)
* [Python](https://github.com/Cm7B68NWsMNNYjzMDREacmpe5sI1o0g40ZC9w1y/crudjt-python?tab=readme-ov-file#performance)
* [Java](https://github.com/Cm7B68NWsMNNYjzMDREacmpe5sI1o0g40ZC9w1y/crudjt-java?tab=readme-ov-file#performance)
* [Javascript](https://github.com/Cm7B68NWsMNNYjzMDREacmpe5sI1o0g40ZC9w1y/crudjt-javascript?tab=readme-ov-file#performance)
* [Elixir](https://github.com/Cm7B68NWsMNNYjzMDREacmpe5sI1o0g40ZC9w1y/crudjt-elixir?tab=readme-ov-file#performance)
* [Erlang](https://github.com/Cm7B68NWsMNNYjzMDREacmpe5sI1o0g40ZC9w1y/crudjt-erlang?tab=readme-ov-file#performance)
* [Go](https://github.com/Cm7B68NWsMNNYjzMDREacmpe5sI1o0g40ZC9w1y/crudjt-go?tab=readme-ov-file#performance)
* [PHP](https://github.com/Cm7B68NWsMNNYjzMDREacmpe5sI1o0g40ZC9w1y/crudjt-php?tab=readme-ov-file#performance)

# Disk footprint  
**40k** tokens  
**256 bytes**  
Median over 10 runs  
macOS (darwin23), APFS    

`48 MB`  

[Full disk footprint results](https://github.com/Cm7B68NWsMNNYjzMDREacmpe5sI1o0g40ZC9w1y/disk_footprint)

# Scale
CRUDJT includes an embedded gRPC layer for multi-process communication  
Designed for vertical scaling with predictable file-based storage  
