# Trigger Call Link

So you're building some kind of an (no-code / low-code) integration but somehow
the integration doesn't support links that are `tel:+123455678`? That's when you
use this repo. Instead of `tel:` links.


## Basic Usage
```
http://bonton-connect.github.io/trigger-call-link/{phone_number}
```

If you want to call the number `+012233445566`, send the
browser to: [`http://bonton-connect.github.io/trigger-call-link/+012233445566`](http://bonton-connect.github.io/trigger-call-link/+012233445566)

## Auto Calling

If you want the browser to automatically promt for calling, add `autocall` somewhere in the URL.

```
http://bonton-connect.github.io/trigger-call-link/autocall/{phone_number}

// OR

http://bonton-connect.github.io/trigger-call-link/{phone_number}?autocall
```

## License

PUBLIC DOMAIN