# Fabrice Kirchner

I run my own infrastructure and publish most of the pieces: Ansible
collections that configure the hosts, container images for mail, DNS and the
web stack, the Hugo modules behind my sites, and the CI presets keeping some
thirty repositories in sync. Solar monitoring and home automation happen on
the side. The k3s cluster and the inventories stay private — the rest is out
here.

> [!NOTE]
> Everything is developed on my own Forgejo instance. What you find anywhere
> else is a mirror of it, and [Codeberg](https://codeberg.org/ricariel) is the
> one where you can reach me.

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

## Questions, bugs, patches

Registration on my instance is closed, so you cannot open an issue there.
Use the [Codeberg mirror](https://codeberg.org/ricariel) instead, or write me
on Mastodon. Pull requests are the one thing that will not survive: the mirror
force-pushes on every change and overwrites whatever was created on the far
side. Send a patch or an issue and I will carry it home myself.

## Contact

- <a href="https://kirchner.social/@fabrice" rel="me">@fabrice@kirchner.social</a>
- [zyria.de](https://zyria.de)
