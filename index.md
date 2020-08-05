## Hypercore Protocol in Python

> [hypercore-protocol.org](https://hypercore-protocol.org)

An implementation of the prole2prole protocol in Python.

### Progress

> [github.com/hyperpy](https://github.com/hyperpy)

- [ ] [simple-hypercore-protocol](https://github.com/hyperpy/simple-hypercore-protocol)
- [x] [simple-message-channels](https://github.com/hyperpy/simple-message-channels)
- [x] [pyvarint](https://github.com/hyperpy/pyvarint)
- [x] [hypercore-crypto](https://github.com/hyperpy/hypercore-crypto)
- [x] [merkle-tree-stream](https://github.com/hyperpy/merkle-tree-stream)
- [x] [flat-tree](https://github.com/hyperpy/flat-tree)

### Join In

Feel most welcome to join! Hyperpy is a non-commercial volunteer-run project
which currently receives no funding. We hope the funding situation will change
but right now, we're doing it because we think it is important and try to make
time for it alongside the rest of \$life. With that said, please do [come and
say hello](#get-in-touch)!

We are tracking our progress on [this project board](https://github.com/users/decentral1se/projects/1).

The two main needs we have right now are are 1. applying for grant funding 2.
python programming.

Regarding the programmming, we need help implementing the remaining modules
that make up the dependency graph of Hypercore. That does involve some pretty
gnarly Python programming. Some modules are easier than others, so its good to
pick something that interests you. In general, the process of implementing a
module looks like this.

1. Look at [this graph](https://datcxx.github.io/hypercore.svg) of the
   Hypercore dependency graph and pick a module that is not already implemented
   and seems interesting to you. You can generally find the corresponding
   source code under [github.com/mafintosh/](https://github.com/mafintosh/) or
   [github.com/hypercore-protocol](https://github.com/hypercore-protocol/).
1. Firstly, try to understand the high-level of what module is trying to
   achieve. Then, try to browse and grok the Javascript. If you need help from
   the implementors of that module, you can most likely find them hanging out
   in [the Hypercore protocol Discord
   server](https://discord.com/invite/ga5hxGf) or on IRC at the `#dat` channel
   on the Freenode network.
1. Before starting, you'll need to investigate if the ways of doing things in
   the Javascript module can be translated to Python. For example, how NodeJS
   streams work will not easily translate to the way we use streams in Python.
   It is good to have an idea of what will need to be changed / created /
   adapted to before diving into the implementation.
1. Finally, go ahead and implement the module! If you like, you can use [this
   Python package
   cookiecutter](https://git.autonomic.zone/decentral1se/pypkgtemplate) to get
   started quick and use the same configuration as the other modules.

### Get in Touch

We're lurking in a few places...

- `#hyperpy` on [cabal.chat](https://cabal.chat/)
- `#hyperpy:autonomic.zone` on [matrix](https://riot.im/app/)
- `#hyperpy` on [freenode](https://webchat.freenode.net/)
- `#hyperpy` on [scuttlebutt](https://www.scuttlebutt.nz/)

### Other Implementations

- [Datrs](https://github.com/datrs/)
- [Datcxx](https://datcxx.github.io/)
