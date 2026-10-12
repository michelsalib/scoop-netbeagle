# Scoop bucket for netbeagle

[netbeagle](https://github.com/michelsalib/netbeagle) shows which process (or container) listens on each
port, who can reach it, who is connected to it, and how everything on your machine connects.

```powershell
scoop bucket add netbeagle https://github.com/michelsalib/scoop-netbeagle
scoop install netbeagle/netbeagle
```

This installs the standalone `netbeagle.exe` from the GitHub release. Update with
`scoop update netbeagle`. Run it from an administrator terminal to see other users' command lines too.

`bucket/netbeagle.json` is generated for each release by `scripts/packages.ts` in the netbeagle
repository, from the release's `SHA256SUMS`.
