---
layout: default
title: 'wp cache incr'
display_global_parameters: true
---

<small>[Commands](/commands/) &raquo; [cache](/commands/cache/) &raquo; incr</small>

`wp cache incr` - Increment a value in the object cache.

<small>Quick links: <a href="https://github.com/wp-cli/wp-cli/issues?q=is%3Aopen+label%3Acommand%3Acache-incr+sort%3Aupdated-desc">Github issues</a></small>

<hr />

Errors if the value can't be incremented.

### OPTIONS

&lt;key&gt;
: Cache key.

[&lt;offset&gt;]
: The amount by which to increment the item's value. Default is 1.

[&lt;group&gt;]
: Method for grouping data within the cache which allows the same key to be used across groups.

### EXAMPLES

    # Increase cache value.
    $ wp cache incr my_key 2 my_group
    50



