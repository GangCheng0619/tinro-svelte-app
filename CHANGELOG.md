# Tinro Changelog

## unreleased

### Documentation

- 📝 Fix typo [`d5fd8025`](https://github.com/WebpassionStar/tinro-svelte-app/commit/d5fd8025d5a6ef39179e867b6b71e22733702d32)

    *Thx to @sevensidedmarble for its PR*

### Other

- Merge branch 'master' of github.com:AlexxNB/tinro [`338b6e74`](https://github.com/WebpassionStar/tinro-svelte-app/commit/338b6e74aca4979c678a6b764b2db780aa205bd5)

## 0.6.7 - 2021-09-03

### Features

- Add method to set base path for router ([#88](https://github.com/WebpassionStar/tinro-svelte-app/issues/88)) [`b25b92ba`](https://github.com/WebpassionStar/tinro-svelte-app/commit/b25b92baddf9a0d12a2cb3742a2ba16694541772)

    *resolve #88*

## 0.6.6 - 2021-08-18

### Bug Fixes

- Links with query or fragments are not have active class [`4ed77bd0`](https://github.com/WebpassionStar/tinro-svelte-app/commit/4ed77bd0bfe0f9f2677cc4475861e488a8f21a2c)

    *#85*
- Unmounted routes not to be deleted from parent's active childs. [`224b2911`](https://github.com/WebpassionStar/tinro-svelte-app/commit/224b29113ca8b622a394395955da44d58a3d40ec)

    *#84*

### Other

- Merge pull request #83 from ItsiAdam/patch-1 ([#83](https://github.com/WebpassionStar/tinro-svelte-app/issues/83)) [`69126b64`](https://github.com/WebpassionStar/tinro-svelte-app/commit/69126b64bbc604e56b600817e1a72605bb7f796b)

    *fix typo :-)*
- fix typo :-) [`c17451ad`](https://github.com/WebpassionStar/tinro-svelte-app/commit/c17451ad04ca77508e30f6e774ea945057f09b10)
- Merge branch 'master' of github.com:AlexxNB/tinro [`27970965`](https://github.com/WebpassionStar/tinro-svelte-app/commit/279709655e2234592ce77af289301342aa042cd9)

## 0.6.5 - 2021-07-22

### Chores

- ⬆️ Upgrade dependencies [`7366e190`](https://github.com/WebpassionStar/tinro-svelte-app/commit/7366e1900fa60e374df40d57dda797673d049040)

### Tests

- ✨ Use uvu for tests running [`8c941454`](https://github.com/WebpassionStar/tinro-svelte-app/commit/8c941454c5ea9505ca6d54567ed7a5b0349c837d)

## 0.6.4 - 2021-05-06

### Code Refactoring

- 🏗 Create proto object for root and other routes [`8821a549`](https://github.com/WebpassionStar/tinro-svelte-app/commit/8821a549b9a4b3ad89026e10affbd9fb36299c01)

## 0.6.3 - 2021-05-06

### Code Refactoring

- 🏗 Add root component for all Routes, so no more any differences between root and nonrot routes [`530bde08`](https://github.com/WebpassionStar/tinro-svelte-app/commit/530bde08145f40f4a1d4886af0127a5ab1f1178a)

## 0.6.2 - 2021-05-06

### Bug Fixes

- 📝 Add forgeted link in table of content [`6812a773`](https://github.com/WebpassionStar/tinro-svelte-app/commit/6812a77300303314e14f2b13dbdce75a93013c3f)

### Documentation

- 📝 Add note for Vite users [`e0c7409b`](https://github.com/WebpassionStar/tinro-svelte-app/commit/e0c7409b2376370864d071e46112611d192002c5)
- 📝 Add reciepe about announcer ([#60](https://github.com/WebpassionStar/tinro-svelte-app/issues/60)) [`19ea8811`](https://github.com/WebpassionStar/tinro-svelte-app/commit/19ea88116e2a36ac55cac8bb9054bf310a783a26)

    *Thanks to @kindoflew*
- 📝 Add notice about using meta() inside Route only [`8bff8321`](https://github.com/WebpassionStar/tinro-svelte-app/commit/8bff8321070fc5dfc7160634b1a00a03830d16f0)

### Other

- update versions [`71f41f91`](https://github.com/WebpassionStar/tinro-svelte-app/commit/71f41f9110a5a532926f2e07c244d2c4f27f3a40)
- Add test for conditional redirects [`90345c27`](https://github.com/WebpassionStar/tinro-svelte-app/commit/90345c277e154e630e6e4c5e1644f53598f26e48)

### Code Refactoring

- Remove useless(i hope) tick in redirect [`117045fd`](https://github.com/WebpassionStar/tinro-svelte-app/commit/117045fdb7794daa75f8f616e400425d08ff16f5)

## 0.6.1 - 2021-03-18

### Documentation

- 🚸 Add error message when use meta out of `Route` context. ([#58](https://github.com/WebpassionStar/tinro-svelte-app/issues/58)) [`428dc256`](https://github.com/WebpassionStar/tinro-svelte-app/commit/428dc2563e7dc40d439b0e12da6fce7138b7c6cf)

    *[#58](https://github.com/AlexxNB/tinro/issues/58)*

### Other

- refactoring [`cfdd01ad`](https://github.com/WebpassionStar/tinro-svelte-app/commit/cfdd01add6c44482ec540e19922544da4b2ba46a)

### Chores

- ⬆️ Upgrade [`d1c285d2`](https://github.com/WebpassionStar/tinro-svelte-app/commit/d1c285d256a054bbf80f1aaa39df45434284dd03)

## 0.6.0 - 2021-03-06

### Features

- Add methods to set query and hash part of URL [`a0bd0ea3`](https://github.com/WebpassionStar/tinro-svelte-app/commit/a0bd0ea320044372b9a4db1215484101b8ccb859)

## 0.5.15 - 2021-02-26

## 0.5.14 - 2021-02-26

### Other

- refactroing merged PR workaround for redirects in hash mode [`61282915`](https://github.com/WebpassionStar/tinro-svelte-app/commit/61282915676ae06ecdbca07061b8bec896d4afba)
- revert change to npmignore [`32c34ade`](https://github.com/WebpassionStar/tinro-svelte-app/commit/32c34adec5f0f3b23b532289a0afc62986d91b5e)
- change to npmignore and gitignore [`32926015`](https://github.com/WebpassionStar/tinro-svelte-app/commit/32926015b4ec59c0e77b71b7f0cdee4438cf18e4)
- removes dist files [`abe47b7d`](https://github.com/WebpassionStar/tinro-svelte-app/commit/abe47b7d802817e3760b9a02a5289b3b602f705c)
- build [`383799d7`](https://github.com/WebpassionStar/tinro-svelte-app/commit/383799d7f5073755a8aca26a21c689a4137cb95c)
- fix types, change goto behavior [`c4e1f4a6`](https://github.com/WebpassionStar/tinro-svelte-app/commit/c4e1f4a633d57687dce98da36e2333ef24f262df)
- Add "replace" option for routes (#1) [`a4a5cc15`](https://github.com/WebpassionStar/tinro-svelte-app/commit/a4a5cc15ad798b9c59d68c807f7df2a731a8aea4)

## 0.5.13 - 2021-02-25

### Other

- remove src from npmignore [`4c6cf210`](https://github.com/WebpassionStar/tinro-svelte-app/commit/4c6cf2102469f0ab5274f13f0c73d5b9980337cd)
- update deps [`1dc4bab1`](https://github.com/WebpassionStar/tinro-svelte-app/commit/1dc4bab1734211553e88debf9ec491ecbc87379d)
- minor fixes [`bf2680cc`](https://github.com/WebpassionStar/tinro-svelte-app/commit/bf2680ccbb834c01d6d80fb2f3a6656990eeaa08)
- Merge pull request #54 from mateomorris/master ([#54](https://github.com/WebpassionStar/tinro-svelte-app/issues/54)) [`333bd58c`](https://github.com/WebpassionStar/tinro-svelte-app/commit/333bd58ce7e53a9dc79eefd2dda4390aa8315bad)

    *Use 'meta' in example instead of 'params'*
- Use 'meta' in example instead of 'params' [`55a8b3b5`](https://github.com/WebpassionStar/tinro-svelte-app/commit/55a8b3b5a9717a891f7dbca27b7eb420f2b77945)

## 0.5.12 - 2021-02-03

### Other

- separate meta from router [`cf98dc96`](https://github.com/WebpassionStar/tinro-svelte-app/commit/cf98dc964ab3e84eb0cae085dad7094b04aa7413)

## 0.5.11 - 2021-01-29

### Other

- resolve [#50](https://github.com/AlexxNB/tinro/issues/50) ([#50](https://github.com/WebpassionStar/tinro-svelte-app/issues/50)) [`5fda2e68`](https://github.com/WebpassionStar/tinro-svelte-app/commit/5fda2e68ba9394ffb1545f89b0b7440407ac3623)

## 0.5.10 - 2021-01-29

### Other

- fix [#50](https://github.com/AlexxNB/tinro/issues/50)#issuecomment-769808395 ([#50](https://github.com/WebpassionStar/tinro-svelte-app/issues/50)) [`3ef1807d`](https://github.com/WebpassionStar/tinro-svelte-app/commit/3ef1807dec68921b0aeaa36d76a5346c75d56bca)

## 0.5.9 - 2021-01-26

### Other

- resolve [#49](https://github.com/AlexxNB/tinro/issues/49) ([#49](https://github.com/WebpassionStar/tinro-svelte-app/issues/49)) [`c2f0b509`](https://github.com/WebpassionStar/tinro-svelte-app/commit/c2f0b5093be1ac174dd46b7cf4b1eb5613dd1523)

## 0.5.8 - 2021-01-19

### Other

- fix parent in redirects [`b41c70db`](https://github.com/WebpassionStar/tinro-svelte-app/commit/b41c70dba34158bab1f869662c5c6d230c35a0a1)
- Merge pull request #48 from kindoflew/edit-readme ([#48](https://github.com/WebpassionStar/tinro-svelte-app/issues/48)) [`b0d88834`](https://github.com/WebpassionStar/tinro-svelte-app/commit/b0d8883460ab55e2e21a8ad3a8626ec2a98f6095)

    *edit README and COMPARE*
- edit README and COMPARE [`f5ba3c18`](https://github.com/WebpassionStar/tinro-svelte-app/commit/f5ba3c18e7a771f8310d97b295b222ac7136c3fb)

## 0.5.7 - 2021-01-17

### Other

- make Route props reactive [`cd887cef`](https://github.com/WebpassionStar/tinro-svelte-app/commit/cd887cefe5f578fb6e16a6158f5591cfecb52698)

## 0.5.6 - 2021-01-08

### Other

- fix hash change listener [#42](https://github.com/AlexxNB/tinro/issues/42) ([#42](https://github.com/WebpassionStar/tinro-svelte-app/issues/42)) [`a3bf6670`](https://github.com/WebpassionStar/tinro-svelte-app/commit/a3bf6670a46923f8178c69743b0a934623bcd65c)

## 0.5.5 - 2021-01-07

### Other

- fix format [`3030ae8e`](https://github.com/WebpassionStar/tinro-svelte-app/commit/3030ae8ed7880061e05e785b23a612d939c682ae)

## 0.5.4 - 2021-01-07

### Other

- build correct module bundles [`fe41d544`](https://github.com/WebpassionStar/tinro-svelte-app/commit/fe41d5441907f32c5d49c1f549ad7aeaa9843156)
- add meta.query in contents [`344227e8`](https://github.com/WebpassionStar/tinro-svelte-app/commit/344227e8b63633ae2886c40b2b7acebb71825e11)

## 0.5.3 - 2021-01-04

### Other

- fix [`2b55c849`](https://github.com/WebpassionStar/tinro-svelte-app/commit/2b55c849e6b245753126f07a7d477fedc8a33a59)

## 0.5.2 - 2021-01-04

### Other

- refactoring [`97e21a4c`](https://github.com/WebpassionStar/tinro-svelte-app/commit/97e21a4c2639ce571b6a85b81210bceb23090c6d)
- added in memory navigation refactoring [`18112939`](https://github.com/WebpassionStar/tinro-svelte-app/commit/18112939e8600312e825a6145f4e0181148054e6)
- update API [`4c992386`](https://github.com/WebpassionStar/tinro-svelte-app/commit/4c992386f647e71c24362836add73f6108ee2a4d)

## 0.5.1 - 2021-01-02

### Other

- edit Readme [`820d0ad1`](https://github.com/WebpassionStar/tinro-svelte-app/commit/820d0ad1e9805bc4f3bdc72016460e44c68498b3)

## 0.5.0 - 2021-01-02

### Other

- new route meta data [`90cf366d`](https://github.com/WebpassionStar/tinro-svelte-app/commit/90cf366dfad09359b03cd5c43eabd9c339929c7a)

## 0.4.11 - 2021-01-02

### Other

- add params for slot definition [`4e3d8b8f`](https://github.com/WebpassionStar/tinro-svelte-app/commit/4e3d8b8f5dfe11331ba8805ddc45dbb5c7cb2159)

## 0.4.10 - 2020-12-30

### Other

- fix build [`2accbcc4`](https://github.com/WebpassionStar/tinro-svelte-app/commit/2accbcc44e8880e5c6dba9acdcefebb55946cdb3)

## 0.4.9 - 2020-12-30

### Other

- use esbuild for bundling instead rollup [`7b78a8e6`](https://github.com/WebpassionStar/tinro-svelte-app/commit/7b78a8e653044645149bb2f99a8913f7fba67431)
- fix readme [`54df547e`](https://github.com/WebpassionStar/tinro-svelte-app/commit/54df547e2f60eaeacf534045835f82b8a3e7d756)

## 0.4.8 - 2020-12-30

## 0.4.7 - 2020-12-30

### Other

- add firstmatch property resolve [#39](https://github.com/AlexxNB/tinro/issues/39) resolve [#31](https://github.com/AlexxNB/tinro/issues/31) resolve [#7](https://github.com/AlexxNB/tinro/issues/7) ([#39](https://github.com/WebpassionStar/tinro-svelte-app/issues/39), [#31](https://github.com/WebpassionStar/tinro-svelte-app/issues/31), [#7](https://github.com/WebpassionStar/tinro-svelte-app/issues/7)) [`5dfe18ba`](https://github.com/WebpassionStar/tinro-svelte-app/commit/5dfe18ba8094457ec9a15ebf926f30656aa8fa7a)

## 0.4.6 - 2020-12-16

### Other

- fix links [`c367e21c`](https://github.com/WebpassionStar/tinro-svelte-app/commit/c367e21cfae180b5c833db1b08834af8088b30b3)

## 0.4.5 - 2020-12-09

### Other

- fix hashed links [`a51fe97e`](https://github.com/WebpassionStar/tinro-svelte-app/commit/a51fe97eb5fef7650cffacd429db391d3684293d)

## 0.4.4 - 2020-12-09

### Other

- refactoring [`264800b4`](https://github.com/WebpassionStar/tinro-svelte-app/commit/264800b476413b902ed37877d6d521a8a9e31a8e)
- Merge pull request #30 from jacobmischka/fix-click-handler ([#30](https://github.com/WebpassionStar/tinro-svelte-app/issues/30)) [`ebb5da32`](https://github.com/WebpassionStar/tinro-svelte-app/commit/ebb5da32fc62e49fdf3c719d46107c07a9623e65)

    *Check for anchor before attempting to get href*
- Check for anchor before attempting to get href [`5f1b8f47`](https://github.com/WebpassionStar/tinro-svelte-app/commit/5f1b8f47ef3c26bcb1604493fe9357641ee4fd7f)

## 0.4.3 - 2020-12-09

### Other

- fix relative links [`f13ca307`](https://github.com/WebpassionStar/tinro-svelte-app/commit/f13ca30793f1c4ee0fb26efc5d15bd6fbb4c7631)

## 0.4.2 - 2020-12-04

### Other

- add error messages [`506e364c`](https://github.com/WebpassionStar/tinro-svelte-app/commit/506e364c73339f9993b25b8097141fa0d6fae8b4)

## 0.4.1 - 2020-12-03

## 0.4.0 - 2020-12-03

### Other

- new routes matching conception [`1daec5cd`](https://github.com/WebpassionStar/tinro-svelte-app/commit/1daec5cd60294abb89f199a13d303a2253563db1)

## 0.3.7 - 2020-09-30

### Other

- Merge pull request #26 from blissini/master ([#26](https://github.com/WebpassionStar/tinro-svelte-app/issues/26)) [`aacae437`](https://github.com/WebpassionStar/tinro-svelte-app/commit/aacae43782313277402feac6223f9fc9355507e9)

    *fixed typos in README*

## 0.3.6 - 2020-09-30

### Other

- updtae Readme with key operator [`4ab64089`](https://github.com/WebpassionStar/tinro-svelte-app/commit/4ab640897fb882d9fd1bd75bd41550e62e39f212)
- update versions [`2da13945`](https://github.com/WebpassionStar/tinro-svelte-app/commit/2da13945a09d0fcaaae800785199695516f15892)
- fixed some typos in README [`ac3747df`](https://github.com/WebpassionStar/tinro-svelte-app/commit/ac3747df1202c3c051e375d5d9f2c2b8d76a81cd)
- Merge pull request #24 from AlexxNB/dependabot/npm_and_yarn/bl-4.0.3 ([#24](https://github.com/WebpassionStar/tinro-svelte-app/issues/24)) [`ac2420cc`](https://github.com/WebpassionStar/tinro-svelte-app/commit/ac2420cc626a4b6b9ec978a90d4dedaaf8ef6692)

    *Bump bl from 4.0.2 to 4.0.3*
- Bump bl from 4.0.2 to 4.0.3 [`e76202c7`](https://github.com/WebpassionStar/tinro-svelte-app/commit/e76202c77a16d9433e2aebc5b24bcdfec8ae9f5a)

    *Bumps [bl](https://github.com/rvagg/bl) from 4.0.2 to 4.0.3. - [Release notes](https://github.com/rvagg/bl/releases) - [Commits](https://github.com/rvagg/bl/compare/v4.0.2...v4.0.3)*

## 0.3.5 - 2020-09-01

### Other

- oops [`e857652d`](https://github.com/WebpassionStar/tinro-svelte-app/commit/e857652d6be0f39ec3ebd43aa149295c649f6a70)

## 0.3.4 - 2020-09-01

### Other

- type deffinition for the Router component [`599d344a`](https://github.com/WebpassionStar/tinro-svelte-app/commit/599d344a8328b535df1281c3fcf507831cd7eb88)

## 0.3.3 - 2020-08-14

### Other

- fix [#16](https://github.com/AlexxNB/tinro/issues/16) ([#16](https://github.com/WebpassionStar/tinro-svelte-app/issues/16)) [`bb5601b5`](https://github.com/WebpassionStar/tinro-svelte-app/commit/bb5601b5926e8e770dc2f5953d4d3108de1300fb)
- update deps [`362c061f`](https://github.com/WebpassionStar/tinro-svelte-app/commit/362c061fb44dbd0c91def85ace4a238ed7f704c7)

## 0.3.2 - 2020-08-13

### Other

- update deps [`e257c1b3`](https://github.com/WebpassionStar/tinro-svelte-app/commit/e257c1b3f64cec80b3565d57e4a3b871dd5d4935)

## 0.3.1 - 2020-07-29

### Other

- Merge pull request #19 from jnordberg/master ([#19](https://github.com/WebpassionStar/tinro-svelte-app/issues/19)) [`6cf7ddd4`](https://github.com/WebpassionStar/tinro-svelte-app/commit/6cf7ddd4f37f93beec303cd8f33331f59bec174b)

    *Improve TypeScript types*
- Extension apparently has to be in separate declaration to be picked up [`00ed1a8c`](https://github.com/WebpassionStar/tinro-svelte-app/commit/00ed1a8c31eee660143c1ed771b6dca3c4a9d190)
- Fix types [`0a1e2a0f`](https://github.com/WebpassionStar/tinro-svelte-app/commit/0a1e2a0fa86670ff8e640b3483ac839b813c82d1)
- add types [`a95b317a`](https://github.com/WebpassionStar/tinro-svelte-app/commit/a95b317a8d2fcb9eedabcefaf38a5b632d70a6dc)
- add gzipped size in compare [`a7c95757`](https://github.com/WebpassionStar/tinro-svelte-app/commit/a7c9575734a9583a6791089f631c2f7a63041d06)
- add error handling [`8e092740`](https://github.com/WebpassionStar/tinro-svelte-app/commit/8e0927407b60ecff29914c2df47e3a8ae4ab8657)

## 0.3.0 - 2020-07-27

### Other

- add relative redirects [`820434de`](https://github.com/WebpassionStar/tinro-svelte-app/commit/820434deca892c8ebf7eff9ceffbbb7a05d27653)
- huge refactoring, use store for routes logic [`38571e9f`](https://github.com/WebpassionStar/tinro-svelte-app/commit/38571e9f7495b268d6fc8f4d864c398146e6b1a5)

## 0.2.10 - 2020-05-26

### Other

- fix [#15](https://github.com/AlexxNB/tinro/issues/15) ([#15](https://github.com/WebpassionStar/tinro-svelte-app/issues/15)) [`fd3ee117`](https://github.com/WebpassionStar/tinro-svelte-app/commit/fd3ee11743d87f31185749766293f5bdcb0e59c0)

## 0.2.9 - 2020-05-16

### Other

- remove browser bundle [`f50e7eec`](https://github.com/WebpassionStar/tinro-svelte-app/commit/f50e7eec609ccbfd640f8d8ffba334517ff91b66)
- Merge pull request #13 from ronthecookie/patch-1 ([#13](https://github.com/WebpassionStar/tinro-svelte-app/issues/13)) [`445dedaa`](https://github.com/WebpassionStar/tinro-svelte-app/commit/445dedaa7f2a6f3c45768161d2e2d052affd1b8c)

    *Fix typo in README*
- Fix typo in README [`f99667b4`](https://github.com/WebpassionStar/tinro-svelte-app/commit/f99667b443f09e2c1f17e57387ce61490d4c04ce)

## 0.2.8 - 2020-05-14

### Other

- fix [#12](https://github.com/AlexxNB/tinro/issues/12) ([#12](https://github.com/WebpassionStar/tinro-svelte-app/issues/12)) [`31697435`](https://github.com/WebpassionStar/tinro-svelte-app/commit/3169743521db5e2a049ea467ef195219d4c26b8b)

## 0.2.7 - 2020-05-12

### Other

- fix ignore attribute remove after first click [`855e9a08`](https://github.com/WebpassionStar/tinro-svelte-app/commit/855e9a08cb3ba1a71376a2ee24710a670159d253)

## 0.2.6 - 2020-05-10

### Other

- add guarded routes recipe from [#9](https://github.com/AlexxNB/tinro/issues/9) ([#9](https://github.com/WebpassionStar/tinro-svelte-app/issues/9)) [`0f1891c1`](https://github.com/WebpassionStar/tinro-svelte-app/commit/0f1891c100d7902903f784ebd5b71d112511f7a3)

## 0.2.5 - 2020-05-09

### Other

- add tinro-ignore options propsed at [#11](https://github.com/AlexxNB/tinro/issues/11) ([#11](https://github.com/WebpassionStar/tinro-svelte-app/issues/11)) [`ee284f9a`](https://github.com/WebpassionStar/tinro-svelte-app/commit/ee284f9ade400b126dd350a60575ad723e79aa95)

## 0.2.4 - 2020-04-28

### Other

- add [#4](https://github.com/AlexxNB/tinro/issues/4) ([#4](https://github.com/WebpassionStar/tinro-svelte-app/issues/4)) [`3f753f03`](https://github.com/WebpassionStar/tinro-svelte-app/commit/3f753f03d588974553eaccebd46d3928e60b750d)
- More universal Lazy component [`43b99b4c`](https://github.com/WebpassionStar/tinro-svelte-app/commit/43b99b4ccc9dfebf85ba3d5bd708a3eed7778657)
- Merge pull request #6 from frederikhors/patch-2 ([#6](https://github.com/WebpassionStar/tinro-svelte-app/issues/6)) [`4a6b18bd`](https://github.com/WebpassionStar/tinro-svelte-app/commit/4a6b18bd68c6d9a1a57f2d23dfc28cb1954a31cf)

    *Misprints*
- Merge pull request #5 from frederikhors/patch-1 ([#5](https://github.com/WebpassionStar/tinro-svelte-app/issues/5)) [`a3a92440`](https://github.com/WebpassionStar/tinro-svelte-app/commit/a3a92440d991c19612e895cca22a53316de10ec2)

    *Misprint*
- Misprints [`6561e257`](https://github.com/WebpassionStar/tinro-svelte-app/commit/6561e257ee24c1316e1ec03b9b07260bb5a3c06e)
- Misprint [`d5e45bc4`](https://github.com/WebpassionStar/tinro-svelte-app/commit/d5e45bc4a82bd31f0aa00bc2ef0c62e014be078c)
- minor edits in readme [`9a9a050d`](https://github.com/WebpassionStar/tinro-svelte-app/commit/9a9a050d036f8c165920343c539cf2ca12426987)
- fix link [`c0bc0b3f`](https://github.com/WebpassionStar/tinro-svelte-app/commit/c0bc0b3f9474d397ee59237f23ab7c3769d046a8)
- fix typo [`e58698b6`](https://github.com/WebpassionStar/tinro-svelte-app/commit/e58698b6b9e736d4ab741bb58ebb108ee2fb6b96)

## 0.2.3 - 2020-04-27

### Other

- Add recipies [`810da4b1`](https://github.com/WebpassionStar/tinro-svelte-app/commit/810da4b1c9d02e94968c116a8207ad1bd1fc31fe)

## 0.2.2 - 2020-04-25

### Other

- fix, active action doesn't work with hashed style path [`b73f9b53`](https://github.com/WebpassionStar/tinro-svelte-app/commit/b73f9b53b071fd9fcca6b5eb75e78168ff5dc0cb)
- fix typo [`ece58bb7`](https://github.com/WebpassionStar/tinro-svelte-app/commit/ece58bb75d16502057f5ad0ec675e6e4b79f7ef2)

## 0.2.1 - 2020-04-25

### Other

- add active action to mark active links [`e7237515`](https://github.com/WebpassionStar/tinro-svelte-app/commit/e7237515841974b1d48016d9248de80e2c85b80a)
- add tests [`91ea0fb3`](https://github.com/WebpassionStar/tinro-svelte-app/commit/91ea0fb33ca12154274fbd71397eb253b6ab7ba5)
- fix build bage [`ce6b5fa9`](https://github.com/WebpassionStar/tinro-svelte-app/commit/ce6b5fa93db24213cf8860404bbbf35c7df20f84)
- fix test [`e9cff078`](https://github.com/WebpassionStar/tinro-svelte-app/commit/e9cff0783d28e51820e537a026f675c1749b160c)
- add badges [`38760ed8`](https://github.com/WebpassionStar/tinro-svelte-app/commit/38760ed885c58caac515b425e62949deffdef916)
- add REPL example [`29a6bd74`](https://github.com/WebpassionStar/tinro-svelte-app/commit/29a6bd744250e13cca57ebf2d614a1ef9e3b7664)
- add test for hash navigation [`7e541530`](https://github.com/WebpassionStar/tinro-svelte-app/commit/7e541530f4af64c9b67c781b678f6480663ee338)
- add hash feature in list [`bf21ade4`](https://github.com/WebpassionStar/tinro-svelte-app/commit/bf21ade420f2e8951db577d6d18afda87b6803ed)

## 0.2.0 - 2020-04-18

### Other

- add hash navigation method [`400e5314`](https://github.com/WebpassionStar/tinro-svelte-app/commit/400e5314f02b855408253cd79bb9988d28c373bc)
- edit Readme [`78fd5291`](https://github.com/WebpassionStar/tinro-svelte-app/commit/78fd529142356be9af94b91b57b1ea99aa60e00d)
- fix error message [`4f1f0571`](https://github.com/WebpassionStar/tinro-svelte-app/commit/4f1f057169364ce8e346f08e526f277bd3bfc557)
- impliment unholded rejection in script [`2931991c`](https://github.com/WebpassionStar/tinro-svelte-app/commit/2931991c9545633f2ca9f745616cb1a5186fa185)
- fix unkilled dev server [`41a4be31`](https://github.com/WebpassionStar/tinro-svelte-app/commit/41a4be31c7febbb1dcf4bdf891d6109f6a2cd946)
- fail test on error with promises [`2896df05`](https://github.com/WebpassionStar/tinro-svelte-app/commit/2896df054543230022ac90b786e4a42a7c196d12)
- add npm publish workflow [`6acc9398`](https://github.com/WebpassionStar/tinro-svelte-app/commit/6acc9398aa8ddf3a43a6ac72494f1fbdcfbcd87d)
- fix import for Route [`bf91b5aa`](https://github.com/WebpassionStar/tinro-svelte-app/commit/bf91b5aae81623db3b78d997acf6afbe1f733f79)
- add table of contents [`b1fd9ca2`](https://github.com/WebpassionStar/tinro-svelte-app/commit/b1fd9ca22f94aacfd00e135eaa77ff3658c7a794)
- add install chapter [`69e9346b`](https://github.com/WebpassionStar/tinro-svelte-app/commit/69e9346b889fa6f112707e866801eaaa24d85bec)
- add readme [`1f528f2d`](https://github.com/WebpassionStar/tinro-svelte-app/commit/1f528f2db7c8b527b47d48edaff645d86b679284)
- add fallback tests [`a07c98d2`](https://github.com/WebpassionStar/tinro-svelte-app/commit/a07c98d215cd3a4d68fc005211b4c4cd03263ac0)
- add links test [`3ee12b1f`](https://github.com/WebpassionStar/tinro-svelte-app/commit/3ee12b1fbfaeaa91028a9adfa3bb76d60f7a18b9)
- add helpers in page object [`eb3fd195`](https://github.com/WebpassionStar/tinro-svelte-app/commit/eb3fd195d4861ef761ae5c8d98d273564b8df398)
- add some tests [`89e46c05`](https://github.com/WebpassionStar/tinro-svelte-app/commit/89e46c051f5ba9f7c59cf76ece21dd65b11c26c0)
- new tests stack using tape-modern+puppeteer [`40eb6f98`](https://github.com/WebpassionStar/tinro-svelte-app/commit/40eb6f9874fadf4eac44c195f70a9c71397dce20)
- Move redirect to separate test [`0e321442`](https://github.com/WebpassionStar/tinro-svelte-app/commit/0e32144249c81d6e548b912974f95423c99286c4)
- make compare result generation [`566ed332`](https://github.com/WebpassionStar/tinro-svelte-app/commit/566ed3327ab475619f6eac8dc4963b069340164d)
- add test for page loading [`7497589a`](https://github.com/WebpassionStar/tinro-svelte-app/commit/7497589a4819d92cf92a17f2ca87657d01b57604)
- break test on pieces in set directory [`4387ab9b`](https://github.com/WebpassionStar/tinro-svelte-app/commit/4387ab9bea0639228d018d411671e49e9ac75036)
- setup test tooling [`d5e9d72e`](https://github.com/WebpassionStar/tinro-svelte-app/commit/d5e9d72ebfe1fa131b642dd85f6518ef64f339cf)
- compare setup to determine the value of the tinro [`504c952b`](https://github.com/WebpassionStar/tinro-svelte-app/commit/504c952b127957da22c242f8012b3a4b2540ba40)
- add some tests [`f9db3329`](https://github.com/WebpassionStar/tinro-svelte-app/commit/f9db3329b63d0ba482e24bff760c730c875304d8)
- fix non exact redirects [`7fa3abdd`](https://github.com/WebpassionStar/tinro-svelte-app/commit/7fa3abdd9db16b1e65bed026a99ea43ea2ca21ee)
- fix redirect [`12ec47bc`](https://github.com/WebpassionStar/tinro-svelte-app/commit/12ec47bc4173a2d020e93c49c598382f6a07f1da)
- add redirect property [`385302c8`](https://github.com/WebpassionStar/tinro-svelte-app/commit/385302c81f02747dc47687a91c5ee20d425e0851)
- remove test bundles from git [`7494cc92`](https://github.com/WebpassionStar/tinro-svelte-app/commit/7494cc923a634f4a3c7842e5158ccc7622ad2c9a)
- add params in router [`71d4252b`](https://github.com/WebpassionStar/tinro-svelte-app/commit/71d4252b1cf1253beb519c46ed74b1d4db590c42)
- some refactoring [`efa465f2`](https://github.com/WebpassionStar/tinro-svelte-app/commit/efa465f2f78d92aa3902a1a19d431d76ff184780)
- rebrending [`a058da0a`](https://github.com/WebpassionStar/tinro-svelte-app/commit/a058da0ac5231b125c4942a3af385b08fe59cccb)
- initial commit [`6119fb8d`](https://github.com/WebpassionStar/tinro-svelte-app/commit/6119fb8db6be396e231b79949a2c2a7c4fdb4431)
- Initial commit [`bdd75907`](https://github.com/WebpassionStar/tinro-svelte-app/commit/bdd75907b75e03096a75c236aa9c7f4b4d51e34e)