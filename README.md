[![Build Status](https://travis-ci.org/codedge-llc/pigeon.svg?branch=master)](https://travis-ci.org/codedge-llc/pigeon)
[![Hex.pm](http://img.shields.io/hexpm/v/pigeon.svg)](https://hex.pm/packages/pigeon) [![Hex.pm](http://img.shields.io/hexpm/dt/pigeon.svg)](https://hex.pm/packages/pigeon)
[![Deps Status](https://beta.hexfaktor.org/badge/all/github/codedge-llc/pigeon.svg)](https://beta.hexfaktor.org/github/codedge-llc/pigeon)
# Pigeon
HTTP2-compliant wrapper for sending iOS and Android push notifications.

Add pigeon and kadabra as `mix.exs` dependencies:
  ```elixir
  def deps do
    [
      {:pigeon, "~> 1.0.0"},
      {:kadabra, "~> 0.2.0"}
    ]
  end
  ```

## Getting Started
For usage and configuration, see the docs:
* [APNS (Apple iOS)](https://hexdocs.pm/pigeon/apns-apple-ios.html)
* [FCM (Android)](https://hexdocs.pm/pigeon/fcm-android.html)
* [ADM (Amazon Android)](https://hexdocs.pm/pigeon/adm-amazon-android.html)

Looking for GCM? Try `v0.13` or earlier.
