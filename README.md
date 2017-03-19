# elixir-ms
- elixir microservice base
- building a new microservice skeleton from scratch once again

## comes with
- strong `http server` basis using plug + cowboy
- fast `json` encode/decode using poison
- `http client` using httpoison
- `metrics` using prometheus_ex
- `healthchecks + config` setup using mix tools
- (json) `access log` provided as Plug
- ELK compliant `logger` with simple API
- registry (in-memory cache) with simple API
- `redis client` using redix
- MIT License

## requirements
- Erlang/OTP >= 19
- Elixir >= 1.3.0

## installation
- git clone this repo
- run `mix deps.get` or `./tools/_get-dependencies.sh`
- start via `./tools/_run.sh`

## build/run in docker container
- build + run via `./tools/_docker.sh`