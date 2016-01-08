rebar3_requirejs_plugin
=====

A rebar plugin

Build
-----

    $ rebar3 compile

Use
---

Add the plugin to your rebar config:

    {plugins, [
        { rebar3_requirejs_plugin, ".*", {git, "git@host:user/rebar3_requirejs_plugin.git", {tag, "0.1.0"}}}
    ]}.

Then just call your plugin directly in an existing application:


    $ rebar3 rebar3_requirejs_plugin
    ===> Fetching rebar3_requirejs_plugin
    ===> Compiling rebar3_requirejs_plugin
    <Plugin Output>
