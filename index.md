## Hypercore Protocol in Python

> [hypercore.protocol.org](https://hypercore-protocol.org)

A prole-to-prole implementation for the ones who write Python.

### Progress

- [ ] [simple-message-channels](https://github.com/Hyperpy/simple-message-channels)
- [x] [pyvarint](https://github.com/Hyperpy/pyvarint)
- [x] [hypercore-crypto](https://github.com/Hyperpy/hypercore-crypto)
- [x] [merkle-tree-stream](https://github.com/Hyperpy/merkle-tree-stream)
- [x] [flat-tree](https://github.com/Hyperpy/flat-tree)

### How to Help

Feel most welcome to join! It is a good idea to [come and say hello](#get-in-touch). We're friendly :rainbow:.

In general, the steps go something like this.

1. Look at [this graph](https://datcxx.github.io/hypercore.svg) of the Hypercore dependency graph and pick a module that is not already implemented and seems interesting to you.
1. Try to understand the high-level of what module is trying to achieve. Then, read the Javascript. If you need help from the implementors of that module, you can most likely find them hanging out in [the Hypercore protocol Discord server](https://discord.com/invite/ga5hxGf), they are also a friendly bunch.
1. Since Javascript is different from Python, you'll need to investigate if the ways of doing things in the Javascript module can be used on the Python side. For example, how NodeJS streams work will not easily translate to the way we use streams in Python. It is good to have an idea of what will need to be changed / created / adapted to before diving into the implementation.
1. Finally, go ahead and implement the module! You can use [this package cookiecutter](https://git.autonomic.zone/decentral1se/pypkgtemplate) to get started fast and use the same configuration as the other modules.

You can see the latest Python work at [github.com/hyperpy](https://github.com/hyperpy).

### Get in Touch

We're lurking in a few places...

- `#hyperpy` on [cabal.chat](https://cabal.chat/)
- `#hyperpy:autonomic.zone` on [matrix](https://riot.im/app/)
- `#hyperpy` on [freenode](https://webchat.freenode.net/)

### Other Implementations

- [datrs](https://github.com/datrs/)
- [datcxx](https://datcxx.github.io/)
