Lager maps patch
================

This patch make possible for [lager](https://github.com/basho/lager) to work with maps

Add to your reabr.config file:

```erlang
{post_hooks, [
    {'get-deps', "./patches/run.sh"}
]}.
```
