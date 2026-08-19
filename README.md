# Fabrice Kirchner

Infrastructure as Code, mostly for my own homelab: Ansible roles and
collections, a GitOps-managed k3s cluster, container stacks for mail and web,
a few Hugo sites — plus solar monitoring and home automation on the side.

> [!NOTE]
> Everything is developed on my own Forgejo instance. Repositories anywhere
> else are mirrors, kept around so working together stays easy.

## Where the code lives

- Personal: [git.zyria.de](https://git.zyria.de/)
- Work: [git.casa-due-pur.de](https://git.casa-due-pur.de/)
- Mirrors: [Codeberg](https://codeberg.org/ricariel) ·
  [GitHub](https://github.com/ricariel)

## Worth a look

Most of it is public. These are the ones people actually reuse:

- [ansible-collection-unixoid](https://git.zyria.de/pyrox/ansible-collection-unixoid)
  — the base configuration every one of my machines gets
- [ansible-collection-podman](https://git.zyria.de/pyrox/ansible-collection-podman)
  and [ansible-collection-docker](https://git.zyria.de/pyrox/ansible-collection-docker)
  — container runtimes and the stacks that run on them
- [postfix-docker](https://git.zyria.de/pyrox/postfix-docker) ·
  [dovecot-docker](https://git.zyria.de/pyrox/dovecot-docker) ·
  [rspamd-docker](https://git.zyria.de/pyrox/rspamd-docker)
  — the mail stack behind zyria.de
- [renovate-config](https://git.zyria.de/pyrox/renovate-config) and
  [actions](https://git.zyria.de/pyrox/actions)
  — shared presets and CI actions keeping some thirty repositories in sync
- [nft-blacklist](https://git.zyria.de/pyrox/nft-blacklist)
  — ban large numbers of IP addresses with nftables

Take what you need; every repository ships its own license.

## Found something broken?

Registration on my instance is closed, so you cannot open an issue there.
Ping me on Mastodon instead — or, for the few repositories mirrored to
[GitHub](https://github.com/ricariel), open the issue right there.

## Contact

- <a href="https://kirchner.social/@fabrice" rel="me">@fabrice@kirchner.social</a>
- [zyria.de](https://zyria.de)
