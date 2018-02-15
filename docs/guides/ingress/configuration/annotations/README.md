# Configure ingress with annotations

Below is the full list of supported annotation keys:

|  Keys  |   Value   |  Default |
|--------|-----------|----------|
| [ingress.appscode.com/accept-proxy](accept-proxy.md) | bool | `false` |
| [ingress.appscode.com/affinity](sticky-session.md) | `cookie` | |
| [ingress.appscode.com/session-cookie-hash](sticky-session.md) | string | |
| [ingress.appscode.com/session-cookie-name](sticky-session.md) | string | `SERVERID` |
| [ingress.appscode.com/hsts](hsts.md) | bool | `true` |
| [ingress.appscode.com/hsts-include-subdomains](hsts.md) | bool | `false` |
| [ingress.appscode.com/hsts-max-age](hsts.md) | string | `15768000` |
| [ingress.appscode.com/hsts-preload](hsts.md) | bool | `false` |
| [ingress.appscode.com/use-node-port]() | bool | `false` |
| [ingress.appscode.com/enable-cors](cors.md) | bool | `false` |
| [ingress.appscode.com/cors-allow-headers](cors.md) | string | `DNT,X-CustomHeader,Keep-Alive,User-Agent,X-Requested-With,If-Modified-Since,Cache-Control,Content-Type,Authorization` |
| [ingress.appscode.com/cors-allow-methods](cors.md) | string | `GET,PUT,POST,DELETE,PATCH,OPTIONS` |
| [ingress.appscode.com/cors-allow-origin](cors.md) | string | `*` |
| [ingress.appscode.com/default-option](default-options.md) | map | `{"http-server-close": "true", "dontlognull": "true"}` |
| [ingress.appscode.com/default-timeout](default-timeouts.md) | map | `{"connect": "50s", "server": "50s", "client": "50s", "client-fin": "50s", "tunnel": "50s"}` |

ingress.appscode.com/annotations-pod
ingress.appscode.com/annotations-service
ingress.appscode.com/api-schema
ingress.appscode.com/auth-realm
ingress.appscode.com/auth-secret
ingress.appscode.com/auth-tls-error-page
ingress.appscode.com/auth-tls-secret
ingress.appscode.com/auth-tls-verify-client
ingress.appscode.com/auth-type
ingress.appscode.com/cors-allow-headers
ingress.appscode.com/cors-allow-methods
ingress.appscode.com/cors-allow-origin
ingress.appscode.com/daemon.nodeSelector
ingress.appscode.com/default-option
ingress.appscode.com/default-timeout
ingress.appscode.com/errorfiles
ingress.appscode.com/force-ssl-redirect
ingress.appscode.com/keep-source-ip
ingress.appscode.com/limit-connection
ingress.appscode.com/limit-rpm
ingress.appscode.com/limit-rps
ingress.appscode.com/load-balancer-ip
ingress.appscode.com/max-connections
ingress.appscode.com/node-selector
ingress.appscode.com/proxy-body-size
ingress.appscode.com/replicas
ingress.appscode.com/rewrite-target

ingress.appscode.com/ssl-passthrough
ingress.appscode.com/ssl-redirect
ingress.appscode.com/stats
ingress.appscode.com/stats-port
ingress.appscode.com/stats-secret-name
ingress.appscode.com/stats-service-name
ingress.appscode.com/sticky-session
ingress.appscode.com/type
ingress.appscode.com/whitelist-source-range