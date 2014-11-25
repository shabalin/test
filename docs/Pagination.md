The Iconfinder API version 2.0 uses two different methods of pagination for listing resources. 
Endpoints with deterministic ordering rely on the last received resource for pagination using
the `after` parameter, while non-deterministic endpoints use the more traditional `offset` query
parameter. See [/v2/iconsets](method://List all public icon sets) and [/v2/icons/search](method://Search for icons) respectively for details.