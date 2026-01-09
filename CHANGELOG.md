# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.12.1](https://github.com/lotusnoir/ansible-apps_java/compare/1.12.0...1.12.1) - 2026-01-09

### Commits

- fix wrong permission for script [`9ed12ef`](https://github.com/lotusnoir/ansible-apps_java/commit/9ed12ef71ce1eb3d5c6a4c192a33f5b71bc55f06)

## [1.12.0](https://github.com/lotusnoir/ansible-apps_java/compare/1.11.0...1.12.0) - 2026-01-08

### Commits

- update vars files for default version [`1f44980`](https://github.com/lotusnoir/ansible-apps_java/commit/1f4498061a633ccec77bc1485b00ae874fd34e1d)
- update core and molecule and add task in main to include success flag at the end to be able to monitor last playbook run [`cea567e`](https://github.com/lotusnoir/ansible-apps_java/commit/cea567eb82e0bf230f0a3d407d5d64a1fdfdd5ac)
- fix molecule paralelism and little updates [`3380880`](https://github.com/lotusnoir/ansible-apps_java/commit/3380880e9126811306221e349330f1463b9d54a4)
- add support for ubuntu24 [`16bb84c`](https://github.com/lotusnoir/ansible-apps_java/commit/16bb84cf8ebb08e22a259c93182f6a48586478f6)
- lowercase vars files [`79ef153`](https://github.com/lotusnoir/ansible-apps_java/commit/79ef153bef789fde98c8fa315d1a28ba92c1dbc6)
- add Debian12 var + retries on install [`4429cee`](https://github.com/lotusnoir/ansible-apps_java/commit/4429cee502d851e3d8f0fac1619575a863ec4164)
- sort testing distrib to avoid random changes [`32147df`](https://github.com/lotusnoir/ansible-apps_java/commit/32147dfd12b887f1c8523dc97cfac18048acb095)
- templating upgrade [`858ba4a`](https://github.com/lotusnoir/ansible-apps_java/commit/858ba4aa8c202640d1f71feac4b7e21f5109da65)
- templating upgrade [`442db10`](https://github.com/lotusnoir/ansible-apps_java/commit/442db1011c8058d44cabac7949c9eab41a1dbeb1)
- add debian12 support [`da6d48c`](https://github.com/lotusnoir/ansible-apps_java/commit/da6d48cd6e1c2bb821e366091e401b6507c75046)

## [1.11.0](https://github.com/lotusnoir/ansible-apps_java/compare/1.10.2...1.11.0) - 2023-01-26

### Commits

- update missing default vars [`a158660`](https://github.com/lotusnoir/ansible-apps_java/commit/a158660e2c681cd3f186ecc08f5a4fc75db73635)
- fix: remove useless and apply autofiles [`46d7a91`](https://github.com/lotusnoir/ansible-apps_java/commit/46d7a9131536079778e9e0490a6eeb794ba3a330)

## [1.10.2](https://github.com/lotusnoir/ansible-apps_java/compare/1.10.1...1.10.2) - 2021-11-05

### Commits

- fix rocky support [`3aacdb2`](https://github.com/lotusnoir/ansible-apps_java/commit/3aacdb2c875e9b738d8aac4018ded6956c7866cb)
- initial commit [`81efd31`](https://github.com/lotusnoir/ansible-apps_java/commit/81efd3147cbe545578e88d91a89424c50168dd00)

## [1.10.1](https://github.com/lotusnoir/ansible-apps_java/compare/1.10.0...1.10.1) - 2021-11-05

### Merged

- Fix #109: File permissions unset or incorrect [`#110`](https://github.com/lotusnoir/ansible-apps_java/pull/110)

### Fixed

- Merge pull request #110 from madhead/patch-1 [`#109`](https://github.com/lotusnoir/ansible-apps_java/issues/109)
- Fix #109: File permissions unset or incorrect [`#109`](https://github.com/lotusnoir/ansible-apps_java/issues/109)

### Commits

- change meta to include new os [`4557823`](https://github.com/lotusnoir/ansible-apps_java/commit/4557823fe1449ca90ed95e3fbc989354efb163e5)
- change meta to maintain iso [`a2e335c`](https://github.com/lotusnoir/ansible-apps_java/commit/a2e335c2454b85d591d118ef6f95136acd8cca81)
- change meta to maintain iso [`5ab92cd`](https://github.com/lotusnoir/ansible-apps_java/commit/5ab92cdd45202ae0a42fb56569cbab020f9ebe12)
- add support for deb11 and rocky/alma [`6a65439`](https://github.com/lotusnoir/ansible-apps_java/commit/6a654399a49f49c8d7a5ded784bf7f4b339918b8)
- Make sure bugs aren't automatically closed. [`86c6782`](https://github.com/lotusnoir/ansible-apps_java/commit/86c67822b3ea2df61db5a4d3b7d150035bda1e95)
- Remove ansible-lint from roles. [`a36aae9`](https://github.com/lotusnoir/ansible-apps_java/commit/a36aae98c9086eb34152b2b539143d325ab20476)
- Make ansible-lint work again. [`a0bcd36`](https://github.com/lotusnoir/ansible-apps_java/commit/a0bcd360ca0e2cb21af117852d947b643574cd1b)
- Drop support for RedHat / CentOS 6. [`fdc8595`](https://github.com/lotusnoir/ansible-apps_java/commit/fdc8595aaef60c2ac7f50004d2949360caa2ebba)
- Drop CentOS / RHEL 6 support. [`fd983ab`](https://github.com/lotusnoir/ansible-apps_java/commit/fd983ab5cdce1df6ff8130ff0ddbafddc184ed44)
- Dump Travis CI and move to GitHub Actions. [`2091e47`](https://github.com/lotusnoir/ansible-apps_java/commit/2091e47c2512415e9ccc84ba269a936e23cc9fc1)

## [1.10.0](https://github.com/lotusnoir/ansible-apps_java/compare/1.9.7...1.10.0) - 2020-05-01

### Merged

- Add Ubuntu 20.04 [`#100`](https://github.com/lotusnoir/ansible-apps_java/pull/100)

### Commits

- PR #100 follow-up x2: Use an int when comparing an int. [`14c5227`](https://github.com/lotusnoir/ansible-apps_java/commit/14c5227e897a9aefd8bbc840ad5224ecc215bc24)
- PR #100 follow-up: Make version handling a little easier for Ubuntu. [`aa48076`](https://github.com/lotusnoir/ansible-apps_java/commit/aa48076c6c08f9c205bbe9f8b95c14216f6a453e)
- Improve code [`d03a905`](https://github.com/lotusnoir/ansible-apps_java/commit/d03a9056088c74d2c9accd9e190a1e646cff2dd7)
- Remove whitespace [`1ffe747`](https://github.com/lotusnoir/ansible-apps_java/commit/1ffe747455a3d9e8f25287ce3691025191e2da65)
- Update main.yml [`439617a`](https://github.com/lotusnoir/ansible-apps_java/commit/439617adf4d30de98c6289bdf1469dc3158fbcd1)
- Update setup-Debian.yml [`5fc0f88`](https://github.com/lotusnoir/ansible-apps_java/commit/5fc0f889366be1e3b658fa3a9c9753fa7a488711)
- Delete Empty file [`46228e6`](https://github.com/lotusnoir/ansible-apps_java/commit/46228e6d49f10c8b7cf2783f08d461d33afdae81)
- Create Empty file [`c101508`](https://github.com/lotusnoir/ansible-apps_java/commit/c1015087dd11c12f926a125467176f23d03333d7)
- Create Ubuntu-20.yml [`85e7f69`](https://github.com/lotusnoir/ansible-apps_java/commit/85e7f691c5c763c2bc45060115e59e83f1b1ba96)
- Add ubuntu 20.04 [`0688369`](https://github.com/lotusnoir/ansible-apps_java/commit/0688369eded081e5541d6eae37e72afc31775149)

## [1.9.7](https://github.com/lotusnoir/ansible-apps_java/compare/1.9.6...1.9.7) - 2019-12-09

### Fixed

- Fixes #92: Add support for RHEL and CentOS 8. [`#92`](https://github.com/lotusnoir/ansible-apps_java/issues/92)

### Commits

- Update docs on versions and defaults. [ci skip] [`806bdc7`](https://github.com/lotusnoir/ansible-apps_java/commit/806bdc75c7a6a5761740457c68038075489a9071)

## [1.9.6](https://github.com/lotusnoir/ansible-apps_java/compare/1.9.5...1.9.6) - 2019-08-26

### Merged

- Make this role work fine with Debian 10. [`#90`](https://github.com/lotusnoir/ansible-apps_java/pull/90)
- Feature/debian 10 [`#1`](https://github.com/lotusnoir/ansible-apps_java/pull/1)

### Commits

- Add Fedora 30 to test suite. [`0012f85`](https://github.com/lotusnoir/ansible-apps_java/commit/0012f85278d4512dfe3871f91f833421970ec42e)
- Added Debian 10 to tests. [`2519818`](https://github.com/lotusnoir/ansible-apps_java/commit/25198181618e9c239cedf26176ecafac14193387)
- Added debian 10  management. [`0235496`](https://github.com/lotusnoir/ansible-apps_java/commit/02354963ae363df7398688a431c262a31969e72a)
- Update role name. [`47a7f53`](https://github.com/lotusnoir/ansible-apps_java/commit/47a7f5305e7a3ae4762f489e46fba5462bbf6098)
- Update main.yml [`389829c`](https://github.com/lotusnoir/ansible-apps_java/commit/389829c0fd2862f259750fc287e00ca2223e8411)
- Remove unused tests. [`b380413`](https://github.com/lotusnoir/ansible-apps_java/commit/b380413513177006b9641fd7ff960ea7d1051942)
- Remove debian8 tests as it is now failing and old. [`10b3bd7`](https://github.com/lotusnoir/ansible-apps_java/commit/10b3bd78b0510baa77f9a519817d90489f3fd83e)

## [1.9.5](https://github.com/lotusnoir/ansible-apps_java/compare/1.9.4...1.9.5) - 2018-12-01

### Merged

- [GH-74] optional java version check [`#75`](https://github.com/lotusnoir/ansible-apps_java/pull/75)
- It fails without become: yes under role [`#73`](https://github.com/lotusnoir/ansible-apps_java/pull/73)

### Commits

- PR #75 follow-up: Drop the unneccessary java_version check. [`13b4270`](https://github.com/lotusnoir/ansible-apps_java/commit/13b427055702d9e91558cad7dcccab7db91e5663)
- [GH-74] no new line at end of file [`663d8dc`](https://github.com/lotusnoir/ansible-apps_java/commit/663d8dcdefe0debe92d4f687f90c944e835c66fd)
- Fix lint issues picked up by galaxy-lint-rules. [`885dae9`](https://github.com/lotusnoir/ansible-apps_java/commit/885dae95ee41c6bd4d5564c5a44263db2fd1607e)

## [1.9.4](https://github.com/lotusnoir/ansible-apps_java/compare/1.9.3...1.9.4) - 2018-10-23

### Fixed

- Fixes #64: Ensure man directory exists so Docker container installs work. [`#64`](https://github.com/lotusnoir/ansible-apps_java/issues/64)

## [1.9.3](https://github.com/lotusnoir/ansible-apps_java/compare/1.9.2...1.9.3) - 2018-10-23

### Merged

- Do not use loop on package module with squash_actions [`#70`](https://github.com/lotusnoir/ansible-apps_java/pull/70)

### Commits

- Update tests for optimum efficiency. [`ba1f86b`](https://github.com/lotusnoir/ansible-apps_java/commit/ba1f86bf1da2718956f94474700f1849696988ba)
- Remove trailing white space to pass TravisCI check [`12c3957`](https://github.com/lotusnoir/ansible-apps_java/commit/12c395713cd85a294da6d336e864470d5f8317d4)

## [1.9.2](https://github.com/lotusnoir/ansible-apps_java/compare/1.9.1...1.9.2) - 2018-10-01

### Commits

- Increase debug verbosity for java version. [`717e66b`](https://github.com/lotusnoir/ansible-apps_java/commit/717e66bb25cdb5497b084fe9f7d2c235096d086c)
- Switch tests to use Molecule. [`c393b08`](https://github.com/lotusnoir/ansible-apps_java/commit/c393b08f14fbde447612c58471df7600e42164d7)
- Only display the Java version with higher verbosity levels. [`ac7caf9`](https://github.com/lotusnoir/ansible-apps_java/commit/ac7caf972f38dcfb1c8ca4a341e36f994767a942)

## [1.9.1](https://github.com/lotusnoir/ansible-apps_java/compare/1.9.0...1.9.1) - 2018-08-31

### Merged

- Fix breakage for RedHat distros [`#67`](https://github.com/lotusnoir/ansible-apps_java/pull/67)

## [1.9.0](https://github.com/lotusnoir/ansible-apps_java/compare/1.8.1...1.9.0) - 2018-08-30

### Merged

- Switch RHEL7 to openjdk8 [`#43`](https://github.com/lotusnoir/ansible-apps_java/pull/43)

### Fixed

- Fixes #64: Test builds failing due to a Debian Stretch and Ubuntu 18.04 bug with man dir missing. [`#64`](https://github.com/lotusnoir/ansible-apps_java/issues/64)

### Commits

- PR #43 follow-up: Remove redundant RedHat vars file. [`f6d8265`](https://github.com/lotusnoir/ansible-apps_java/commit/f6d826520ba281147493bd5cb75c77b35995b30e)
- fix include_vars for Ubuntu [`bc50720`](https://github.com/lotusnoir/ansible-apps_java/commit/bc5072044efe3df26861127bdd8be1e6c1c5e291)
- Issue #64: Allow failures of test build on Ubuntu 18.04. [`3ee0994`](https://github.com/lotusnoir/ansible-apps_java/commit/3ee099494f6785f91ae3e0ce88fa35b9b28d7f27)
- support for Ubuntu 18.04 [`6867239`](https://github.com/lotusnoir/ansible-apps_java/commit/686723907230af8df4155f8382830ec0d685b829)
- newline between blocks [`a326916`](https://github.com/lotusnoir/ansible-apps_java/commit/a326916fe81a9636dc78b1b17a942df904613dfa)
- ensure idempotency [`d98a937`](https://github.com/lotusnoir/ansible-apps_java/commit/d98a93700a1524c4f94592cf37078e300d8185b4)
- display java version at the end [`8d4a81d`](https://github.com/lotusnoir/ansible-apps_java/commit/8d4a81df65fb93e259174160e59c1da9668d43d1)
- fix small merge error [`a0b100e`](https://github.com/lotusnoir/ansible-apps_java/commit/a0b100e2b1e201c664e9297d9dde4e5a62c7f1aa)
- customize per centos/rhel version and switch v7 to opendk8 - required for elk5 [`178c334`](https://github.com/lotusnoir/ansible-apps_java/commit/178c334f25bfcfc8cff00e4315198946d9932c11)

## [1.8.1](https://github.com/lotusnoir/ansible-apps_java/compare/1.8.0...1.8.1) - 2018-05-10

### Merged

- Fixed the case sensitive issue for Ubuntu OS (Resolves #62) [`#63`](https://github.com/lotusnoir/ansible-apps_java/pull/63)

### Fixed

- Fixes #61: Support Ubuntu 18.04 Bionic. [`#61`](https://github.com/lotusnoir/ansible-apps_java/issues/61)
- Merge pull request #63 from kallaics-liferay/issue-62 [`#62`](https://github.com/lotusnoir/ansible-apps_java/issues/62)
- Fixed the case sensitive issue for Ubuntu [`#62`](https://github.com/lotusnoir/ansible-apps_java/issues/62)

## [1.8.0](https://github.com/lotusnoir/ansible-apps_java/compare/1.7.7...1.8.0) - 2018-04-26

### Merged

- refs #55 - remove deprecation warnings [`#60`](https://github.com/lotusnoir/ansible-apps_java/pull/60)

### Commits

- refs #55 - removed 'static' as requested [`1c24603`](https://github.com/lotusnoir/ansible-apps_java/commit/1c24603468b059df8939f51f9098d79a7dd6092c)

## [1.7.7](https://github.com/lotusnoir/ansible-apps_java/compare/1.7.6...1.7.7) - 2018-04-04

### Commits

- Fix deprecation warnings in Ansible 2.5 for state 'present'. [`77afc0e`](https://github.com/lotusnoir/ansible-apps_java/commit/77afc0ef847dbeffd14711e5002ea6d0ba6c996e)

## [1.7.6](https://github.com/lotusnoir/ansible-apps_java/compare/1.7.5...1.7.6) - 2018-02-18

### Commits

- Fix Galaxy meta/main.yml to parse Debian versions correctly. [`ebe72b1`](https://github.com/lotusnoir/ansible-apps_java/commit/ebe72b1b52fe0053bb156fd1b29d044f2048556b)

## [1.7.5](https://github.com/lotusnoir/ansible-apps_java/compare/1.7.4...1.7.5) - 2018-02-18

### Commits

- Update variable inclusion method to work correctly. [`73f9cf0`](https://github.com/lotusnoir/ansible-apps_java/commit/73f9cf0a8a6ca299939e39fcc552763cd2d240b3)
- Add some files missing from previous commit. [`35f1524`](https://github.com/lotusnoir/ansible-apps_java/commit/35f1524b10abbf482cdf8a2d26a199985f7de892)
- Add Debian-9-specific settings. [`834f938`](https://github.com/lotusnoir/ansible-apps_java/commit/834f9384292ded96c65bc8f0668f34c331576f2e)
- Test Fedora 27 instead of Fedora 24 and add Debian 9 tests. [`c611f90`](https://github.com/lotusnoir/ansible-apps_java/commit/c611f90e9490286c410ed97fdc0c27371d4edbf7)
- Update test script README. [ci skip] [`54e594a`](https://github.com/lotusnoir/ansible-apps_java/commit/54e594a32d91c6b3dc69c887fcd1872a6dd18b4b)
- Switch to more efficient and compact test setup. [`98e85fb`](https://github.com/lotusnoir/ansible-apps_java/commit/98e85fb1595cf5f60a89424fb8be10c68a5917d2)
- Add a LICENSE file for MIT license. [ci skip] [`6812f62`](https://github.com/lotusnoir/ansible-apps_java/commit/6812f62be6c7dca3be8c155d03b744cd9ed22933)

## [1.7.4](https://github.com/lotusnoir/ansible-apps_java/compare/1.7.3...1.7.4) - 2017-02-21

### Merged

- Make java_home non-empty string conditional explicit instead of bare variable [`#38`](https://github.com/lotusnoir/ansible-apps_java/pull/38)

### Commits

- Change java_home non-empty string conditional from bare variable to explicit [`235844f`](https://github.com/lotusnoir/ansible-apps_java/commit/235844ffcf9e05ca966fb44656fb495f36d16a2e)

## [1.7.3](https://github.com/lotusnoir/ansible-apps_java/compare/1.7.2...1.7.3) - 2017-02-07

### Merged

- Remove apt cache update [`#33`](https://github.com/lotusnoir/ansible-apps_java/pull/33)

### Commits

- Update the author's URL. Now with more HTTPS! [`9a54615`](https://github.com/lotusnoir/ansible-apps_java/commit/9a54615c80085a4a0c1adbc0201f76783bd0464a)

## [1.7.2](https://github.com/lotusnoir/ansible-apps_java/compare/1.7.1...1.7.2) - 2017-01-05

### Merged

- fix exported JAVA_HOME [`#30`](https://github.com/lotusnoir/ansible-apps_java/pull/30)

### Commits

- Fix test failures on Ubuntu 12.04. [`b0436ca`](https://github.com/lotusnoir/ansible-apps_java/commit/b0436caa193fd742cf1ff53243f83dde0477eae3)
- Fix test build failures. [`7f63946`](https://github.com/lotusnoir/ansible-apps_java/commit/7f63946f7168a11903862d47d083e008a2a03ec4)

## [1.7.1](https://github.com/lotusnoir/ansible-apps_java/compare/1.7.0...1.7.1) - 2016-11-02

### Fixed

- Fixes #26: 'java_packages' is undefined on Ansible 2.2. [`#26`](https://github.com/lotusnoir/ansible-apps_java/issues/26)

### Commits

- Remove sudo requirement from Travis build. [`4b0eac3`](https://github.com/lotusnoir/ansible-apps_java/commit/4b0eac30601ea741615280abfc28177a403ecbbb)
- One newline tweak. [`336c490`](https://github.com/lotusnoir/ansible-apps_java/commit/336c49065e7f7364009dc6b22669c9a98f9161f9)
- Remove sudo usage and clean up Travisfile slightly. [`4714111`](https://github.com/lotusnoir/ansible-apps_java/commit/47141118cd249633cb185c34c63650992ab22b17)
- Add Debian 8 test to Travis. [`d465d76`](https://github.com/lotusnoir/ansible-apps_java/commit/d465d7678e3b18b7addb8d21f512eb2f1802366f)
- Simpler test case. [`94e0e05`](https://github.com/lotusnoir/ansible-apps_java/commit/94e0e0555de71ba32d0cd7d97b10cbb0e9ac00fa)

## [1.7.0](https://github.com/lotusnoir/ansible-apps_java/compare/1.6.0...1.7.0) - 2016-09-17

### Commits

- Fix broken test on Ubuntu. [`240f222`](https://github.com/lotusnoir/ansible-apps_java/commit/240f222d3625149654c2f6f5766c7fa5b3b4ac95)
- Fix test build failures on Fedora and Ubuntu. [`ef9dcee`](https://github.com/lotusnoir/ansible-apps_java/commit/ef9dcee1a33ed77a5bddb0fd9e8a6be6a3d3e74d)
- Add automated Fedora test and better support. [`b46e739`](https://github.com/lotusnoir/ansible-apps_java/commit/b46e7393e9f70a021e81354f58e1539a23b0273f)

## [1.6.0](https://github.com/lotusnoir/ansible-apps_java/compare/1.5.1...1.6.0) - 2016-09-12

### Merged

- Issue #17: Add ability to set JAVA_HOME global env variable. [`#22`](https://github.com/lotusnoir/ansible-apps_java/pull/22)

## [1.5.1](https://github.com/lotusnoir/ansible-apps_java/compare/1.5.0...1.5.1) - 2016-09-10

### Commits

- Add Fedora to supported OSes. [`ced6b22`](https://github.com/lotusnoir/ansible-apps_java/commit/ced6b22a3f9dd2a94c36c2ae2b0d58e8c17d9e87)

## [1.5.0](https://github.com/lotusnoir/ansible-apps_java/compare/1.4.1...1.5.0) - 2016-09-10

### Merged

- Use the package module instead of yum [`#21`](https://github.com/lotusnoir/ansible-apps_java/pull/21)

## [1.4.1](https://github.com/lotusnoir/ansible-apps_java/compare/1.4.0...1.4.1) - 2016-09-02

### Merged

- Test under Ubuntu 16.04 [`#20`](https://github.com/lotusnoir/ansible-apps_java/pull/20)

### Commits

- Tweak to travis file. [`845c899`](https://github.com/lotusnoir/ansible-apps_java/commit/845c899a813f7040ddb5b215ebc49a74a5fb1e60)
- Adjust Travis file for easier maintenance. [`a0c453f`](https://github.com/lotusnoir/ansible-apps_java/commit/a0c453fdd5f10495763d66972c2b49cc72a70906)
- Use shorter valid time for apt cache. [`7c243d9`](https://github.com/lotusnoir/ansible-apps_java/commit/7c243d97b7bc022f85643c9f36be35f8b38c6d86)
- Check available packages. [`9aebefd`](https://github.com/lotusnoir/ansible-apps_java/commit/9aebefd12da3daba4b0f5bbe0cfa18259565b256)
- Add Ubuntu 16.04 to Travis test environments. [`732e7dc`](https://github.com/lotusnoir/ansible-apps_java/commit/732e7dcad7d2aad052d0c574d253f1c85848c910)
- Switch to using Docker registry containers for efficiency. [`6c41d19`](https://github.com/lotusnoir/ansible-apps_java/commit/6c41d1974572414bf6d1cc390f64b2f677fd145e)
- Typo. [`ea353fd`](https://github.com/lotusnoir/ansible-apps_java/commit/ea353fd637e59e1dd0cbf55cb50c0b7f8dc7f97b)
- Update idempotence test and use more correct apt state. [`909233f`](https://github.com/lotusnoir/ansible-apps_java/commit/909233fd2cb764542cde3a40230ea3be2baa741f)

## [1.4.0](https://github.com/lotusnoir/ansible-apps_java/compare/1.3.0...1.4.0) - 2016-04-22

### Fixed

- Fixes #16: Make role work out of the box with Ubuntu 16.04. [`#16`](https://github.com/lotusnoir/ansible-apps_java/issues/16)

### Commits

- Issue #16: Add missing variable files. [`d791727`](https://github.com/lotusnoir/ansible-apps_java/commit/d7917276a4846905f6c92d336b31b03a4e8faee7)

## [1.3.0](https://github.com/lotusnoir/ansible-apps_java/compare/1.2.1...1.3.0) - 2016-02-28

### Merged

- Fix deprecation warning [`#12`](https://github.com/lotusnoir/ansible-apps_java/pull/12)

### Commits

- Ansible version bump due to bare variable fix for 2.x. [`d41f5b1`](https://github.com/lotusnoir/ansible-apps_java/commit/d41f5b1eda591235e63858466b5bc4e5aa80002f)

## [1.2.1](https://github.com/lotusnoir/ansible-apps_java/compare/1.2.0...1.2.1) - 2016-02-17

### Merged

- Revert "fix raw variable deprecation warnings" [`#11`](https://github.com/lotusnoir/ansible-apps_java/pull/11)

### Commits

- Update README with better examples. [`05e8111`](https://github.com/lotusnoir/ansible-apps_java/commit/05e81110ddac79ae25599c7ae4490f6c192cb67f)

## [1.2.0](https://github.com/lotusnoir/ansible-apps_java/compare/1.1.1...1.2.0) - 2016-02-16

### Merged

- Document java8 [`#8`](https://github.com/lotusnoir/ansible-apps_java/pull/8)
- fix raw variable deprecation warnings [`#10`](https://github.com/lotusnoir/ansible-apps_java/pull/10)

### Commits

- PR #8 Follow-up. [`0e8b66c`](https://github.com/lotusnoir/ansible-apps_java/commit/0e8b66c0a3a3c91e9817baa0cf106bdaef231436)
- Add Dockerfiles so tests will actually run. [`07d3af0`](https://github.com/lotusnoir/ansible-apps_java/commit/07d3af02e61c98766c54c01b75b862c9ddddf663)
- Switch to Docker-based multiplatform tests. [`905dbf1`](https://github.com/lotusnoir/ansible-apps_java/commit/905dbf1014a6838f28a6bb90f23cc537187a733d)
- Update tests to notify Galaxy automatically. [`1f91352`](https://github.com/lotusnoir/ansible-apps_java/commit/1f913529f4d84a0ed7d43a71a5e1a3255865ad54)
- Update README.md [`65b8034`](https://github.com/lotusnoir/ansible-apps_java/commit/65b803446ccf96d125f4d49e5ddff718615efed6)
- Added instructions for Java 8 [`a0ca10c`](https://github.com/lotusnoir/ansible-apps_java/commit/a0ca10c0c438dcb0224c28769a2cdb146b737b6d)
- Added instructions for Java 8 [`e61828f`](https://github.com/lotusnoir/ansible-apps_java/commit/e61828fe984bb0d2960523255320b020b8a0c45a)

## [1.1.1](https://github.com/lotusnoir/ansible-apps_java/compare/1.1.0...1.1.1) - 2015-09-28

### Merged

- PR #9: FreeBSD support [`#9`](https://github.com/lotusnoir/ansible-apps_java/pull/9)

### Commits

- added FreeBSD support [`497de00`](https://github.com/lotusnoir/ansible-apps_java/commit/497de004fae949637401f843d9917defa4d4635a)
- added FreeBSD support [`975d0f7`](https://github.com/lotusnoir/ansible-apps_java/commit/975d0f74dbc4b20b7dcad31146e39c509725d54e)

## [1.1.0](https://github.com/lotusnoir/ansible-apps_java/compare/1.0.4...1.1.0) - 2014-11-10

### Commits

- Update README again. [`14df32c`](https://github.com/lotusnoir/ansible-apps_java/commit/14df32ccb7cb6060d3b11e1c702c2741684eda97)
- Update README. [`2fdc129`](https://github.com/lotusnoir/ansible-apps_java/commit/2fdc1296c3ca7ef4d6f506cb79c30386913806fe)
- Better cross-platform compatibility, default to OpenJDK 7. [`c4142da`](https://github.com/lotusnoir/ansible-apps_java/commit/c4142da57b02a7ee8312a430876e22f216e1ae90)
- Update test. [`91cb502`](https://github.com/lotusnoir/ansible-apps_java/commit/91cb502fc10966176f1bf78ba8e51e4922596850)

## [1.0.4](https://github.com/lotusnoir/ansible-apps_java/compare/1.0.3...1.0.4) - 2014-09-26

### Commits

- Issue #2: Update cache on Debian. [`b330db2`](https://github.com/lotusnoir/ansible-apps_java/commit/b330db23bf93498a0bb53e91b2fb925e9d65de3f)
- Install current version of Ansible when testing instead of 1.5.0. [`d310118`](https://github.com/lotusnoir/ansible-apps_java/commit/d310118848f387c4af87f00ccce5c0872e96e6fc)

## [1.0.3](https://github.com/lotusnoir/ansible-apps_java/compare/1.0.2...1.0.3) - 2014-07-14

### Commits

- Update docs and test file for java_packages var. [`4727349`](https://github.com/lotusnoir/ansible-apps_java/commit/472734929c9781ae9f1d09d37f4420da28f8f202)
- Add note on 'java_packages' variable. [`111be58`](https://github.com/lotusnoir/ansible-apps_java/commit/111be589df8a1e25678abb16c849bd78ef5b39ac)
- Remove main default. [`594825a`](https://github.com/lotusnoir/ansible-apps_java/commit/594825aa13e58b218b30765bef9100ad25986549)
- Issue #1: Fix for OpenJDK 7 cannot be installed. [`6a8ed11`](https://github.com/lotusnoir/ansible-apps_java/commit/6a8ed11bcdc60b958f825dfd7eb283f58c65ac4e)
- Another attempt to detect Java installation. [`c600594`](https://github.com/lotusnoir/ansible-apps_java/commit/c6005949ce240e462db594d24af6210ece8d8181)
- Update Travis command to check Java version. [`11d5ec6`](https://github.com/lotusnoir/ansible-apps_java/commit/11d5ec6b54a733dc4afc467b52b6a316e6342660)

## [1.0.2](https://github.com/lotusnoir/ansible-apps_java/compare/1.0.1...1.0.2) - 2014-05-06

### Commits

- Add Travis CI testing. [`0abdb2e`](https://github.com/lotusnoir/ansible-apps_java/commit/0abdb2ed94fc88d29762b18f2e556057447dc989)
- Move default vars to defaults. [`7bddbce`](https://github.com/lotusnoir/ansible-apps_java/commit/7bddbcefd460a94359e969e8b3dafd369b32e11c)
- Updated README.md [`705ae00`](https://github.com/lotusnoir/ansible-apps_java/commit/705ae008ece99a8a7fc02701d7352118d8ca17ca)

## [1.0.1](https://github.com/lotusnoir/ansible-apps_java/compare/1.0.0...1.0.1) - 2014-03-16

### Commits

- Add support for Debian/Ubuntu flavors. [`d22412e`](https://github.com/lotusnoir/ansible-apps_java/commit/d22412e52be4498c2296ee3fd1121df059ad1ec5)

## 1.0.0 - 2014-02-28

### Commits

- Initial commit. [`b431529`](https://github.com/lotusnoir/ansible-apps_java/commit/b4315296195cd8c2e4198c4a39878766423ae17e)
