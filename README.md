# so

**Note:** under development, not ready for prime time.

### to troubleshoot
```
export RUST_BACKTRACE=full
cargo run -- how do I exit Vim > test.txt 2>&1
```

### api keys
According to the [StackExchange
docs](https://api.stackexchange.com/docs/throttle), most users should be fine
without generating a personal API key (10k requests per IP per day). If you do
run into throttling issues, get a key
[here](https://stackapps.com/apps/oauth/register) and tell `so` to use it:
```
so --set-api-key <KEY>
```

Recall my api key is: `8o9g7WcfwnwbB*Qp4VsGsw((`

