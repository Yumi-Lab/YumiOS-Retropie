<!-- THIS FILE IS UPDATED AUTOMATICALLY, ANY CHANGES WILL BE OVERRIDDEN -->
# Changelog
All notable changes to Mainsail will be documented in this file.

## [unreleased]
### Features

- **build**: Removed raspicam and serialcomm module (#83) | [27e8e7c](27e8e7cea78d436b3f47c24f471bb6d2ac6ce3ec)
- **moonraker.conf**: Add mainsail subscription to announcements (#115) | [a45c67e](a45c67efd3750be80bc05b54372835f2af1d5dc5)
- Add park to CANCEL_PRINT (#58) | [00169c7](00169c709b8d144f70849e1d0b7ed43a349c6772)
- Replaced module busterpatch (#77) | [abaeec6](abaeec6f10eb255d470c680608e6fa99b63cbbd0)
- Added .editorconfig (#78) | [67ae0d4](67ae0d4750788bf66fe891fbffcfa8381e2043cf)
- Changed logging and logrotate behavior (#79) | [83988ea](83988ea1da37080a1cc3025b4245617fbb9c907c)
- Added mainsailos module (#81) | [744cee9](744cee90fdbb2156297757224ea9dc128ec5eb0f)
- Stop part fan on CANCEL_PRINT (#103) | [cd69f53](cd69f53dfbb484cd4916c874dd66fba7910313c8)
- Add sonar by default to image (#107) | [33185db](33185db546f4cda6c4ee3a423745c301eb40b163)
- Add on_error_gcode to mainsail.cfg (#116) | [0dc5944](0dc5944b2c99f8b05a7e30ea2360de60647b32f1)
- Add on_error_gcode to mainsail.cfg (#116) | [0b383d5](0b383d57262834d3198cc8fcd90f0e5028a92781)
- Add python3-serial CanBoot dependency (#129) | [1f59f0f](1f59f0f0db4ef653dafec0e04f18b3b08b639606)
- Add postrename module (#128) | [942896c](942896c8c9899763f64f6e58c00570584ab528e0)
- Add timelapse module (#130) | [7b99d1f](7b99d1f02fdab98a3a314cb090c1f3de6c02a203)

### Bug Fixes and Improvements

- **build**: Updated download paths (#65) | [0622a2f](0622a2f60a8e39237c1fd213d67932ae6c986e08)
- **build**: Fixes error in Makefile (#76) | [0ff09b5](0ff09b5ac0503e8cee0c35a298a41a26344b57c8)
- **build**: Updated torrent download url (#90) | [a16126c](a16126c08733f96f6db7b067e7fa12d12324569b)
- **config.txt**: Fix configuration errors with attached screens (#119) | [81c335e](81c335eb6cb7d54de2b5433611f13dfefff2f5d7)
- **crowsnest**: Fix install of crowsnest (#111) | [e8eee5f](e8eee5fc07df000cebf3ff7379454a3efce0042b)
- **lint**: Should fix shellcheck warnings (#160) | [2569dd2](2569dd25db5c719c3e55d299062c5664c3c038b0)
- **mainsail**: Changed download url to mainsail-crew url (#92) | [b6dc45d](b6dc45d7aab8279e78ac131ff06b0a2852153273)
- **sonar**: Fixes missing moonraker update manager entry (#112) | [924ce38](924ce38dc78c0de93101562365e6bb47461db7bc)
- **ustreamer**: Disable buffering on webcam proxy entries (#84) | [1dd32e8](1dd32e8083defea09998c17a1b4d01c2ad83aad9)
- Nginx config file | [e3ea7e7](e3ea7e7e928513f803effbb038a5c48b5ee11228)
- Added http1.1 to moonraker api reverse proxy location (#75) | [8f548d2](8f548d2fd6b18faf0097a2e7b00b538b1a390d5b)
- Correct on_error_gcode in mainsail.cfg (#118) | [f0e3ee3](f0e3ee38acd2a9934dcd4ff01e78b1989bae6bfc)
- Correct on_error_gcode in mainsail.cfg (#118) | [e20f357](e20f357b498f16ccfa7eccf09f32fc5ee5389f99)
- Fix errors in moved venvs (#138) | [cb8a822](cb8a82201bf92fd0cb2bc21e8134a76e6f42b89f)
- Fixes error unusable wpa_supplicant.txt (#142) | [53cb819](53cb81958474766c3dfdcfcd2ea2e8fe708e0bd8)
- Fix postrename script (#150) | [dbcee22](dbcee227cd2ac8cc5999f8a3fdaeada5aad52937)
- Fix shellcheck errors in net module (#161) | [687b02f](687b02f7cdb99808b2e04487c4bc83d47c1c4fa4)
- Set wrong source path (#164) | [fc95133](fc95133045de95af56ef25525e69fe175d527298)
- Add otg_mode=1 for CM4 in config.txt (#167) | [cb0bf60](cb0bf600e8526a79ae534a64e9fccd584eb20388)
- Fix SC2086 in armbian module (#173) | [2f4f8b1](2f4f8b13737b3f95582b9c8b824136413e9884eb)
- Fixes error setting link to macro (#175) | [d1ad3f8](d1ad3f8006ad7c9b84a9a34acc4798f15ab605e4)
- Fix shellcheck errors (#185) | [efe1b68](efe1b68d0a8cd5ccf3238d280c83ae523c331688)
- Fix syntax error in net module (#191) | [cb890af](cb890afafaa1ab6dc68fbfdc103ceca61432e064)

### Refactor

- **klipper**: Refactor klipper and is-pre-install module (#113) | [1a8cd48](1a8cd482f8059675f925092af55a4281f786312a)
- **mainsail.cfg**: Substituting `/home/pi` with `~` (#114) | [338eb8e](338eb8e8e3d86b0cf2714cd574229089d7889d40)
- **mainsail.cfg**: Substituting `/home/pi` with `~` (#114) | [51f4940](51f4940143497d0b5d53faa73b1584e108f90e5f)
- Updated input shaper dependencies to python3 (#74) | [3f78c07](3f78c07513d1533267aa16dc56dd8f6735cb3c74)
- Add `enable_auto_refresh: True` (#133) | [1b78efb](1b78efb963537a3a6dad5910ff201ba19cee2103)
- Deactivate IPv6 in nginx per default (#157) | [40b3719](40b37192608e13b4f5e97b295840715a42974fb6)
- Change behavior of piconfig module (#180) | [825af74](825af74061c48043c1ae8390c0825d2220bd623f)

### Documentation

- Improve reamde.md (#54) | [3e6d1a5](3e6d1a5d62dcdd12d9c2672908ee801b6dc71733)
- Fix typo in readme.md (#91) | [6ffadca](6ffadca6669f3ce8e2140ed27dddd1a2af1bbea2)
- Correct screenshot image URL (#93) | [03677f1](03677f16ef73df8ca348c25b01eeb21e289b633b)
- Add mainsailos logo (#124) | [0664678](0664678dca265eb898dd18581e2250c5dda34302)
- Update README for improved readability (#144) | [af3d78b](af3d78bdb9eb5090f3b3a092d98c28b0ac25d147)
- Adds faq section | [96c21d5](96c21d5fb1782c9ba80207ff30efd14760f607c3)

### Other

- **README**: Update README according to latest changes. (#110) | [e4ec596](e4ec596da09b131b19b838762b2495f183f2c01c)
- **build**: Refactor build dependend files (#154) | [d0d6375](d0d63759c18968b6fabcdf2e30040367fbdedcde)
- **crowsnest**: Update crowsnest module (#123) | [4d034c8](4d034c81acd7fd099faf6a5e7e5c65a8de1ea7a8)
- **docs**: Fix urls, add includes (#122) | [0b0b0e0](0b0b0e0c7586fd592596606fbaaf45d2464c0f23)
- **klipper**: Update klipper and input shaper to py3 (#105) | [180724b](180724b28629849026b81f7ebb92e5c2a9630b50)
- **moonraker**: Refactored moonraker module (#89) | [e5155fd](e5155fd717ab2f86a13230810b6140973946e89f)
- **workflow**: Rework release workflow for multi builds (#181) | [eacef2f](eacef2f77d3204ff4f642988d5b8a8ef87b18a1a)
- **workflows**: Update pull_request trigger | [32464f2](32464f2c648d5bd32c718b873e7c013866a99113)
- Update default moonraker.conf | [cdea2ec](cdea2ecbd121c0ec350b6cecaa5e925714f08a11)
- Remove job_queue and postprocessing from moonraker.conf | [19d2b9d](19d2b9deb9e294d25393d9696d99e8d7af65a71e)
- Updated .editorconfig for yml files (#86) | [7cbf70b](7cbf70b8eb1ee20b2b26ecaa13e3ebbf85d9ef96)
- Push versionnumber to 0.6.1 | [0059e9f](0059e9f24bb5e072f317b7e122eea9e5f5e94b78)
- Update moonraker.conf (#101) | [0b196ca](0b196ca00554475878348e370d2b9d3b4a5760dd)
- Add funding informations (#120) | [c43b00c](c43b00cea8f4fae1a76cfa66b39063efe7df85a0)
- Add Issue Templates (#121) | [381b600](381b600d7210fee1da811973b61515b876601063)
- Bump version to 0.7.0 (#131) | [268b239](268b2398b2ffe7f49dc84617d6a1b93a109c6099)
- Add wireless-tools as moonraker dependency (#137) | [f4bd84d](f4bd84db1c8708df825afb1b45893f39a5a25ef2)
- Add workflow to close stale issues / pull requests (#139) | [7510996](75109963b7bc0cc5ba4c6330b58656a7fd175600)
- Add additional Input shaper dependencies (#140) | [3f63e65](3f63e658019016a3b2605a128b53e3fd35344700)
- Bump version to v0.7.1 (#145) | [8863d00](8863d0050f239c78894bb977490c7e94c0d5bea7)
- Rework build workflow with source image cache (#146) | [421a9c0](421a9c0dff96a585ab653bb7c4a41b64f60ffd30)
- Only build an image on push in master/develop branch (#148) | [5bf5f4d](5bf5f4d45ea68ce69b6b9f3f7601e361fe85c769)
- Change cron interval of stale action (#149) | [bbb1f13](bbb1f134d50b346c97bce83b2c209383d940f179)
- Update versions according to bullseye (#147) | [9db4b42](9db4b42863d9a34600989e0423b3765fc1a5b203)
- Rework build workflow for multiple images (#152) | [dc48d1b](dc48d1ba6105a8934bcb90741801121a90e22a08)
- Fix image name (#153) | [7d7855e](7d7855e43a014b40bb69f694ab56d0c162cac9e9)
- Impove shellcheck and auto read version number (#155) | [9048152](90481524669f193c8d0d8f90e82dc9cd6fb7aac3)
- Add Raspberry 64bit config (#156) | [72314fb](72314fba6129d3086ad8ff8eeef5504af0ce6e09)
- Upload failed logfile (#163) | [dcc16cf](dcc16cf773449050c2864da0b8dfe17663821995)
- Add armbian module (#165) | [d245465](d24546513880743df766b1e1814a095b2760a281)
- Update modules according to path changes (#166) | [e5943af](e5943af3dda70cc453531ea9c6f3e3ffbf0b08f2)
- Update BuildImages workflow (#171) | [132c676](132c676ad2ccae91e717c402c8c82f3d752ff134)
- Improved shellcheck lint (#172) | [b204334](b20433453e95979cde7ae5007fbc3824dd7d8d7e)
- Remove github-token for build action (#178) | [7d42152](7d42152d38191a979c75c7837e92e92689509fb7)
- Add "not-on-Github" bot for issues (#179) | [68520ce](68520ce40659e223d8c79820a7eda4923d9ae02d)
- Fix changelog in release workflow (#182) | [32f9429](32f9429d49671e5657c7ed5143ca63e88046f364)
- Removes fkms overlays (#183) | [999183b](999183bef6b290efcd8d4f2c8d708354152d411c)
