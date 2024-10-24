Should work:
- [Path aliases](Path%20aliases.md) — regular link
- [Path aliases](Path%20aliases) — without `.md`
- [Path aliases](<Path aliases.md>) — non-encoded with angle braces
- [Path aliases](<Path aliases>) — without `.md`, non-encoded with angle braces

May be not supported:
- [Path aliases](Path aliases.md) — non-encoded
- [Path aliases](Path aliases) — without `.md`, non-encoded

In tables:

| Link                      | type                                            | GitLab | GitHub | Obsidian |
| ------------------------- | ----------------------------------------------- | ------ | ------ | -------- |
| [link](Path%20aliases.md) | regular                                         | ✅      | ✅      | ✅        |
| [link](Path%20aliases)    | without `.md`                                   | ❌      | ❌      | ✅        |
| [link](<Path aliases.md>) | non-encoded with angle braces                   | ✅      | ✅      | ✅        |
| [link](<Path aliases>)    | without `.md`,<br>non-encoded with angle braces | ❌      | ❌      | ✅        |
| [link](Path aliases.md)   | non-encoded                                     | ✅<br>  | ❌      | ❌        |
| [link](Path aliases)      | without `.md`, non-encoded                      | ✅      | ❌      | ❌        |

