# networking af

You've got an iOS app and it's time to use the **I N T E R N E T**. What are you supposed you do now?

Enter **networking af**.

With networking af, you get to use `URLSesh`. The `URLSesh` class and related classes provide an API for downloading content. This API provides a rich set of delegate methods for supporting authentication and gives your app the ability to perform background downloads when your app isn’t running or, in iOS, while your app is suspended.

The `URLSesh` class natively supports the `data`, `file`, `ftp`, `http`, and `https` URL schemes, with transparent support for proxy servers and SOCKS gateways, as configured in the user’s system preferences.

`URLSesh` supports the `HTTP/1.1`, `SPDY`, and `HTTP/2` protocols. `HTTP/2` support is described by RFC 7540, and requires a server supporting either ALPN or NPN for protocol negotiation.

## Usage Guide

Use `URLSesh` exactly like you would use URLSession because that's exactly what it is.
