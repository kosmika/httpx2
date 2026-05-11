# Exceptions

This page lists exceptions that may be raised when using HTTPX.

For an overview of how to work with HTTPX exceptions, see [Exceptions (Quickstart)](quickstart.md#exceptions).

## The exception hierarchy

* HTTPError
    * RequestError
        * TransportError
            * TimeoutException
                * ConnectTimeout
                * ReadTimeout
                * WriteTimeout
                * PoolTimeout
            * NetworkError
                * ConnectError
                * ReadError
                * WriteError
                * CloseError
            * ProtocolError
                * LocalProtocolError
                * RemoteProtocolError
            * ProxyError
            * UnsupportedProtocol
        * DecodingError
        * TooManyRedirects
    * HTTPStatusError
* InvalidURL
* CookieConflict
* StreamError
    * StreamConsumed
    * ResponseNotRead
    * RequestNotRead
    * StreamClosed

---

## Exception classes

::: httpx2.HTTPError
    :docstring:

::: httpx2.RequestError
    :docstring:

::: httpx2.TransportError
    :docstring:

::: httpx2.TimeoutException
    :docstring:

::: httpx2.ConnectTimeout
    :docstring:

::: httpx2.ReadTimeout
    :docstring:

::: httpx2.WriteTimeout
    :docstring:

::: httpx2.PoolTimeout
    :docstring:

::: httpx2.NetworkError
    :docstring:

::: httpx2.ConnectError
    :docstring:

::: httpx2.ReadError
    :docstring:

::: httpx2.WriteError
    :docstring:

::: httpx2.CloseError
    :docstring:

::: httpx2.ProtocolError
    :docstring:

::: httpx2.LocalProtocolError
    :docstring:

::: httpx2.RemoteProtocolError
    :docstring:

::: httpx2.ProxyError
    :docstring:

::: httpx2.UnsupportedProtocol
    :docstring:

::: httpx2.DecodingError
    :docstring:

::: httpx2.TooManyRedirects
    :docstring:

::: httpx2.HTTPStatusError
    :docstring:

::: httpx2.InvalidURL
    :docstring:

::: httpx2.CookieConflict
    :docstring:

::: httpx2.StreamError
    :docstring:

::: httpx2.StreamConsumed
    :docstring:

::: httpx2.StreamClosed
    :docstring:

::: httpx2.ResponseNotRead
    :docstring:

::: httpx2.RequestNotRead
    :docstring:
