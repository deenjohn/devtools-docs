(Note: these files are copied and built nightly from the mozilla repo
 [here](https://github.com/mozilla/gecko-dev/tree/master/devtools/docs).
 You read the [built version](http://mozilla.github.io/devtools-docs/))

# Firefox Developer Tools

Hello! This documentation is for developers who want to work on the
developer tools. If you are looking for general docs about how to use
the tools, checkout [this MDN
page](https://developer.mozilla.org/en-US/docs/Tools).

These docs explain how the developer tools work at high-level, as well
as providing links to reference documentation. This is a good starting
point if you are a new contributor, or want to learn how our protocol,
a specific tool, or something else works.

If you are looking to start hacking on the developer tools, all of
this information is documented on the
[Hacking](https://wiki.mozilla.org/DevTools/Hacking) wiki page.

A very quick version:

```
$ hg clone http://hg.mozilla.org/integration/fx-team
$ ./mach build
$ ./mach run -P development
```

You can also clone via git from
`https://github.com/mozilla/gecko-dev.git`. Note that the workflow for
submitting patches may be a little different if using git.

Please see the [Hacking](https://wiki.mozilla.org/DevTools/Hacking)
page for a lot more information!