---
layout: default
title: 'wp cache get'
display_global_parameters: true
---

<small>[Commands](/commands/) &raquo; [cache](/commands/cache/) &raquo; get</small>

`wp cache get` - Get a value from the object cache.

<small>Quick links: <a href="https://github.com/wp-cli/wp-cli/issues?q=is%3Aopen+label%3Acommand%3Acache-get+sort%3Aupdated-desc">Github issues</a></small>

<hr />

Errors if the value doesn't exist.

### OPTIONS

&lt;key&gt;
: Cache key.

[&lt;group&gt;]
: Method for grouping data within the cache which allows the same key to be used across groups.

### EXAMPLES

    # Get cache.
    $ wp cache get my_key my_group
    my_value



