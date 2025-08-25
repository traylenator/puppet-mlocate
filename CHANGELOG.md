# Changelog

All notable changes to this project will be documented in this file.
Each new release typically also includes the latest modulesync defaults.
These should not affect the functionality of the module.

## [v4.0.0](https://github.com/voxpupuli/puppet-mlocate/tree/v4.0.0) (2025-08-25)

[Full Changelog](https://github.com/voxpupuli/puppet-mlocate/compare/v3.0.0...v4.0.0)

**Breaking changes:**

- Drop puppet, update openvox minimum version to 8.19 [\#69](https://github.com/voxpupuli/puppet-mlocate/pull/69) ([TheMeier](https://github.com/TheMeier))

**Implemented enhancements:**

- Added Ubuntu 22.04 and 24.04 as supported OS [\#74](https://github.com/voxpupuli/puppet-mlocate/pull/74) ([traylenator](https://github.com/traylenator))
- Allow puppet-systemd v9 [\#73](https://github.com/voxpupuli/puppet-mlocate/pull/73) ([traylenator](https://github.com/traylenator))
- Support Debian 13 \(trixie\) [\#71](https://github.com/voxpupuli/puppet-mlocate/pull/71) ([traylenator](https://github.com/traylenator))
- puppet/cron: Allow 5.x [\#68](https://github.com/voxpupuli/puppet-mlocate/pull/68) ([TheMeier](https://github.com/TheMeier))
- metadata.json: Add OpenVox [\#66](https://github.com/voxpupuli/puppet-mlocate/pull/66) ([jstraw](https://github.com/jstraw))
- puppet systemd 9 [\#59](https://github.com/voxpupuli/puppet-mlocate/pull/59) ([jay7x](https://github.com/jay7x))

**Merged pull requests:**

- Remove redundant \(EL7\) cron cases [\#72](https://github.com/voxpupuli/puppet-mlocate/pull/72) ([traylenator](https://github.com/traylenator))

## [v3.0.0](https://github.com/voxpupuli/puppet-mlocate/tree/v3.0.0) (2025-01-21)

[Full Changelog](https://github.com/voxpupuli/puppet-mlocate/compare/v2.1.0...v3.0.0)

**Breaking changes:**

- drop support for Fedora 36,37,38 add support for Fedora 40,41 [\#63](https://github.com/voxpupuli/puppet-mlocate/pull/63) ([TheMeier](https://github.com/TheMeier))
- drop support for RedHat 7, CentOS 7/8, OracleLinux, ScientificLinux [\#62](https://github.com/voxpupuli/puppet-mlocate/pull/62) ([TheMeier](https://github.com/TheMeier))
- Support plocate alternative to mlocate [\#42](https://github.com/voxpupuli/puppet-mlocate/pull/42) ([traylenator](https://github.com/traylenator))
- Drop Puppet 6 support [\#40](https://github.com/voxpupuli/puppet-mlocate/pull/40) ([bastelfreak](https://github.com/bastelfreak))

**Implemented enhancements:**

- Stub out settings to match/extend EL10's default config [\#60](https://github.com/voxpupuli/puppet-mlocate/pull/60) ([jcpunk](https://github.com/jcpunk))
- update puppet-systemd upper bound to 8.0.0 [\#54](https://github.com/voxpupuli/puppet-mlocate/pull/54) ([TheMeier](https://github.com/TheMeier))
- puppet/cron: Allow 4.x [\#50](https://github.com/voxpupuli/puppet-mlocate/pull/50) ([zilchms](https://github.com/zilchms))
- puppet/systemd: Allow 6.x [\#49](https://github.com/voxpupuli/puppet-mlocate/pull/49) ([zilchms](https://github.com/zilchms))
- Declare Puppet 8 support [\#45](https://github.com/voxpupuli/puppet-mlocate/pull/45) ([traylenator](https://github.com/traylenator))
- Allow  stdlib v9, cron v3 and systemd v6 [\#44](https://github.com/voxpupuli/puppet-mlocate/pull/44) ([traylenator](https://github.com/traylenator))
- Support Debian 11, 12 and Archlinux [\#43](https://github.com/voxpupuli/puppet-mlocate/pull/43) ([traylenator](https://github.com/traylenator))
- bump puppet/systemd to \< 5.0.0 [\#38](https://github.com/voxpupuli/puppet-mlocate/pull/38) ([jhoblitt](https://github.com/jhoblitt))

**Fixed bugs:**

- Fix `force_update` on Archlinux [\#51](https://github.com/voxpupuli/puppet-mlocate/pull/51) ([Valantin](https://github.com/Valantin))
- fix tests [\#47](https://github.com/voxpupuli/puppet-mlocate/pull/47) ([zilchms](https://github.com/zilchms))
- Don't index /var/cache/{dnf,yum} on RedHat systems [\#37](https://github.com/voxpupuli/puppet-mlocate/pull/37) ([jcpunk](https://github.com/jcpunk))

## [v2.1.0](https://github.com/voxpupuli/puppet-mlocate/tree/v2.1.0) (2022-07-03)

[Full Changelog](https://github.com/voxpupuli/puppet-mlocate/compare/v2.0.0...v2.1.0)

**Implemented enhancements:**

- Add package\_names parameter [\#32](https://github.com/voxpupuli/puppet-mlocate/pull/32) ([jcpunk](https://github.com/jcpunk))
- Add EL9 support [\#31](https://github.com/voxpupuli/puppet-mlocate/pull/31) ([jcpunk](https://github.com/jcpunk))

**Merged pull requests:**

- adapt to rubocop 1.22.3 [\#30](https://github.com/voxpupuli/puppet-mlocate/pull/30) ([traylenator](https://github.com/traylenator))

## [v2.0.0](https://github.com/voxpupuli/puppet-mlocate/tree/v2.0.0) (2021-11-25)

[Full Changelog](https://github.com/voxpupuli/puppet-mlocate/compare/v1.1.0...v2.0.0)

**Breaking changes:**

- Drop Puppet 5 support; enable Puppet 7 support [\#23](https://github.com/voxpupuli/puppet-mlocate/pull/23) ([bastelfreak](https://github.com/bastelfreak))
- Drop EoL Centos 6 support [\#22](https://github.com/voxpupuli/puppet-mlocate/pull/22) ([bastelfreak](https://github.com/bastelfreak))

**Implemented enhancements:**

- camptocamp/systemd: allow 3.x [\#21](https://github.com/voxpupuli/puppet-mlocate/pull/21) ([bastelfreak](https://github.com/bastelfreak))
- puppetlabs/stdlib: Allow 7.x [\#20](https://github.com/voxpupuli/puppet-mlocate/pull/20) ([bastelfreak](https://github.com/bastelfreak))

**Merged pull requests:**

- Allow stdlib 8.0.0 [\#25](https://github.com/voxpupuli/puppet-mlocate/pull/25) ([smortex](https://github.com/smortex))
- switch from camptocamp/systemd to voxpupuli/systemd [\#24](https://github.com/voxpupuli/puppet-mlocate/pull/24) ([bastelfreak](https://github.com/bastelfreak))
- modulesync 3.0.0 & puppet-lint updates [\#17](https://github.com/voxpupuli/puppet-mlocate/pull/17) ([bastelfreak](https://github.com/bastelfreak))
- Use voxpupuli-acceptance [\#16](https://github.com/voxpupuli/puppet-mlocate/pull/16) ([ekohl](https://github.com/ekohl))
- Give example a title in strings doc [\#7](https://github.com/voxpupuli/puppet-mlocate/pull/7) ([traylenator](https://github.com/traylenator))

## [v1.1.0](https://github.com/voxpupuli/puppet-mlocate/tree/v1.1.0) (2020-02-14)

[Full Changelog](https://github.com/voxpupuli/puppet-mlocate/compare/v1.0.0...v1.1.0)

**Fixed bugs:**

- Add username field to /etc/cron.d entries / introduce puppet/cron as new dependency [\#12](https://github.com/voxpupuli/puppet-mlocate/pull/12) ([traylenator](https://github.com/traylenator))
- Reset OnCalendar event in Timer before adding new one. [\#6](https://github.com/voxpupuli/puppet-mlocate/pull/6) ([traylenator](https://github.com/traylenator))

**Merged pull requests:**

- Correct parameter name in documentation [\#11](https://github.com/voxpupuli/puppet-mlocate/pull/11) ([traylenator](https://github.com/traylenator))
- Allow puppetlabs/stdlib 6.x [\#10](https://github.com/voxpupuli/puppet-mlocate/pull/10) ([dhoppe](https://github.com/dhoppe))

## [v1.0.0](https://github.com/voxpupuli/puppet-mlocate/tree/v1.0.0) (2019-11-28)

[Full Changelog](https://github.com/voxpupuli/puppet-mlocate/compare/f3ac25fb28c8e78f37ee8b1e673ce6e742670f4e...v1.0.0)

**Merged pull requests:**

- Add badges and LICENSE file. [\#2](https://github.com/voxpupuli/puppet-mlocate/pull/2) ([traylenator](https://github.com/traylenator))
- First version of puppet-mlocate [\#1](https://github.com/voxpupuli/puppet-mlocate/pull/1) ([traylenator](https://github.com/traylenator))



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
