Lager maps patch
================

This patch make possible for [lager](https://github.com/basho/lager) to work with maps

Add to your reabr.config file:

```erlang
{deps, [
    {lager, ".*" , {git, "git://github.com/basho/lager.git", {tag, "2.0.0"}}}
].

{post_hooks, [
    {'get-deps', "./patches/run.sh"}
]}.
```
