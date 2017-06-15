# Adding State to HTTP

HTTP is a stateless protocol. This means each request does not know anything
about any previous requests. So in order to add state to your web application
that state, or a reference to it, needs to be sent as part of every single
HTTP request. This is where cookies come in.

## Skills

- Can explain "state" vs. "stateless"
- Can explain what "HTTP is a stateless protocol" means
- Can explain what a cookie is
- Can store data in cookies using node and express
- Can track individual visitors to your App
- Can setup a `nodejs` / `express` app that uses cookie based authentication

## Search Terms

```
http stateless
http cookie
cookie based authentication
```

## Suggested Resources

### Watch

- [Everything You Ever Wanted To Know About Authentication in Node.js](https://www.youtube.com/watch?v=yvviEA1pOXw&list=UUJI9gByFSXE1ABDRcLQjWgQ)

### Read

- https://en.wikipedia.org/wiki/State_(computer_science)
- [All You Ever Wanted to Know About Sessions In Node.js](https://stormpath.com/blog/everything-you-ever-wanted-to-know-about-node-dot-js-sessions)



## Activies

- [Remember Me App](./exercises/Remember-Me-App)
- [Secure Session Cookie](./exercises/Secure-Session-Cookie)