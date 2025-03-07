# Changelog

This is the log of notable changes to Expo CLI and related packages.

## main

### 🛠 Breaking changes

### 🎉 New features

### 🧹 Chores

## [Sun, 10 Sep 2023 17:56:11 -0700](https://github.com/expo/expo-cli/commit/24eb3415f8e120e82a4f6dc8577d07fbe42ef854)

### 🛠 Breaking changes

### 🎉 New features

- [doctor] @expo/metro-config deep dependency check ([#4742](https://github.com/expo/expo-cli/issues/4742))
- [pod-install] show alternative message in managed projects ([#4566](https://github.com/expo/expo-cli/issues/4566))
- [create-expo] Bump @expo/package-manager for Bun support
- [create-expo] detect bun package manager ([#4752](https://github.com/expo/expo-cli/issues/4752))
- [webpack]: Bump expo to SDK 49 ([#4747](https://github.com/expo/expo-cli/issues/4747))

### 🧹 Chores

### 🐛 Bug fixes

- [create-expo]: allow scoped template package names ([#4750](https://github.com/expo/expo-cli/issues/4750))

### 📦 Packages updated

- create-expo@2.1.1
- create-expo-app@2.1.1
- @expo/dev-tools@0.13.187
- expo-cli@6.3.12
- expo-doctor@1.1.3
- install-expo-modules@0.6.3
- pod-install@0.1.39
- expo-pwa@0.0.127
- @expo/webpack-config@18.1.3
- xdl@60.0.12

## [Wed Jul 5 17:04:00 2023 -0700](https://github.com/expo/expo-cli/commit/b417540058c85cc7c2b28c37aa2e2ce52b06b03b)

### 🧹 Chores

- [install-expo-modules] Update text re: Expo CLI installation

### 📦 Packages updated

- install-expo-modules@0.6.1

## [Wed, 5 Jul 2023 12:03:05 -0700](https://github.com/expo/expo-cli/commit/2bc53712a2d0c856b5504a77f402a08e3bef993f)

### 🎉 New features

- [install-expo-modules] add cli integration support ([#4728](https://github.com/expo/expo-cli/issues/4728))

### 🧹 Chores

- [cli] Improve the Expo CLI deprecation message
- [doctor] clean up check names ([#4727](https://github.com/expo/expo-cli/issues/4727))
- [github] Remove webpack workflows
- [pwa] drop custom config path

### 📦 Packages updated

- @expo/babel-preset-cli@0.3.1
- create-expo@2.0.3
- @expo/dev-tools@0.13.185
- expo-cli@6.3.9
- expo-doctor@1.1.1
- install-expo-modules@0.6.0
- expo-pwa@0.0.126
- @expo/webpack-config@18.1.1
- xdl@60.0.10

## [Tue, 30 May 2023 13:01:03 -0500](https://github.com/expo/expo-cli/commit/23cc30b081aabefc2b0d8f7139c001fd286322d8)

### 🛠 Breaking changes

### 🎉 New features

- [doctor] Move dependencies to devDependencies ([#4709](https://github.com/expo/expo-cli/issues/4709))
- Make `@expo/webpack-config` depend on `expo` ([#4703](https://github.com/expo/expo-cli/issues/4703))

### 🧹 Chores

### 🐛 Bug fixes

- [doctor] remove sh command from dep check for Windows compat ([#4706](https://github.com/expo/expo-cli/issues/4706))

### 📦 Packages updated

- @expo/dev-tools@0.13.184
- expo-cli@6.3.8
- expo-doctor@1.1.0
- expo-pwa@0.0.125
- @expo/webpack-config@18.1.0
- xdl@60.0.9

## [Thu, 27 Apr 2023 13:46:02 -0700](https://github.com/expo/expo-cli/commit/80d7d352b476aba692226367a3bb6a8e78bf6294)

### 🧹 Chores

- [cli] cross deploy to create-expo ([#4698](https://github.com/expo/expo-cli/issues/4698))
- [cli] Add link to new Expo CLI blog post
- [cli] add deprecated commands to helpgroup ([#4696](https://github.com/expo/expo-cli/issues/4696))
- [cli] replace deprecated commands with superceded ones ([#4693](https://github.com/expo/expo-cli/issues/4693))
- [cli] advise to use new doctor on SDK 46+ ([#4689](https://github.com/expo/expo-cli/issues/4689))
- [cli] deprecate publish:\* ([#4685](https://github.com/expo/expo-cli/issues/4685))

### 🐛 Bug fixes

- [doctor] specify schemer version ([#4687](https://github.com/expo/expo-cli/issues/4687))

### 📦 Packages updated

- create-expo-app@1.3.3
- expo-cli@6.3.7
- expo-doctor@1.0.6

## [Tue, 14 Feb 2023 18:55:17 -0800](https://github.com/expo/expo-cli/commit/043302f4d0fdd3f13a4bfc928bd45c8c5f501c3a)

### 🎉 New features

- [create-expo-app] add `--example` flag to initialize from example ([#4644](https://github.com/expo/expo-cli/issues/4644))
- [install-expo-modules] add sdk 48 support ([#4652](https://github.com/expo/expo-cli/issues/4652))

### 🧹 Chores

- [xdl] remove unused import from `createBundlesAsync` ([#4645](https://github.com/expo/expo-cli/issues/4645))

### 📦 Packages updated

- create-expo-app@1.3.2
- @expo/dev-tools@0.13.178
- expo-cli@6.3.1
- install-expo-modules@0.5.0
- xdl@60.0.3

## [Mon, 6 Feb 2023 20:37:17 -0800](https://github.com/expo/expo-cli/commit/36dbc671d41270885a046fd5848ddd3b039139ed)

### 🎉 New features

- [expo-cli] Bump @expo/dev-server to support the latest React Native release with Hermes sourcemap changes

### 🐛 Bug fixes

- [expo-cli] Bump @expo/apple-utils
- [next-adapter] drop next-expo script as it causes npm to fail ([#4637](https://github.com/expo/expo-cli/issues/4637))

### 📦 Packages updated

- create-expo-app@1.2.1
- @expo/dev-tools@0.13.177
- expo-cli@6.3.0
- @expo/next-adapter@5.0.2
- xdl@60.0.2

## [Fri, 27 Jan 2023 11:42:59 -0600](https://github.com/expo/expo-cli/commit/226ac07bd39ec14a97441365af0d2030a8ff0f59)

### 🐛 Bug fixes

- fix(webpack): add webpack-dev-server as a dependency of webpack-config ([#4636](https://github.com/expo/expo-cli/issues/4636))

### 📦 Packages updated

- @expo/dev-tools@0.13.176
- expo-cli@6.2.1
- @expo/webpack-config@18.0.1
- xdl@60.0.1

## [Fri, 27 Jan 2023 11:01:19 -0600](https://github.com/expo/expo-cli/commit/4e7dbf3adc90106a3d013cb5289c1b0e1ca06172)

### 🛠 Breaking changes

- [webpack] Upgrade to Webpack 5 ([#3763](https://github.com/expo/expo-cli/issues/3763))
- Remove Node.js limitations on the legacy CLI ([#4635](https://github.com/expo/expo-cli/issues/4635))

### 🎉 New features

- [webpack] Upgrade to Webpack 5 ([#3763](https://github.com/expo/expo-cli/issues/3763))

### 🧹 Chores

- [readme] Highlight the modern local CLI over everything else ([#4632](https://github.com/expo/expo-cli/issues/4632))

### 🐛 Bug fixes

- fix(create-expo-app): skip creating a git repo when inside existing repo ([#4629](https://github.com/expo/expo-cli/issues/4629))

### 📦 Packages updated

- @expo/babel-preset-cli@0.3.0
- create-expo-app@1.1.7
- @expo/dev-tools@0.13.175
- expo-cli@6.2.0
- @expo/next-adapter@5.0.1
- @expo/webpack-config@18.0.0
- xdl@60.0.0

### 🛠 Breaking changes

### 🎉 New features

### 🧹 Chores

## [Thu, 5 Jan 2023 12:40:31 +0100](https://github.com/expo/expo-cli/commit/a1511511803f5b4c1935a00cd18b340a9d5309ce)

### 🛠 Breaking changes

### 🎉 New features

- [install-expo-modules] Add react-native 0.71 support ([#4612](https://github.com/expo/expo-cli/issues/4612))
- [uri-scheme] Handle multiple query parameters in Android URIs ([#4538](https://github.com/expo/expo-cli/issues/4538))
- [xdl] Add feature gates ([#4587](https://github.com/expo/expo-cli/issues/4587))

### 🧹 Chores

- [expo-cli] deprecate `expo-optimize` and drop related checks ([#4588](https://github.com/expo/expo-cli/issues/4588))
- [traveling-fastlane] drop source ([#4589](https://github.com/expo/expo-cli/issues/4589))

### 🐛 Bug fixes

- [json] json5 to v2.2.2 where vulnerability has been patched ([#4618](https://github.com/expo/expo-cli/issues/4618))
- [plist] Update `@xmldom/xmldom` ([#4592](https://github.com/expo/expo-cli/issues/4592))

### 📦 Packages updated

- @expo/babel-preset-cli@0.2.25
- create-expo-app@1.1.5
- @expo/dev-tools@0.13.174
- expo-cli@6.1.0
- install-expo-modules@0.4.0
- @expo/json-file@8.2.37
- @expo/next-adapter@5.0.0
- @expo/plist@0.0.20
- uri-scheme@1.1.0
- @expo/webpack-config@0.17.4
- xdl@59.3.0

## [Thu, 3 Nov 2022 15:56:46 -0700](https://github.com/expo/expo-cli/commit/e01f9467376b71a8e1bbe28065a697f7c8e1da1e)

### 🧹 Chores

- [cli] Add specific error message about SDK 47+ and expo build

### 📦 Packages updated

- @expo/dev-tools@0.13.173
- expo-cli@6.0.8
- xdl@59.2.55

## [Mon, 31 Oct 2022 14:39:49 -0700](https://github.com/expo/expo-cli/commit/1f5ff3e45d83de6e437cb9b445e5f3afa9db33cc)

### 🎉 New features

- [install-expo-modules] add sdk 47 (rn 0.70) support. ([#4578](https://github.com/expo/expo-cli/issues/4578))

### 🧹 Chores

- update babel preset ([#4580](https://github.com/expo/expo-cli/issues/4580))
- update e2e tests for export ([#4579](https://github.com/expo/expo-cli/issues/4579))
- [plist] Update xmldom for security reasons ([#4571](https://github.com/expo/expo-cli/issues/4571))
- [create-expo-app] Prevent Forbidden/ Conflicting app names ([#4565](https://github.com/expo/expo-cli/issues/4565))
- [schemer] bump AJV, bump other deps ([#3423](https://github.com/expo/expo-cli/issues/3423))
- [image-utils] Silence sharp related warnings by default ([#4558](https://github.com/expo/expo-cli/issues/4558))

### 🐛 Bug fixes

- fix(image-utils): make jimp export buffers as png like sharp ([#4576](https://github.com/expo/expo-cli/issues/4576))

### 📦 Packages updated

- create-expo-app@1.1.4
- @expo/dev-tools@0.13.172
- expo-cli@6.0.7
- expo-optimize@0.2.20
- @expo/image-utils@0.3.23
- install-expo-modules@0.3.9
- @expo/next-adapter@4.0.13
- @expo/plist@0.0.19
- expo-pwa@0.0.124
- @expo/schemer@1.4.4
- uri-scheme@1.0.121
- @expo/webpack-config@0.17.3
- xdl@59.2.54

## [Mon, 26 Sep 2022 16:10:32 -0700](https://github.com/expo/expo-cli/commit/baa05e13d84a2a4e16bf2481883c40233d1e9ef9)

### 🧹 Chores

- [xdl] fix schema test ([#4539](https://github.com/expo/expo-cli/issues/4539))
- [CEA] bump and cleanup dependencies ([#4536](https://github.com/expo/expo-cli/issues/4536))

### 🐛 Bug fixes

- [install-expo-modules] Fix RCTRootView for react-native 0.68 or above ([#4555](https://github.com/expo/expo-cli/issues/4555))
- [install-expo-modules] Replace xcode with xcparse ([#4554](https://github.com/expo/expo-cli/issues/4554))

### 📦 Packages updated

- create-expo-app@1.1.2
- @expo/dev-tools@0.13.171
- expo-cli@6.0.6
- install-expo-modules@0.3.8
- xdl@59.2.53

## [Wed, 17 Aug 2022 09:13:43 -0700](https://github.com/expo/expo-cli/commit/e0f8c6f7bb2f70c57905947d37a6b7819fe8fc3d)

### 🧹 Chores

- [cli] Add learn more link about local CLI

### 📦 Packages updated

- expo-cli@6.0.5

## [Thu, 11 Aug 2022 21:01:44 -0700](https://github.com/expo/expo-cli/commit/2989fd7bf0737e007f9cb8c72a78246d41bac0dc)

### 🧹 Chores

- [webpack-config] Remove explicit `@expo/config` dependency ([#4512](https://github.com/expo/expo-cli/pull/4512))

### 📦 Packages updated

- @expo/dev-tools@0.13.170
- expo-cli@6.0.4
- @expo/next-adapter@4.0.12
- @expo/webpack-config@0.17.2
- xdl@59.2.52

### 🐛 Bug fixes

## [Thu, 11 Aug 2022 17:55:34 -0700](https://github.com/expo/expo-cli/commit/8012304c978ae6f943b95210534536577418cb86)

### 🧹 Chores

- [pwa] Move away from direct dep on @expo/config
- [package-manager] Move package manager to expo/expo repository ([#4506](https://github.com/expo/expo-cli/issues/4506))

### 📦 Packages updated

- @expo/dev-tools@0.13.169
- expo-cli@6.0.3
- @expo/next-adapter@4.0.11
- expo-pwa@0.0.123
- @expo/webpack-config@0.17.1
- xdl@59.2.51

## [Tue, 9 Aug 2022 17:12:18 -0700](https://github.com/expo/expo-cli/commit/5cbaeba757f2ea1e27f6f962c7b63bcd3f462e03)

### 🎉 New features

- feat(cli): add migration logs when available ([#4505](https://github.com/expo/expo-cli/issues/4505))

### 🧹 Chores

- chore(expo-cli): add better warning when prebuilding in non-interactive mode ([#4456](https://github.com/expo/expo-cli/issues/4456))

### 📦 Packages updated

- @expo/dev-tools@0.13.168
- expo-cli@6.0.2
- xdl@59.2.50

## [Tue, 26 Jul 2022 15:36:36 -0400](https://github.com/expo/expo-cli/commit/0a8681d04e3558676384c767b61aa123c140dfc1)

### 🐛 Bug fixes

- [xdl] include version number in package info cache ([#4484](https://github.com/expo/expo-cli/issues/4484))

### 📦 Packages updated

- @expo/dev-tools@0.13.167
- expo-cli@6.0.1
- xdl@59.2.49

## [Mon, 25 Jul 2022 14:09:28 -0700](https://github.com/expo/expo-cli/commit/0f34bd72db14d9504877dd9a0b1d7b44f6f99a3c)

### 🛠 Breaking changes

- [expo-cli] stop showing dev tools UI ([#4482](https://github.com/expo/expo-cli/issues/4482))

### 🧹 Chores

- [create-expo-app] drop all URL caching in favor of temporary cache ([#4481](https://github.com/expo/expo-cli/issues/4481))

### 🐛 Bug fixes

- [webpack-config] fix import export treeshaking ([#4476](https://github.com/expo/expo-cli/issues/4476))

### 📦 Packages updated

- create-expo-app@1.1.1
- @expo/dev-tools@0.13.166
- expo-cli@6.0.0
- @expo/next-adapter@4.0.10
- @expo/webpack-config@0.17.0
- xdl@59.2.48

## [Wed, 20 Jul 2022 16:42:39 -0700](https://github.com/expo/expo-cli/commit/8c3da4b3c28eef860dc612f18c841c57eaa28a7d)

### 🎉 New features

- [install-expo-modules] Add SDK 46 support ([#4471](https://github.com/expo/expo-cli/issues/4471))
- [create-expo-app] add support for EXPO_BETA flag ([#4474](https://github.com/expo/expo-cli/issues/4474))

### 🧹 Chores

- Deleted config packages ([#4449](https://github.com/expo/expo-cli/issues/4449))
- Deleted metro packages ([#4465](https://github.com/expo/expo-cli/issues/4465))

### 🐛 Bug fixes

- [next-adapter] Fix showstopper in next-adapter/document.js ([#4461](https://github.com/expo/expo-cli/issues/4461))

### 📦 Packages updated

- create-expo-app@1.0.4
- @expo/dev-tools@0.13.165
- expo-cli@5.6.0
- expo-env-info@1.0.5
- expo-optimize@0.2.19
- @expo/image-utils@0.3.22
- install-expo-modules@0.3.7
- @expo/next-adapter@4.0.9
- @expo/package-manager@0.0.56
- pod-install@0.1.38
- expo-pwa@0.0.122
- @expo/schemer@1.4.3
- @expo/webpack-config@0.16.27
- xdl@59.2.47

## [Mon, 11 Jul 2022 14:48:32 -0700](https://github.com/expo/expo-cli/commit/ad7d79c9b216de9c62b52083aa407c843f261bdd)

### 🐛 Bug fixes

- Republish packages in order to prevent @expo/config@6.0.25 from being pulled in.

### 📦 Packages updated

- @expo/config@6.0.26
- @expo/dev-server@0.1.116
- @expo/dev-tools@0.13.161
- expo-cli@5.5.1
- expo-optimize@0.2.18
- install-expo-modules@0.3.5
- @expo/metro-config@0.3.19
- @expo/next-adapter@4.0.8
- @expo/prebuild-config@4.0.4
- expo-pwa@0.0.121
- @expo/webpack-config@0.16.26
- xdl@59.2.44

## [Mon, 11 Jul 2022 13:58:56 -0700](https://github.com/expo/expo-cli/commit/413f14e366e090c2c5f3f53103d764fc30b97b4b)

### 🎉 New features

- [doctor] Validate that projects do not include illegal packages ([#4448](https://github.com/expo/expo-cli/issues/4448))

### 🧹 Chores

- [dev-tools-ui] add deprecated banner to dev tools UI ([#4453](https://github.com/expo/expo-cli/issues/4453))

### 🐛 Bug fixes

- [dev-server] Support prebuilt hermes in react-native 0.69 ([#4462](https://github.com/expo/expo-cli/issues/4462))

### 📦 Packages updated

- @expo/dev-server@0.1.115
- @expo/dev-tools@0.13.160
- expo-cli@5.5.0
- xdl@59.2.43

## [Fri, 24 Jun 2022 17:35:58 -0700](https://github.com/expo/expo-cli/commit/5441ad05c2b99429cee32e5be5ddd5bcedcec204)

### 🛠 Breaking changes

### 🎉 New features

### 🧹 Chores

### 🐛 Bug fixes

- [cli] Fix ignored existing plugins on `expo install`. ([#4429](<[https://github.com/expo/expo/pull/17936](https://github.com/expo/expo-cli/pull/4429)>)
- [cli] Remove no-startup-window flag when starting Hermes debugger
- [expo-env-info] don't show workflow type outside of project folder ([#4310](https://github.com/expo/expo-cli/issues/4310))
- [fix] fix auto TypeScript version check ([#4439](https://github.com/expo/expo-cli/issues/4439))
- [image-utils] update expected `sharp-cli` version to 2.1.0 for M1 compatibility ([#4435](https://github.com/expo/expo-cli/pull/4435))

### 📦 Packages updated

- @expo/dev-server@0.1.114
- @expo/dev-tools@0.13.159
- expo-cli@5.4.12
- expo-env-info@1.0.4
- expo-optimize@0.2.17
- @expo/image-utils@0.3.21
- @expo/next-adapter@4.0.7
- @expo/prebuild-config@4.0.3
- expo-pwa@0.0.120
- @expo/webpack-config@0.16.25
- xdl@59.2.42

## [Wed, 15 Jun 2022 20:47:15 -0700](https://github.com/expo/expo-cli/commit/2c8188fd3e0dbbc9f545ce4c59ea543d676f97eb)

### 🧹 Chores

- update ajv ([#4385](https://github.com/expo/expo-cli/issues/4385))

### 🐛 Bug fixes

- [cli] Support scoped package names for initialising projects ([#4417](https://github.com/expo/expo-cli/issues/4417))
- [package-manager] should not use yarn when npm lockfile exists ([#4387](https://github.com/expo/expo-cli/issues/4387))
- [cli] `expo doctor` return non-zero exit code if package versions are incorrect ([#4424](https://github.com/expo/expo-cli/issues/4424))

### 📦 Packages updated

- @expo/dev-tools@0.13.157
- expo-cli@5.4.10
- install-expo-modules@0.3.4
- @expo/next-adapter@4.0.6
- @expo/package-manager@0.0.55
- pod-install@0.1.37
- @expo/schemer@1.4.2
- xdl@59.2.41

## [Sun, 5 Jun 2022 15:51:35 +0200](https://github.com/expo/expo-cli/commit/82139f7d126e8a950a005875de1d1b4f73c83ca7)

### 🧹 Chores

- [doctor] Gracefully handle not being able to run dependency tree validation on older Node/npm versions. ([#4413](https://github.com/expo/expo-cli/pull/4413))

### 📦 Packages updated

- expo-cli@5.4.9

## [Wed, 1 Jun 2022 14:18:31 -0700](https://github.com/expo/expo-cli/commit/7873fefa2f73a5c8df08d20376d0ff374a19e96d)

### 🧹 Chores

- [xdl] Add logging of manifest requests for debugging purposes

### 📦 Packages updated

- @expo/dev-tools@0.13.156
- expo-cli@5.4.8
- xdl@59.2.40

## [Thu, 26 May 2022 16:40:07 -0700](https://github.com/expo/expo-cli/commit/8c468c79bcbae988d0ef2a2d5e298a0b8d0f91d6)

### 🎉 New features

- [cli] use `npm pack` for template downloading to be compatible with private npm registries ([#4233](https://github.com/expo/expo-cli/pull/4223))
- [doctor] Add version validation for expo-modules-autolinking, @expo/config-plugins, @expo/config ([#4392](https://github.com/expo/expo-cli/issues/4392))

### 🧹 Chores

- [prebuild-config] Bump expo-modules-autolinking version

### 🐛 Bug fixes

- [dev-server] Fix js inspector broken from websocket address transform ([#4394](https://github.com/expo/expo-cli/issues/4394))

### 📦 Packages updated

- @expo/dev-server@0.1.113
- @expo/dev-tools@0.13.155
- expo-cli@5.4.7
- @expo/metro-config@0.3.18
- @expo/prebuild-config@4.0.2
- xdl@59.2.39

## [Wed, May 18 2022 19:34:55 2022 -0700](https://github.com/expo/expo-cli/commit/866daede8095b3febb98b0d325085fb36550d7b9)

### 🧹 Chores

- [dev-server] add sdk 45 support for the sanity check of hermes bundle ([#4382](https://github.com/expo/expo-cli/pull/4382))

### 📦 Packages updated

- expo-cli@5.4.6
- @expo/dev-tools@0.13.154
- @expo/dev-server@0.1.112
- xdl@59.2.38

## [Fri, 13 May 2022 14:44:51 -0700](https://github.com/expo/expo-cli/commit/dce0e2d23f1b38089a66d023c9ca8a5e70fd3fc2)

### 🎉 New features

- [config-plugins] rename android jni java descriptors from prebuild ([#4362](https://github.com/expo/expo-cli/issues/4362))
- [create-expo-app] add support for the `--template` arg from `expo init` ([#4367](https://github.com/expo/expo-cli/issues/4367))
- [create-expo-app] auto select package manager ([#4339](https://github.com/expo/expo-cli/issues/4339))
- [create-expo-app] fail on invalid template before prompting for the app name ([#4372](https://github.com/expo/expo-cli/issues/4372))
- [create-expo-app] hello, world! (create the package) ([#4338](https://github.com/expo/expo-cli/issues/4338))
- [create-expo-app] use hidden directory for home cache ([#4353](https://github.com/expo/expo-cli/issues/4353))
- [package-manager] Prefer yarn over npm if both lockfiles exists ([#4369](https://github.com/expo/expo-cli/issues/4369))

### 🧹 Chores

- [expo-cli] Improve Fig autocomplete support ([#4331](https://github.com/expo/expo-cli/issues/4331))
- [expo-cli] set non-zero exit code when expo doctor fails ([#4359](https://github.com/expo/expo-cli/issues/4359))
- [expo-cli][metro-config] prevent throwing when an upper-level directory has an invalid package.json ([#4363](https://github.com/expo/expo-cli/issues/4363))
- [package-manager] explicitly order package managers ([#4344](https://github.com/expo/expo-cli/issues/4344))

### 🐛 Bug fixes

- [config-plugins] Handle quoted build configuration ([#4341](https://github.com/expo/expo-cli/issues/4341))
- [config-plugins] Remove warning when permissions config is empty when using blockedPermissions ([#4352](https://github.com/expo/expo-cli/issues/4352))
- [prebuild-config] update manifest roundIcon property ([#4370](https://github.com/expo/expo-cli/issues/4370))

### 📦 Packages updated

- @expo/config-plugins@4.1.5
- @expo/config@6.0.24
- create-expo-app@0.0.9
- @expo/dev-server@0.1.111
- @expo/dev-tools@0.13.153
- expo-cli@5.4.4
- expo-optimize@0.2.16
- install-expo-modules@0.3.3
- @expo/metro-config@0.3.17
- @expo/next-adapter@4.0.5
- @expo/package-manager@0.0.54
- pod-install@0.1.36
- @expo/prebuild-config@4.0.1
- expo-pwa@0.0.119
- uri-scheme@1.0.120
- @expo/webpack-config@0.16.24
- xdl@59.2.37

## [Wed, 27 Apr 2022 16:29:28 -0700](https://github.com/expo/expo-cli/commit/e517d22aaf8a3fd93795a276ed68be8b1afed30d)

### 🎉 New features

- [package-manager] Add support for pnpm ([#4311](https://github.com/expo/expo-cli/issues/4311))

### 🧹 Chores

- [prebuild-config] Bump expo-modules-autolinking version

### 📦 Packages updated

- @expo/dev-tools@0.13.152
- expo-cli@5.4.3
- install-expo-modules@0.3.2
- @expo/next-adapter@4.0.4
- @expo/package-manager@0.0.53
- pod-install@0.1.35
- @expo/prebuild-config@4.0.0
- xdl@59.2.36

## [Wed, 27 Apr 2022 11:34:35 -0700](https://github.com/expo/expo-cli/commit/7bbabeec424484dd8b1592cc128d35a9e99e323d)

### 🧹 Chores

- [config-types] Bump version

### 📦 Packages updated

- @expo/config-plugins@4.1.4
- @expo/config@6.0.23
- @expo/dev-server@0.1.110
- @expo/dev-tools@0.13.151
- expo-cli@5.4.2
- expo-optimize@0.2.15
- install-expo-modules@0.3.1
- @expo/metro-config@0.3.16
- @expo/next-adapter@4.0.3
- @expo/prebuild-config@3.1.4
- expo-pwa@0.0.118
- uri-scheme@1.0.119
- @expo/webpack-config@0.16.23
- xdl@59.2.35

## [Wed, 27 Apr 2022 10:57:06 -0700](https://github.com/expo/expo-cli/commit/c4258cabdb3f860ff190bb4234074e1570f5be86)

### 🎉 New features

- [install-expo-modules] Add react-native 0.68 and expo sdk 45 support ([#4333](https://github.com/expo/expo-cli/issues/4333))
- [config plugins] support android.blockedPermissions ([#4323](https://github.com/expo/expo-cli/issues/4323))

### 📦 Packages updated

- @expo/config-plugins@4.1.3
- @expo/config@6.0.22
- @expo/dev-server@0.1.109
- @expo/dev-tools@0.13.150
- expo-cli@5.4.1
- expo-optimize@0.2.14
- install-expo-modules@0.3.0
- @expo/metro-config@0.3.15
- @expo/next-adapter@4.0.2
- @expo/prebuild-config@3.1.3
- expo-pwa@0.0.117
- uri-scheme@1.0.118
- @expo/webpack-config@0.16.22
- xdl@59.2.34

## [Mon, 25 Apr 2022 09:39:36 -0700](https://github.com/expo/expo-cli/commit/3b877aba82399512ca583a972effcd09c6f43f26)

### 🎉 New features

- [config-plugins] Introduce rule-based build properties config-plugin ([#4270](https://github.com/expo/expo-cli/issues/4270))
- [config-plugins] add initial app clip support ([#4327](https://github.com/expo/expo-cli/issues/4327))
- [config-plugins] resolve target specific entitlements files ([#4313](https://github.com/expo/expo-cli/issues/4313))
- [expo-env-info] prepare repo to convert expo-env-info to esm ([#4312](https://github.com/expo/expo-cli/issues/4312))
- [dev-server] support new API for Expo SDK 45 ([#4306](https://github.com/expo/expo-cli/issues/4306))

### 🧹 Chores

- [expo-env-info] convert expo-env-info from CJS to ESM ([#4320](https://github.com/expo/expo-cli/issues/4320))

### 📦 Packages updated

- @expo/config-plugins@4.1.2
- @expo/config@6.0.21
- @expo/dev-server@0.1.108
- @expo/dev-tools@0.13.149
- expo-cli@5.4.0
- expo-codemod@1.1.6
- expo-env-info@1.0.3
- expo-optimize@0.2.13
- @expo/image-utils@0.3.20
- install-expo-modules@0.2.8
- @expo/json-file@8.2.36
- @expo/metro-config@0.3.14
- @expo/next-adapter@4.0.1
- @expo/osascript@2.0.33
- @expo/package-manager@0.0.52
- pod-install@0.1.34
- @expo/prebuild-config@3.1.2
- expo-pwa@0.0.116
- @expo/schemer@1.4.1
- uri-scheme@1.0.117
- @expo/webpack-config@0.16.21
- xdl@59.2.33

## [Tue, 19 Apr 2022 14:19:30 -0700](https://github.com/expo/expo-cli/commit/a61ddb4dcd27da86f74de9c7e9bd18570d8c2684)

### 🧹 Chores

- [ci] Set timeout to 2 minutes and remove check files on windows ([#4302](https://github.com/expo/expo-cli/issues/4302))
- chore(xdl): add new metro logging events ([#4304](https://github.com/expo/expo-cli/issues/4304))
- chore: sync stale config with other repo ([#4297](https://github.com/expo/expo-cli/issues/4297))
- Bump @expo/apple-utils@0.0.0-alpha.31 ([#4300](https://github.com/expo/expo-cli/issues/4300))
- ci: add stale bot from expo/expo ([#4295](https://github.com/expo/expo-cli/issues/4295))

### 🐛 Bug fixes

- [schemer] Update user-facing error message for `not` fields ([#4308](https://github.com/expo/expo-cli/issues/4308))

### 📦 Packages updated

- @expo/dev-tools@0.13.148
- expo-cli@5.3.2
- @expo/schemer@1.4.0
- xdl@59.2.32

## [Mon, 11 Apr 2022 13:14:18 -0700](https://github.com/expo/expo-cli/commit/f163652768ae987280307275b0a02cfd4b3cc403)

### 🛠 Breaking changes

- [next-adapter] revert webpack5 detection ([#4254](https://github.com/expo/expo-cli/issues/4254))
- [metro-config] Removes duplicate `json` extensions in metro `assetExts` and `sourceExts`. ([#4255](https://github.com/expo/expo-cli/pull/4255))

### 🎉 New features

- [cli] update supported Node version warning to reflect current LTS schema ([#4261](https://github.com/expo/expo-cli/pull/4261))
- [cli] Cap Expo CLI at Node 16 ([#4281](https://github.com/expo/expo-cli/issues/4281))

### 🧹 Chores

- update packages readme files ([#4170](https://github.com/expo/expo-cli/issues/4170))
- add webpack-dev-server dependency to expo/webpack-config ([#4282](https://github.com/expo/expo-cli/issues/4282))
- chore(config plugins): drop fs-extra ([#4290](https://github.com/expo/expo-cli/issues/4290))
- update bugreport template label ([#4272](https://github.com/expo/expo-cli/issues/4272))
- re-enable codecov ([#4222](https://github.com/expo/expo-cli/issues/4222))

### 🐛 Bug fixes

- [config-plugins] use relative path for locales ([#4260](https://github.com/expo/expo-cli/issues/4260))
- [config-plugins] match `xcodeproj` in ios directory only ([#4288](https://github.com/expo/expo-cli/issues/4288))

### 📦 Packages updated

- @expo/babel-preset-cli@0.2.24
- @expo/config-plugins@4.1.1
- @expo/config@6.0.20
- @expo/dev-server@0.1.107
- @expo/dev-tools@0.13.147
- expo-cli@5.3.1
- expo-optimize@0.2.12
- @expo/image-utils@0.3.19
- install-expo-modules@0.2.7
- @expo/json-file@8.2.35
- @expo/metro-config@0.3.13
- @expo/next-adapter@4.0.0
- @expo/osascript@2.0.32
- @expo/package-manager@0.0.51
- @expo/pkcs12@0.0.8
- @expo/plist@0.0.18
- pod-install@0.1.33
- @expo/prebuild-config@3.1.1
- expo-pwa@0.0.115
- @expo/schemer@1.3.34
- uri-scheme@1.0.116
- @expo/webpack-config@0.16.20
- xdl@59.2.31

## [Tue, 8 Mar 2022 12:30:47 -0700](https://github.com/expo/expo-cli/commit/82dcf7ce6669e277eafe5bca0440e925dcbc6e08)

### 🛠 Breaking changes

- [expo-cli] Deprecate the `--name` argument of the init command. ([#4225](https://github.com/expo/expo-cli/issues/4225))
- [expo-cli] Deprecate `expo diagnostics` command in favor of `npx expo-env-info`. ([#4221](https://github.com/expo/expo-cli/issues/4221))

### 🎉 New features

- [config-plugins] Added support for `AppDelegate.mm`. ([#4243](https://github.com/expo/expo-cli/issues/4243))
- [config-plugin] Append scheme `REVERSED_CLIENT_ID` from `GoogleService-Info.plist`. ([#4238](https://github.com/expo/expo-cli/issues/4238))

### 🧹 Chores

- [expo-cli] Move `expo eject` to the deprecated help group ([#4249](https://github.com/expo/expo-cli/issues/4249))
- [config-plugins] update `AndroidManifest.xml` template for introspect ([#4245](https://github.com/expo/expo-cli/issues/4245))
- [chore] Switch issue template to `expo-env-info` ([#4233](https://github.com/expo/expo-cli/issues/4233))

### 🐛 Bug fixes

- [config-types] Deprecated `reservedClientId` ([#4241](https://github.com/expo/expo-cli/issues/4241))
- [expo-cli] Pick correct scheme for open android app ([#4228](https://github.com/expo/expo-cli/issues/4228))
- [config-plugins] Unescape values when reading strings.xml ([#4229](https://github.com/expo/expo-cli/issues/4229))
- Round file results to fix E2E tests ([#4226](https://github.com/expo/expo-cli/issues/4226))

### 📦 Packages updated

- @expo/config-plugins@4.1.0
- @expo/config@6.0.19
- @expo/dev-server@0.1.106
- @expo/dev-tools@0.13.146
- expo-cli@5.3.0
- expo-optimize@0.2.11
- install-expo-modules@0.2.6
- @expo/metro-config@0.3.12
- @expo/next-adapter@3.1.21
- @expo/prebuild-config@3.1.0
- expo-pwa@0.0.114
- uri-scheme@1.0.115
- @expo/webpack-config@0.16.19
- xdl@59.2.30

## [Wed, 16 Feb 2022 12:20:14 -0800](https://github.com/expo/expo-cli/commit/11f518d24c070ef6b82b6eb5f9da22f1648f2665)

### 🎉 New features

- [expo-cli][package-manager] Pass parameters to `npm install` or `yarn add` command when using `expo install` ([#4174](https://github.com/expo/expo-cli/pull/4174))
- [expo-cli][xdl] remove env flag for interstitial page ([#4218](https://github.com/expo/expo-cli/issues/4218))
- [expo-cli] fix: pass max-workers option to metro on publish command ([#4187](https://github.com/expo/expo-cli/issues/4187))
- [Interstitial page] Try to detect if a deep link succeed ([#4209](https://github.com/expo/expo-cli/issues/4209))
- [cli] new expo-env-info package ([#4167](https://github.com/expo/expo-cli/issues/4167))

### 🐛 Bug fixes

- [Interstitial page] Fix QR on web UI & fallback to SDK version if the runtime version wasn't defined ([#4214](https://github.com/expo/expo-cli/issues/4214))
- [expo-cli] don't sanitize numbers from project names for npm package name on init ([#4208](https://github.com/expo/expo-cli/issues/4208))

### 📦 Packages updated

- @expo/dev-tools@0.13.145
- expo-cli@5.2.0
- expo-env-info@1.0.2
- install-expo-modules@0.2.5
- @expo/next-adapter@3.1.20
- @expo/package-manager@0.0.50
- pod-install@0.1.32
- xdl@59.2.29

## [Tue, 15 Feb 2022 10:13:55 -0800](https://github.com/expo/expo-cli/commit/f1d2413db3374a425561cbf71c7f20a6bb697b55)

### 🧹 Chores

- [docs] outdated docs link in contributing guidelines ([#4211](https://github.com/expo/expo-cli/issues/4211))

### 🐛 Bug fixes

- [cli] fix typo in settings validation logic ([#4215](https://github.com/expo/expo-cli/issues/4215))

### 📦 Packages updated

- @expo/dev-tools@0.13.144
- expo-cli@5.1.3
- xdl@59.2.28

## [Thu, 10 Feb 2022 12:37:31 -0800](https://github.com/expo/expo-cli/commit/82904c9641b22fdf0cc2b24b1cfd4ed33c4dfc33)

### 🎉 New features

- [cli] check expo-updates is installed before a publish ([#4179](https://github.com/expo/expo-cli/issues/4179))

### 🧹 Chores

- Publish @expo/config-types@44.0.0

### 🐛 Bug fixes

- [cli] Skip parsing font files on init ([#4202](https://github.com/expo/expo-cli/issues/4202))
- [cli] fix project page param typo ([#4204](https://github.com/expo/expo-cli/issues/4204))

### 📦 Packages updated

- @expo/config-plugins@4.0.18
- @expo/config@6.0.18
- @expo/dev-server@0.1.105
- @expo/dev-tools@0.13.143
- expo-cli@5.1.2
- expo-optimize@0.2.10
- install-expo-modules@0.2.4
- @expo/metro-config@0.3.11
- @expo/next-adapter@3.1.19
- @expo/prebuild-config@3.0.18
- expo-pwa@0.0.113
- uri-scheme@1.0.114
- @expo/webpack-config@0.16.18
- xdl@59.2.27

## [Tue, 8 Feb 2022 14:47:23 -0800](https://github.com/expo/expo-cli/commit/e68ec76f84d1ffe7691dbaf3d13de8cf1b7a264e)

### 🐛 Bug fixes

- [xdl] Add static directory to files

### 📦 Packages updated

- @expo/dev-tools@0.13.142
- expo-cli@5.1.1
- xdl@59.2.26

## [Tue, 8 Feb 2022 14:03:05 -0800](https://github.com/expo/expo-cli/commit/79e403db6d4a34cae02fca2f2e6baecc5bc4e709)

### 🛠 Breaking changes

### 🎉 New features

- [Interstitial page] Add missing information about project ([#4143](https://github.com/expo/expo-cli/issues/4143))
- [Interstitial page] Ensure that development build is installed ([#4144](https://github.com/expo/expo-cli/issues/4144))
- [Interstitial page] Improving user experience ([#4183](https://github.com/expo/expo-cli/issues/4183))
- [cli] add new query params to project URL ([#4178](https://github.com/expo/expo-cli/issues/4178))
- [cli] fix reading EAS project ID from app.json during start ([#4156](https://github.com/expo/expo-cli/issues/4156))
- [cli] new `--fix-dependencies` option for `doctor` ([#4153](https://github.com/expo/expo-cli/issues/4153))
- [cli] update error message when publish is misconfigured ([#4177](https://github.com/expo/expo-cli/issues/4177))
- [config-plugins] Add code signing configuration to updates config plugin ([#4122](https://github.com/expo/expo-cli/issues/4122))
- [xdl] persist dev client ids locally, use to start dev sessions ([#4087](https://github.com/expo/expo-cli/issues/4087))

### 🧹 Chores

- [cli] Skip updates warning in bare projects when expo-updates isn't in the package.json ([#4173](https://github.com/expo/expo-cli/issues/4173))
- [pkcs12] upgrade node-forge ([#4162](https://github.com/expo/expo-cli/issues/4162))
- [xdl] Drop sentry from xdl ([#4135](https://github.com/expo/expo-cli/issues/4135))
- [xdl] drop IP from track context ([#4146](https://github.com/expo/expo-cli/issues/4146))
- [xdl] refactor UrlUtils to not use Joi ([#4166](https://github.com/expo/expo-cli/issues/4166))

### 🐛 Bug fixes

- [cli] Fix running `expo web --no-dev` ([#4188](https://github.com/expo/expo-cli/issues/4188))
- [cli][docs] update broken flags in docs generation ([#4141](https://github.com/expo/expo-cli/issues/4141))
- [config-plugins] avoid duplicate CFBundleURLTypes ([#4164](https://github.com/expo/expo-cli/issues/4164))
- [config-plugins] handle missing targetattributes edge case when setting provisioning profile for multitarget projects ([#4175](https://github.com/expo/expo-cli/issues/4175))
- [metro-config] Add missing resolve-from dependency ([#4182](https://github.com/expo/expo-cli/issues/4182))

### 📦 Packages updated

- @expo/config-plugins@4.0.17
- @expo/config@6.0.17
- @expo/dev-server@0.1.104
- @expo/dev-tools@0.13.141
- expo-cli@5.1.0
- expo-optimize@0.2.9
- install-expo-modules@0.2.3
- @expo/metro-config@0.3.10
- @expo/next-adapter@3.1.18
- @expo/pkcs12@0.0.7
- @expo/prebuild-config@3.0.17
- expo-pwa@0.0.112
- uri-scheme@1.0.113
- @expo/webpack-config@0.16.17
- xdl@59.2.25

## [Wed, 12 Jan 2022 13:56:55 +0100](https://github.com/expo/expo-cli/commit/9e79e507e3de51dbc48db762f36d680b845760e8)

### 🎉 New features

- [cli][init] Skip git init in monorepo ([#4121](https://github.com/expo/expo-cli/issues/4121))

### 🧹 Chores

- [cli] Remove instance of got ([#4112](https://github.com/expo/expo-cli/issues/4112))
- [cli] Remove instances of xdl ([#4113](https://github.com/expo/expo-cli/issues/4113))
- [cli] Remove pacote ([#4088](https://github.com/expo/expo-cli/issues/4088))
- [cli] deprecate unused `expo start` options ([#4092](https://github.com/expo/expo-cli/issues/4092))
- [cli] suppress unauthorized warning on login and logout after logging out of all sessions on website ([#4120](https://github.com/expo/expo-cli/issues/4120))
- [install-expo-modules] Add begin-rescue to Podfile ([#4131](https://github.com/expo/expo-cli/issues/4131))
- [install-expo-modules] Fix invalid installation for yarn 2 ([#4130](https://github.com/expo/expo-cli/issues/4130))
- [repo] Refactor chalk imports ([#4111](https://github.com/expo/expo-cli/issues/4111))
- [repo] lerna version bump and config update ([#4117](https://github.com/expo/expo-cli/issues/4117))
- [xdl] switch cloudfront domain to classic-assets.eascdn.net ([#4115](https://github.com/expo/expo-cli/issues/4115))

### 🐛 Bug fixes

- [cli] Refactor NotificationCode to LoadingEvent ([#4136](https://github.com/expo/expo-cli/issues/4136))
- [package-manager] Fix `pod repo update` not automatically running ([#4084](https://github.com/expo/expo-cli/issues/4084))
- [plist] Skip plist keys if value is undefined ([#4109](https://github.com/expo/expo-cli/issues/4109))
- [xdl] Fix various ngrok bugs ([#4132](https://github.com/expo/expo-cli/issues/4132))

### 📦 Packages updated

- @expo/config-plugins@4.0.16
- @expo/config@6.0.16
- @expo/dev-server@0.1.103
- @expo/dev-tools@0.13.140
- expo-cli@5.0.5
- expo-optimize@0.2.8
- install-expo-modules@0.2.2
- @expo/metro-config@0.3.9
- @expo/next-adapter@3.1.17
- @expo/package-manager@0.0.49
- @expo/plist@0.0.17
- pod-install@0.1.31
- @expo/prebuild-config@3.0.16
- expo-pwa@0.0.111
- uri-scheme@1.0.112
- @expo/webpack-config@0.16.16
- xdl@59.2.24

## [Wed, 22 Dec 2021 14:05:44 +0800](https://github.com/expo/expo-cli/commit/de947a91dfc3aa5c4b92330c3c03ec6649e0129f)

### 🐛 Bug fixes

- [install-expo-modules] Add `expo_patch_react_imports!` for sdk 44 ([#4090](https://github.com/expo/expo-cli/issues/4090))
- Remove all `yarn global add X` prompts ([#4086](https://github.com/expo/expo-cli/issues/4086))
- [config-plugins] throw if there is a runtime version mismatch ([#4078](https://github.com/expo/expo-cli/issues/4078))
- [prebuild-config] update expo-modules-autolinking version ([#4083](https://github.com/expo/expo-cli/issues/4083))

### 📦 Packages updated

- @expo/config-plugins@4.0.15
- @expo/config@6.0.15
- @expo/dev-server@0.1.102
- @expo/dev-tools@0.13.139
- expo-cli@5.0.4
- expo-optimize@0.2.7
- install-expo-modules@0.2.1
- @expo/metro-config@0.3.8
- @expo/next-adapter@3.1.16
- pod-install@0.1.30
- @expo/prebuild-config@3.0.15
- expo-pwa@0.0.110
- uri-scheme@1.0.111
- @expo/webpack-config@0.16.15
- xdl@59.2.23

## [Thu, 16 Dec 2021 15:44:19 -0800](https://github.com/expo/expo-cli/commit/487031d3de00d9710aadbf32913cd831158a771f)

### 🎉 New features

- [install-expo-modules] Add Expo SDK 44 support ([#4077](https://github.com/expo/expo-cli/issues/4077))
- [cli] Allow specifying `expo config --json` in order to output config as a valid json string. ([#4071](https://github.com/expo/expo-cli/issues/4071))

### 📦 Packages updated

- @expo/dev-tools@0.13.138
- expo-cli@5.0.3
- install-expo-modules@0.2.0
- xdl@59.2.22

## [Wed, 15 Dec 2021 19:25:08 -0800](https://github.com/expo/expo-cli/commit/c610a9b2b5864dd614fc12aefc55cc74b92d8e61)

### 🎉 New features

- [config-plugins] Resolve against fully qualified MainApplications ([#4072](https://github.com/expo/expo-cli/issues/4072))
- [config-plugins][prebuild-config] Set iOS PRODUCT_NAME on prebuild ([#4064](https://github.com/expo/expo-cli/issues/4064))

### 🧹 Chores

- [cli] replace few Lodash methods with native code ([#4059](https://github.com/expo/expo-cli/issues/4059))
- [schemer] replace few Lodash methods with native code ([#4057](https://github.com/expo/expo-cli/issues/4057))

### 🐛 Bug fixes

- [config-plugins] Fix adding Google maps pods ([#4075](https://github.com/expo/expo-cli/issues/4075))

### 📦 Packages updated

- @expo/config-plugins@4.0.14
- @expo/config@6.0.14
- @expo/dev-server@0.1.101
- @expo/dev-tools@0.13.137
- expo-cli@5.0.2
- expo-optimize@0.2.6
- install-expo-modules@0.1.6
- @expo/metro-config@0.3.7
- @expo/next-adapter@3.1.15
- @expo/prebuild-config@3.0.14
- expo-pwa@0.0.109
- @expo/schemer@1.3.33
- uri-scheme@1.0.110
- @expo/webpack-config@0.16.14
- xdl@59.2.21

### [Tue, 14 Dec 2021 11:14:43 -0800](https://github.com/expo/expo-cli/commit/d2aca480eea9d9ab570ba0e10f1963c0613052db)

### 🎉 New features

- [config-plugins] Add plugin to restrict android permissions ([#3817](https://github.com/expo/expo-cli/issues/3817))

### 🧹 Chores

- [cli] Update link to eas build info

### 🐛 Bug fixes

- [config-plugins] Fix react-native-maps regex to account for React AppDelegate ([#4068](https://github.com/expo/expo-cli/issues/4068))
- [prebuild-config] Revert autolinking config plugin behavior to always add expo-dev-client plugin when installed ([#4070](https://github.com/expo/expo-cli/issues/4070))
- [prebuild-config] android.icon now properly overrides root icon property ([#4063](https://github.com/expo/expo-cli/issues/4063))

### 📦 Packages updated

- @expo/config-plugins@4.0.13
- @expo/config@6.0.13
- @expo/dev-server@0.1.100
- @expo/dev-tools@0.13.136
- expo-cli@5.0.1
- expo-optimize@0.2.5
- install-expo-modules@0.1.5
- @expo/metro-config@0.3.6
- @expo/next-adapter@3.1.14
- @expo/prebuild-config@3.0.13
- expo-pwa@0.0.108
- uri-scheme@1.0.109
- @expo/webpack-config@0.16.13
- xdl@59.2.20# [Tue, 14 Dec 2021 11:14:43 -0800](https://github.com/expo/expo-cli/commit/d2aca480eea9d9ab570ba0e10f1963c0613052db)

### 🛠 Breaking changes

### 🎉 New features

### 🧹 Chores

### 🐛 Bug fixes

- Update getAutolinkedPackages.ts ([#4070](https://github.com/expo/expo-cli/issues/4070))
- [config-plugins] Fix react-native-maps regex to account for React AppDelegate ([#4068](https://github.com/expo/expo-cli/issues/4068))
- Add plugin to restrict android permissions ([#3817](https://github.com/expo/expo-cli/issues/3817))
- fix e2e tests
- [cli] Update link to eas build info
- Update withAndroidIcons.ts ([#4063](https://github.com/expo/expo-cli/issues/4063))
- Update CHANGELOG and commit schema cache

### 📦 Packages updated

- @expo/config-plugins@4.0.13
- @expo/config@6.0.13
- @expo/dev-server@0.1.100
- @expo/dev-tools@0.13.136
- expo-cli@5.0.1
- expo-optimize@0.2.5
- install-expo-modules@0.1.5
- @expo/metro-config@0.3.6
- @expo/next-adapter@3.1.14
- @expo/prebuild-config@3.0.13
- expo-pwa@0.0.108
- uri-scheme@1.0.109
- @expo/webpack-config@0.16.13
- xdl@59.2.20

## [Mon, 13 Dec 2021 11:00:23 -0800](https://github.com/expo/expo-cli/commit/1387ccc525abd7d55436004cb84e787d00728cb0)

### 🧹 Chores

- [expo-cli] Add deprecation notice to build commands ([#4056](https://github.com/expo/expo-cli/issues/4056))

### 🐛 Bug fixes

- [next-adapter] fix incorrect detection of webpack 5 ([#4058](https://github.com/expo/expo-cli/issues/4058))
- [cli] prebuild should keep expo-updates package in sdk 44 ([#4061](https://github.com/expo/expo-cli/issues/4061))

### 📦 Packages updated

- @expo/dev-tools@0.13.135
- expo-cli@5.0.0
- @expo/next-adapter@3.1.13
- xdl@59.2.19

## [Thu, 9 Dec 2021 14:38:50 -0800](https://github.com/expo/expo-cli/commit/e24ce591c0051d7300f048f19fb252717f4870b8)

### 🎉 New features

- [cli] Always upgrade expo package when prereleased ([#3936](https://github.com/expo/expo-cli/issues/3936))
- [cli] Server modern manifest type with EAS Update updates.url ([#4054](https://github.com/expo/expo-cli/issues/4054))
- [prebuild-config] use autolinking for auto plugins ([#3926](https://github.com/expo/expo-cli/issues/3926))

### 🧹 Chores

- [interstitial] Capture analytics event when user selects "custom client" ([#4023](https://github.com/expo/expo-cli/issues/4023))
- [xdl] remove username and project root from analytics events ([#4049](https://github.com/expo/expo-cli/issues/4049))

### 📦 Packages updated

- @expo/config-plugins@4.0.12
- @expo/config@6.0.12
- @expo/dev-server@0.1.99
- @expo/dev-tools@0.13.134
- expo-cli@5.0.0-rc.4
- expo-optimize@0.2.4
- install-expo-modules@0.1.4
- @expo/metro-config@0.3.5
- @expo/next-adapter@3.1.12
- @expo/prebuild-config@3.0.12
- expo-pwa@0.0.107
- uri-scheme@1.0.108
- @expo/webpack-config@0.16.12
- xdl@59.2.18

## [Fri, 3 Dec 2021 10:48:28 -0800](https://github.com/expo/expo-cli/commit/ce6fd8710d895074becf48b0fac3907cf87c6192)

### 🎉 New features

- [cli][install] use recommended versions from remote ([#4014](https://github.com/expo/expo-cli/issues/4014))
- [config-plugins] use new error recovery setting in config plugin for updates 0.11.x ([#4043](https://github.com/expo/expo-cli/issues/4043))
- [config-plugins] Automatically remove auto generated intent filters ([#4042](https://github.com/expo/expo-cli/issues/4042))
- [config-plugins] Added buildscript.ext version plugin ([#4038](https://github.com/expo/expo-cli/issues/4038))

### 🧹 Chores

- [config-plugins] Added maps resolution back ([#4047](https://github.com/expo/expo-cli/issues/4047))

### 🐛 Bug fixes

- [config-plugins] fix reading target dependencies ([#4048](https://github.com/expo/expo-cli/issues/4048))
- [config-plugins] add missing sdk-runtime-versions dep ([#4045](https://github.com/expo/expo-cli/issues/4045))
- [config-plugins] Ensure TeamID has quotes around it ([#4040](https://github.com/expo/expo-cli/issues/4040))

### 📦 Packages updated

- @expo/config-plugins@4.0.11
- @expo/config@6.0.11
- @expo/dev-server@0.1.98
- @expo/dev-tools@0.13.133
- expo-cli@5.0.0-rc.3
- expo-optimize@0.2.3
- install-expo-modules@0.1.3
- @expo/metro-config@0.3.4
- @expo/next-adapter@3.1.11
- @expo/prebuild-config@3.0.11
- expo-pwa@0.0.106
- uri-scheme@1.0.107
- @expo/webpack-config@0.16.11
- xdl@59.2.17

## [Mon, 29 Nov 2021 13:33:11 -0800](https://github.com/expo/expo-cli/commit/3917a2784f64517caa92b058e755efcc76cd9bfb)

### 🎉 New features

- [config-plugins] Export withPodfileProperties ([#4036](https://github.com/expo/expo-cli/issues/4036))

### 🐛 Bug fixes

- [prebuild-config] Fix autolinking issue ([#4039](https://github.com/expo/expo-cli/issues/4039))
- Update CHANGELOG

### 📦 Packages updated

- @expo/config-plugins@4.0.10
- @expo/config@6.0.10
- @expo/dev-server@0.1.97
- @expo/dev-tools@0.13.132
- expo-cli@5.0.0-rc.2
- expo-optimize@0.2.2
- install-expo-modules@0.1.2
- @expo/metro-config@0.3.3
- @expo/next-adapter@3.1.10
- @expo/prebuild-config@3.0.10
- expo-pwa@0.0.105
- uri-scheme@1.0.106
- @expo/webpack-config@0.16.10
- xdl@59.2.16

## [Fri, 26 Nov 2021 13:30:44 -0800](https://github.com/expo/expo-cli/commit/a43843a619d58b165eb7fcb4bcfd3ee7aaac65fd)

### 🧹 Chores

- [expo-cli] check update URL is not pointing at EAS ([#4032](https://github.com/expo/expo-cli/issues/4032))
- [prebuild-config] Drop unversioned apple authentication support ([#4031](https://github.com/expo/expo-cli/issues/4031))
- [prebuild-config] Revert "Skip APNS entitlement by default unless expo-notifications is installed ([#4001](https://github.com/expo/expo-cli/issues/4001))"

### 🐛 Bug fixes

- [webpack-config] Fix native asset loading ([#4034](https://github.com/expo/expo-cli/issues/4034))
- [expo-cli] fix runtime version validation error ([#4033](https://github.com/expo/expo-cli/issues/4033))

### 📦 Packages updated

- @expo/config-plugins@4.0.9
- @expo/config@6.0.9
- @expo/dev-server@0.1.96
- @expo/dev-tools@0.13.131
- expo-cli@5.0.0-rc.1
- expo-optimize@0.2.1
- install-expo-modules@0.1.1
- @expo/metro-config@0.3.2
- @expo/next-adapter@3.1.9
- @expo/prebuild-config@3.0.9
- expo-pwa@0.0.104
- uri-scheme@1.0.105
- @expo/webpack-config@0.16.9
- xdl@59.2.15

## [Wed, 24 Nov 2021 14:52:26 -0800](https://github.com/expo/expo-cli/commit/8ca2a96f4cc092b602ec37c3754302943ae81f2e)

### 🛠 Breaking changes

- [cli] Drop `expo client:ios` ([#4009](https://github.com/expo/expo-cli/issues/4009))
- [cli] Move `expo upload:android` to `eas submit -p android` ([#3991](https://github.com/expo/expo-cli/issues/3991))
- [cli] Skip showing dev tools UI on startup for new users ([#3966](https://github.com/expo/expo-cli/issues/3966))

### 🎉 New features

- [cli] Add --no-build-cache to clear the derived data folder for ios builds ([#4010](https://github.com/expo/expo-cli/issues/4010))
- [cli] Add more packages to diagnostics ([#3996](https://github.com/expo/expo-cli/issues/3996))
- [cli] Auto setup web support ([#3994](https://github.com/expo/expo-cli/issues/3994))
- [cli] Handle unhandled errors from Terminal UI ([#4006](https://github.com/expo/expo-cli/issues/4006))
- [cli] Prevent forbidden project names ([#4025](https://github.com/expo/expo-cli/issues/4025))
- [cli][xdl][dev-client] Add interstitial disambiguation page ([#3899](https://github.com/expo/expo-cli/issues/3899))
- [config-plugins] Added warning for using backgroundColor on iOS ([#4012](https://github.com/expo/expo-cli/issues/4012))
- [config-plugins] Support schemes with a dot in the name ([#4003](https://github.com/expo/expo-cli/issues/4003))
- [config-plugins] fix setting CODE_SIGN_ENTITLEMENTS ([#4007](https://github.com/expo/expo-cli/issues/4007))
- [config-plugins][prebuild-config] Skip APNS entitlement by default unless expo-notifications is installed ([#4001](https://github.com/expo/expo-cli/issues/4001))
- [expo-cli] parallelize expo-optimize ([#3956](https://github.com/expo/expo-cli/issues/3956))

### 🧹 Chores

- [webpack-config] Bump fixtures SDK 43 ([#4028](https://github.com/expo/expo-cli/issues/4028))
- [config-plugins] consolidate getRuntimeVersionNullable ([#4029](https://github.com/expo/expo-cli/issues/4029))
- [cli] use 'better-opn' instead of 'react-dev-utils/openBrowser' ([#4018](https://github.com/expo/expo-cli/issues/4018))
- [xdl] Bump rudder node sdk ([#4030](https://github.com/expo/expo-cli/issues/4030))
- [cli] Bump @expo/xcpretty ([#4027](https://github.com/expo/expo-cli/issues/4027))
- [cli] Move publish command to the publish help group ([#4019](https://github.com/expo/expo-cli/issues/4019))
- [cli] Chunk build logs ([#4021](https://github.com/expo/expo-cli/issues/4021))
- [cli] refactor files ([#3995](https://github.com/expo/expo-cli/issues/3995))
- Refactor project owner method ([#4017](https://github.com/expo/expo-cli/issues/4017))
- [cli][run] Don't export logs as markdown ([#4011](https://github.com/expo/expo-cli/issues/4011))
- Import general fixes from autolinking PR ([#3993](https://github.com/expo/expo-cli/issues/3993))
- Upgrade expo e2e test to 43 ([#3581](https://github.com/expo/expo-cli/issues/3581))
- Rename master branch to main

### 🐛 Bug fixes

- [config-plugins] fix android strings xml ([#4004](https://github.com/expo/expo-cli/issues/4004))
- [install-expo-modules] Fix workspace support ([#4024](https://github.com/expo/expo-cli/issues/4024))
- [prebuild-config] add missing dependency ([#4013](https://github.com/expo/expo-cli/issues/4013))
- [xdl] Remove md extension from expo updates config fyi link ([#4022](https://github.com/expo/expo-cli/issues/4022))

### 📦 Packages updated

- @expo/babel-preset-cli@0.2.23
- @expo/config-plugins@4.0.8
- @expo/config@6.0.8
- @expo/dev-server@0.1.95
- @expo/dev-tools@0.13.130
- expo-cli@5.0.0-rc.0
- expo-codemod@1.1.5
- expo-optimize@0.2.0
- @expo/image-utils@0.3.18
- install-expo-modules@0.1.0
- @expo/json-file@8.2.34
- @expo/metro-config@0.3.1
- @expo/next-adapter@3.1.8
- @expo/osascript@2.0.31
- @expo/package-manager@0.0.48
- @expo/pkcs12@0.0.6
- @expo/plist@0.0.16
- pod-install@0.1.29
- @expo/prebuild-config@3.0.8
- expo-pwa@0.0.103
- @expo/schemer@1.3.32
- uri-scheme@1.0.104
- @expo/webpack-config@0.16.8
- xdl@59.2.14

## [Mon, 8 Nov 2021 17:19:54 -0800](https://github.com/expo/expo-cli/commit/61315e0ef950a2d1359dfba33c1ca12e7aa960ee)

### 🎉 New features

- [prebuild-config] Add unversioned expo-system-ui plugin ([#3957](https://github.com/expo/expo-cli/issues/3957))
- [prebuild-config] Add url support for splash screens ([#3978](https://github.com/expo/expo-cli/issues/3978))
- [metro-config] Add environment variable for forcing the use of unversioned config plugins ([#3984](https://github.com/expo/expo-cli/issues/3984))
- [webpack-config] Add support for any main file in Webpack ([#3973](https://github.com/expo/expo-cli/issues/3973))

### 🧹 Chores

- [cli] Change "dev client" to "development build" ([#3946](https://github.com/expo/expo-cli/issues/3946))
- [xdl] Swap out Cloudfront CDN for `classic-assets.eascdn.net`. ([#4115](https://github.com/expo/expo-cli/issues/4115))

### 📦 Packages updated

- @expo/config-plugins@4.0.7
- @expo/config@6.0.7
- @expo/dev-server@0.1.94
- @expo/dev-tools@0.13.129
- expo-cli@4.13.0
- expo-optimize@0.1.114
- install-expo-modules@0.0.6
- @expo/metro-config@0.3.0
- @expo/next-adapter@3.1.7
- @expo/prebuild-config@3.0.7
- expo-pwa@0.0.102
- uri-scheme@1.0.103
- @expo/webpack-config@0.16.7
- xdl@59.2.13

## [Thu, 4 Nov 2021 13:01:04 -0700](https://github.com/expo/expo-cli/commit/507c1e8c6973290a649675d292a137fb75306bcd)

### 🎉 New features

- Use expo run commands on prebuild/eject ([#3549](https://github.com/expo/expo-cli/issues/3549))

### 🧹 Chores

- Bump @expo/xcpretty@4.0.0 ([#3968](https://github.com/expo/expo-cli/issues/3968))

### 🐛 Bug fixes

- Revert "Add built-in support for Yarn workspaces ([#3945](https://github.com/expo/expo-cli/issues/3945))"

### 📦 Packages updated

- @expo/dev-server@0.1.93
- @expo/dev-tools@0.13.128
- expo-cli@4.12.12
- @expo/metro-config@0.2.8
- xdl@59.2.12

### 🐛 Bug fixes

## [Tue, 2 Nov 2021 10:48:05 -0700](https://github.com/expo/expo-cli/commit/7c096e60ac0a6ce52f90a8532d3e6184d4ead597)

### 🛠 Breaking changes

### 🎉 New features

- [dev-server] Enhance hermes inspector opening experience ([#3967](https://github.com/expo/expo-cli/issues/3967))
- [metro-config] Add built-in support for Yarn workspaces ([#3945](https://github.com/expo/expo-cli/issues/3945))

### 🧹 Chores

- [cli][init] add package.json name and version ([#3942](https://github.com/expo/expo-cli/issues/3942))
- [cli][install] Reduce plugin validation after install ([#3940](https://github.com/expo/expo-cli/issues/3940))

### 🐛 Bug fixes

- [cli] Bump to apple-utils 26 to fix unhandled error on 403 from Apple ([#3958](https://github.com/expo/expo-cli/issues/3958))
- [cli] Revert open in editor to a more stable revision ([#3964](https://github.com/expo/expo-cli/issues/3964))
- [metro-config] Fix bug preventing babel.config.js from being used ([#3965](https://github.com/expo/expo-cli/issues/3965))

### 📦 Packages updated

- @expo/dev-server@0.1.92
- @expo/dev-tools@0.13.127
- expo-cli@4.12.11
- @expo/metro-config@0.2.7
- xdl@59.2.11

## [Fri, 22 Oct 2021 14:41:44 -0700](https://github.com/expo/expo-cli/commit/6b6cedbfa1cb96c1a6d22f3cf9dbcdc87160c2ef)

### 🛠 Breaking changes

### 🎉 New features

- [config-plugins] Add property to update iOS bitcode setting ([#3933](https://github.com/expo/expo-cli/issues/3933))

### 🧹 Chores

- [config-types] Bump version
- [expo-cli] Fix lint warning accidentally introduced in hotfix

### 🐛 Bug fixes

- [prebuild-config] Skip deleting UIUserInterfaceStyle for now ([#3941](https://github.com/expo/expo-cli/issues/3941))

### 📦 Packages updated

- @expo/config-plugins@4.0.6
- @expo/config@6.0.6
- @expo/dev-server@0.1.91
- @expo/dev-tools@0.13.126
- expo-cli@4.12.10
- expo-optimize@0.1.113
- install-expo-modules@0.0.5
- @expo/metro-config@0.2.6
- @expo/next-adapter@3.1.6
- @expo/prebuild-config@3.0.6
- expo-pwa@0.0.101
- uri-scheme@1.0.102
- @expo/webpack-config@0.16.6
- xdl@59.2.10

## [Thu, 21 Oct 2021 18:23:36 -0700](https://github.com/expo/expo-cli/commit/7d8d7202185f79061a0e69cb7a84bfb6b879efe4)

### 🛠 Breaking changes

### 🎉 New features

### 🧹 Chores

- [config-plugins] Convert NavigationBar to an unversioned plugin ([#3902](https://github.com/expo/expo-cli/issues/3902))

### 🐛 Bug fixes

- [expo-cli] Revert Info.plist lookup change
- [dev-server] fix app hanging if hermes inspector opening and reload app ([#3932](https://github.com/expo/expo-cli/issues/3932))

### 📦 Packages updated

- @expo/config-plugins@4.0.4
- @expo/config@6.0.4
- @expo/dev-server@0.1.89
- @expo/dev-tools@0.13.124
- expo-cli@4.12.8
- expo-optimize@0.1.111
- install-expo-modules@0.0.3
- @expo/metro-config@0.2.4
- @expo/next-adapter@3.1.4
- @expo/prebuild-config@3.0.4
- expo-pwa@0.0.99
- uri-scheme@1.0.100
- @expo/webpack-config@0.16.4
- xdl@59.2.8

## [Wed, 20 Oct 2021 19:32:55 -0700](https://github.com/expo/expo-cli/commit/8f9bd4c43889826f5058a91d060dba2b594240ef)

### 🐛 Bug fixes

- [cli] Disable auto detection of manifest type until a more reliable mechanism is ready

### 📦 Packages updated

- @expo/dev-tools@0.13.123
- expo-cli@4.12.7
- xdl@59.2.7

## [Wed, 20 Oct 2021 10:33:37 -0700](https://github.com/expo/expo-cli/commit/5d0a7bf6368e044fd5f0624d6b355c20f4528b5c)

### 🐛 Bug fixes

- [xdl] Add missing nullthrows package

### 📦 Packages updated

- @expo/dev-tools@0.13.122
- expo-cli@4.12.6
- xdl@59.2.6

## [Tue, 19 Oct 2021 16:13:11 -0700](https://github.com/expo/expo-cli/commit/159c7fc92ed430962a5a799b23743196867449ac)

### 🐛 Bug fixes

- [cli] Fix reading EAS project ID from app.json during start ([#3929](https://github.com/expo/expo-cli/issues/3929))

### 📦 Packages updated

- @expo/dev-tools@0.13.121
- expo-cli@4.12.5
- xdl@59.2.5

## [Tue, 19 Oct 2021 12:55:08 -0700](https://github.com/expo/expo-cli/commit/93426f59c26c89e22f88420aed14c89cde6807d3)

### 🛠 Breaking changes

### 🎉 New features

- [cli] Use expoConfig.extra.eas.projectId to determine which type of development manifest to serve ([#3890](https://github.com/expo/expo-cli/issues/3890))
- [config-plugins] Update AndroidManifest.xml template for introspection ([#3881](https://github.com/expo/expo-cli/issues/3881))
- [config-plugins] introduce codeMod ([#3909](https://github.com/expo/expo-cli/issues/3909))
- [dev-server] fix react-native +65 support ([#3923](https://github.com/expo/expo-cli/issues/3923))
- [expo-cli] add hermes inspector support in terminal ui ([#3894](https://github.com/expo/expo-cli/issues/3894))
- [metro-config] Added exotic docs ([#3914](https://github.com/expo/expo-cli/issues/3914))
- [metro-config] Create modular transformer API ([#3887](https://github.com/expo/expo-cli/issues/3887))
- [metro-config] extend Exotic API ([#3915](https://github.com/expo/expo-cli/issues/3915))
- [xdl][expo-cli] Improve metro bundler errors ([#3924](https://github.com/expo/expo-cli/issues/3924))

### 🧹 Chores

- [config-plugins] Added test app delegate for SDK 43 maps ([#3913](https://github.com/expo/expo-cli/issues/3913))
- [config-plugins] Fix runtimeVersion test
- [config-plugins] Move Branch config plugin to unversioned expo-branch ([#3903](https://github.com/expo/expo-cli/issues/3903))
- [config-plugins] Move Facebook config plugin to unversioned expo-facebook ([#3904](https://github.com/expo/expo-cli/issues/3904))
- [config-plugins] use exact xml2js version ([#3920](https://github.com/expo/expo-cli/issues/3920))
- [expo-cli] Bump envinfo ([#3882](https://github.com/expo/expo-cli/issues/3882))
- [expo-cli] Update unable to reach server message for bundledNativeModules.json
- [expo-cli] updated introspection script for fig mode ([#3912](https://github.com/expo/expo-cli/issues/3912))
- [webpack] Remove extra config values from public web manifest ([#3811](https://github.com/expo/expo-cli/issues/3811))
- [xdl] analytics updated from username => userid ([#3916](https://github.com/expo/expo-cli/issues/3916))
- [xdl] improvement: round bundle progress % to 2 digits ([#3917](https://github.com/expo/expo-cli/issues/3917))
- [xdl][config-types][config-plugins] update runtimeVersion policy types ([#3893](https://github.com/expo/expo-cli/issues/3893))

### 🐛 Bug fixes

- [dev-server][xdl] suppress remote debugging EISDIR error ([#3889](https://github.com/expo/expo-cli/issues/3889))
- [expo-cli] Fix running expo start --dev-client in a project without expo installed ([#3921](https://github.com/expo/expo-cli/issues/3921))
- [image-utils] Fix resolving global sharp-cli for windows users ([#3895](https://github.com/expo/expo-cli/issues/3895))
- [webpack] Fix asset hosting on native webpack ([#3869](https://github.com/expo/expo-cli/issues/3869))
- [xdl] Fix RN version validation ([#3922](https://github.com/expo/expo-cli/issues/3922))

### 📦 Packages updated

- @expo/config-plugins@4.0.3
- @expo/config@6.0.3
- @expo/dev-server@0.1.88
- @expo/dev-tools@0.13.120
- expo-cli@4.12.4
- expo-optimize@0.1.110
- @expo/image-utils@0.3.17
- install-expo-modules@0.0.2
- @expo/metro-config@0.2.3
- @expo/next-adapter@3.1.3
- @expo/prebuild-config@3.0.3
- expo-pwa@0.0.98
- uri-scheme@1.0.99
- @expo/webpack-config@0.16.3
- xdl@59.2.4

## [Tue, 5 Oct 2021 17:10:41 -0700](https://github.com/expo/expo-cli/commit/b6d4505fb66ce1809096c45099294b4f0c7f657c)

### 🧹 Chores

- [config-types] Update for SDK 43. [31edae](https://github.com/expo/expo-cli/commit/31edae)

### 🐛 Bug fixes

- [config-plugins][expo-cli][xdl] Fix runtimeVersion related code to build against config-types. [909d47](https://github.com/expo/expo-cli/commit/909d47)

### 📦 Packages updated

_Note_: a patch version was skipped due to a failed build that was resolved in [909d47](https://github.com/expo/expo-cli/commit/909d47)

- @expo/config-plugins@4.0.2
- @expo/config@6.0.2
- @expo/dev-server@0.1.87
- @expo/dev-tools@0.13.119
- expo-cli@4.12.3
- expo-optimize@0.1.109
- @expo/metro-config@0.2.2
- @expo/next-adapter@3.1.2
- @expo/prebuild-config@3.0.2
- expo-pwa@0.0.97
- uri-scheme@1.0.98
- @expo/webpack-config@0.16.2
- xdl@59.2.3

## [Fri, 1 Oct 2021 14:44:35 -0700](https://github.com/expo/expo-cli/commit/7621454e3b2e47e5341da5076183f5da819cbd8e)

### 🛠 Breaking changes

### 🎉 New features

- [expo-cli] Add version check fallback for packages with exports ([#3878](https://github.com/expo/expo-cli/issues/3878))
- [expo-cli][xdl] Remove expo forked react-native from managed apps on SDK 43+ ([#3821](https://github.com/expo/expo-cli/issues/3821))

### 🧹 Chores

- [expo-cli] bump @expo/rudder-sdk-node ([#3875](https://github.com/expo/expo-cli/issues/3875))
- [pod-install] mention `macos` directory in Readme ([#3870](https://github.com/expo/expo-cli/issues/3870))

### 🐛 Bug fixes

- [expo-cli] Remove incorrect platform from 'dev client start command' event ([#3874](https://github.com/expo/expo-cli/issues/3874))
- [expo-cli] Fix loader bug ([#3867](https://github.com/expo/expo-cli/issues/3867))

### 📦 Packages updated

- @expo/dev-tools@0.13.117
- expo-cli@4.12.1
- pod-install@0.1.28
- xdl@59.2.1

## [Tue, 21 Sep 2021 14:39:00 -0700](https://github.com/expo/expo-cli/commit/d614ee9c98268686dbe5eeea5bfa512b89325d3f)

### 🛠 Breaking changes

- [cli] Remove prompts to install Expo Go on upgrade ([#3853](https://github.com/expo/expo-cli/issues/3853))

### 🎉 New features

- [config-cli][xdl] add getRuntimeVersion method ([#3803](https://github.com/expo/expo-cli/issues/3803))
- [config-plugins] Add hermes support for ios Podfile.properties.json ([#3796](https://github.com/expo/expo-cli/issues/3796))
- [config-plugins] Escape single quotes in project name ([#3838](https://github.com/expo/expo-cli/issues/3838))
- [config-plugins] extend base mods ([#3852](https://github.com/expo/expo-cli/issues/3852))
- [configure-splash-screen] support new expo-splash-screen to setup imageResizeMode and statusBarTranslucent in resource ([#3774](https://github.com/expo/expo-cli/issues/3774))
- [dev-server] support building hermes bytecode bundle for ios ([#3814](https://github.com/expo/expo-cli/issues/3814))
- [expo-cli] generate smaller QR codes ([#3800](https://github.com/expo/expo-cli/issues/3800))
- [expo-cli] minimize spacing to fit smaller QR codes ([#3812](https://github.com/expo/expo-cli/issues/3812))
- [expo-cli] start project using application identifier ([#3737](https://github.com/expo/expo-cli/issues/3737))
- [expo-cli] use platforms array for disabling platforms ([#3844](https://github.com/expo/expo-cli/issues/3844))
- [expo-cli][run:android] add flavors support ([#3856](https://github.com/expo/expo-cli/issues/3856))
- [expo-cli][run:ios] Add --no-install option to expo run:ios ([#3851](https://github.com/expo/expo-cli/issues/3851))
- [expo-cli][run:ios] JS API for iOS binary install, and connected devices ([#3847](https://github.com/expo/expo-cli/issues/3847))
- [metro-config] Added improved babel loading ([#3861](https://github.com/expo/expo-cli/issues/3861))
- [prebuild-config] Support new expo-splash-screen to manage resizeMode in resource ([#3784](https://github.com/expo/expo-cli/issues/3784))
- [webpack-config] Add native asset loader ([#3801](https://github.com/expo/expo-cli/issues/3801))
- [webpack] Add metro runtime shim ([#3809](https://github.com/expo/expo-cli/issues/3809))
- [xdl][config] Implement naive manifest signing for EAS update manifests ([#3831](https://github.com/expo/expo-cli/issues/3831))

### 🧹 Chores

- [config-plugins] Use upstream react-native/normalize-color ([#3826](https://github.com/expo/expo-cli/issues/3826))
- [dev-server] Added webpack symbolicator ([#3819](https://github.com/expo/expo-cli/issues/3819))
- [dev-server] Improve the symbolicator ([#3822](https://github.com/expo/expo-cli/issues/3822))
- [dev-server] chore: missing deps #3813 ([#3818](https://github.com/expo/expo-cli/issues/3818))
- [eas-cli][xdl] Removes Segment ([#3805](https://github.com/expo/expo-cli/issues/3805))
- [expo-cli] Enable sockets in native webpack ([#3823](https://github.com/expo/expo-cli/issues/3823))
- [expo-cli] refactor export command ([#3794](https://github.com/expo/expo-cli/issues/3794))
- [expo-cli] remove warning aggregator batched logging ([#3799](https://github.com/expo/expo-cli/issues/3799))
- [next-adapter] Disable lint warnings ([#3866](https://github.com/expo/expo-cli/issues/3866))
- [next-adapter] update babel config ([#3834](https://github.com/expo/expo-cli/issues/3834))
- [webpack] Add all native middleware to webpack ([#3808](https://github.com/expo/expo-cli/issues/3808))
- [webpack] Added unified logging ([#3766](https://github.com/expo/expo-cli/issues/3766))
- [xdl] throw if AndroidManifest.xml is missing a MainApplication ([#3825](https://github.com/expo/expo-cli/issues/3825))

### 🐛 Bug fixes

- [config-plugins] dodge extraneous Info.plist warning in managed projects ([#3835](https://github.com/expo/expo-cli/issues/3835))
- [expo-cli] remove ascii colors, add generated comments, sanitize descriptions, add version notice ([#3848](https://github.com/expo/expo-cli/issues/3848))
- [expo-cli][run] Fix linking issues ([#3857](https://github.com/expo/expo-cli/issues/3857))
- [xdl] Fix expo-updates EAS manifest assets for iOS ([#3860](https://github.com/expo/expo-cli/issues/3860))

### 📦 Packages updated

- @expo/config-plugins@4.0.0
- @expo/config@6.0.0
- @expo/configure-splash-screen@0.6.0
- @expo/dev-server@0.1.85
- @expo/dev-tools@0.13.116
- @expo/metro-config@0.2.0
- @expo/next-adapter@3.1.0
- @expo/plist@0.0.15
- @expo/prebuild-config@3.0.0
- @expo/webpack-config@0.16.0
- expo-cli@4.12.0
- expo-optimize@0.1.107
- expo-pwa@0.0.95
- uri-scheme@1.0.96
- xdl@59.2.0

## [Fri, 6 Aug 2021 13:06:23 -0700](https://github.com/expo/expo-cli/commit/cb9ec2ec1d33f484fd956ac9669926443904a6cb)

### 🛠 Breaking changes

- [webpack-config] Drop workbox support ([#3729](https://github.com/expo/expo-cli/issues/3729))

### 🎉 New features

- [cli] added fig icons ([#3733](https://github.com/expo/expo-cli/issues/3733))
- [cli][run:ios] Auto detect device type for scheme ([#3720](https://github.com/expo/expo-cli/issues/3720))

### 🧹 Chores

- [cli] Refactor TerminalUI commands ([#3749](https://github.com/expo/expo-cli/issues/3749))
- [cli] Support robot publishing of kernel when owner is supplied ([#3753](https://github.com/expo/expo-cli/issues/3753))
- [cli] prevent checking for updates more than once per run ([#3748](https://github.com/expo/expo-cli/issues/3748))
- [config-plugins][config-types] set default url returned by getUpdateU… ([#3456](https://github.com/expo/expo-cli/issues/3456))
- [readme] added box to side bar ([#3735](https://github.com/expo/expo-cli/issues/3735))
- [xdl] Move ngrok tools out of UrlUtils module ([#3739](https://github.com/expo/expo-cli/issues/3739))
- Bump babel/runtime ([#3732](https://github.com/expo/expo-cli/issues/3732))
- Restrict [native code] in stack traces ([#3742](https://github.com/expo/expo-cli/issues/3742))
- Upgrade uuid ([#3730](https://github.com/expo/expo-cli/issues/3730))

### 🐛 Bug fixes

- [cli] Fix downloading expo go progress bar bug
- [cli] various fixes from #3685 ([#3736](https://github.com/expo/expo-cli/issues/3736))
- [webpack-config] Remove progress and babel/runtime ([#3700](https://github.com/expo/expo-cli/issues/3700))
- [xdl] Upgrade @expo/ngrok ([#3740](https://github.com/expo/expo-cli/issues/3740))
- [xdl] pass appropriate headers when making getManifestCall ([#3751](https://github.com/expo/expo-cli/issues/3751))

### 📦 Packages updated

- @expo/config-plugins@3.0.7
- @expo/config@5.0.7
- @expo/dev-server@0.1.82
- @expo/dev-tools@0.13.113
- expo-cli@4.10.0
- expo-optimize@0.1.104
- @expo/json-file@8.2.33
- @expo/metro-config@0.1.82
- @expo/next-adapter@3.0.4
- @expo/package-manager@0.0.46
- pod-install@0.1.26
- @expo/prebuild-config@2.0.7
- expo-pwa@0.0.92
- uri-scheme@1.0.93
- @expo/webpack-config@0.14.0
- xdl@59.0.53

## [Thu, 29 Jul 2021 19:21:41 -0700](https://github.com/expo/expo-cli/commit/a94bed2031b86d244b143937fde14d97f2bc6a71)

### 🎉 New features

- Added fig to introspection script ([#3727](https://github.com/expo/expo-cli/issues/3727))

### 🧹 Chores

- [cli] Skip checking for latest expo-cli version on EAS Build
- Drop template sw file ([#3728](https://github.com/expo/expo-cli/issues/3728))

### 📦 Packages updated

- @expo/dev-tools@0.13.112
- expo-cli@4.9.1
- @expo/next-adapter@3.0.3
- @expo/webpack-config@0.13.3
- xdl@59.0.52

## [Wed, 28 Jul 2021 13:48:31 -0700](https://github.com/expo/expo-cli/commit/911c052e83d10b73b2a3971c9ec6c5eb26abba08)

### 🛠 Breaking changes

- [next-adapter] Remove custom server and service worker code ([#3705](https://github.com/expo/expo-cli/issues/3705))
- [webpack] Drop asset aliases ([#3706](https://github.com/expo/expo-cli/issues/3706))
- [webpack] Drop support for deep-scope plugin ([#3701](https://github.com/expo/expo-cli/issues/3701))
- [webpack] Drop support for worker-loader ([#3696](https://github.com/expo/expo-cli/issues/3696))

### 🎉 New features

- [cli] display correct manifest link after publish when using runtime version ([#3719](https://github.com/expo/expo-cli/issues/3719))
- [cli][config][xdl] support runtimeVersion in classic updates ([#3547](https://github.com/expo/expo-cli/issues/3547))
- [config-plugins] Added support for iOS rootViewBackgroundColor ([#3660](https://github.com/expo/expo-cli/issues/3660))
- [config-plugins] Added window soft input mode ([#3725](https://github.com/expo/expo-cli/issues/3725))
- [config-plugins] Fix multitasking ipad orientations ([#3710](https://github.com/expo/expo-cli/issues/3710))
- [image-utils] Use jimp compact ([#3698](https://github.com/expo/expo-cli/issues/3698))
- [readme] Added animated banner ([#3726](https://github.com/expo/expo-cli/issues/3726))
- Improved webpack bundling errors ([#3680](https://github.com/expo/expo-cli/issues/3680))

### 🧹 Chores

- [cli] Remove custom branch setting so that default branch set in global gitconfig is used ([#3702](https://github.com/expo/expo-cli/issues/3702))
- [cli][webpack] Allow customization to use local files ([#3695](https://github.com/expo/expo-cli/issues/3695))
- [config-plugins] use default value for android version code - for consistency with buildNumber on ios ([#3713](https://github.com/expo/expo-cli/issues/3713))
- [config] Improve error formatting for config reading in the CLI ([#3707](https://github.com/expo/expo-cli/issues/3707))
- [config] Remove fs-extra from config ([#3699](https://github.com/expo/expo-cli/issues/3699))
- [config] Replace babel with sucrase ([#3693](https://github.com/expo/expo-cli/issues/3693))
- [webpack] Drop partial / unsupported fast refresh web implementation ([#3697](https://github.com/expo/expo-cli/issues/3697))
- Remove shared monorepo deps ([#3704](https://github.com/expo/expo-cli/issues/3704))
- Remove eas sort group ([#3703](https://github.com/expo/expo-cli/issues/3703))
- Lazy load prebuild-config modules ([#3681](https://github.com/expo/expo-cli/issues/3681))
- Remove expo/simple-spinner ([#3683](https://github.com/expo/expo-cli/issues/3683))
- Combine similar commands ([#3684](https://github.com/expo/expo-cli/issues/3684))
- Remove term-size and slugid ([#3682](https://github.com/expo/expo-cli/issues/3682))

### 🐛 Bug fixes

- [cli] Fix hermesc.exe resolving on windows ([#3708](https://github.com/expo/expo-cli/issues/3708))
- [xdl] Fix legacy dev server port selection ([#3694](https://github.com/expo/expo-cli/issues/3694))

### 📦 Packages updated

- @expo/config-plugins@3.0.6
- @expo/config@5.0.6
- @expo/dev-server@0.1.81
- @expo/dev-tools@0.13.111
- expo-cli@4.9.0
- expo-codemod@1.1.4
- expo-optimize@0.1.103
- @expo/image-utils@0.3.16
- @expo/json-file@8.2.32
- @expo/metro-config@0.1.81
- @expo/next-adapter@3.0.2
- @expo/osascript@2.0.30
- @expo/package-manager@0.0.45
- pod-install@0.1.25
- @expo/prebuild-config@2.0.6
- expo-pwa@0.0.91
- @expo/schemer@1.3.31
- uri-scheme@1.0.92
- @expo/webpack-config@0.13.2
- xdl@59.0.51

## [Fri, 16 Jul 2021 11:09:46 -0700](https://github.com/expo/expo-cli/commit/ca2116669c211b4500893ce780dae62a3c41d50c)

### 🛠 Breaking changes

- [config] Switch requiresFullScreen to false in SDK 43 ([#3650](https://github.com/expo/expo-cli/issues/3650))

### 🎉 New features

- [cli] Added port option to expo start ([#3645](https://github.com/expo/expo-cli/issues/3645))
- [cli] Added skipPlugins prop to getConfig to support expo install better ([#3670](https://github.com/expo/expo-cli/issues/3670))
- [cli] Skip prompting to start dev server on another port ([#3635](https://github.com/expo/expo-cli/issues/3635))
- [config][xdl] Added flipper hack ([#3643](https://github.com/expo/expo-cli/issues/3643))
- [conifg][xdl] serve new expo-updates format manifests ([#3606](https://github.com/expo/expo-cli/issues/3606))
- [next-adapter] Update for NextJS 11.x ([#3586](https://github.com/expo/expo-cli/issues/3586))
- [webpack-config] Bump workbox-webpack-plugin ([#3641](https://github.com/expo/expo-cli/issues/3641))
- [xdl] Warn about babel config changing ([#3638](https://github.com/expo/expo-cli/issues/3638))

### 🧹 Chores

- [cli] Lazy load the start command ([#3673](https://github.com/expo/expo-cli/issues/3673))
- [cli] Restructure exp to load a little better ([#3672](https://github.com/expo/expo-cli/issues/3672))
- [cli] Split up e2e tests so they're only run when the user specifies ([#3655](https://github.com/expo/expo-cli/issues/3655))
- [cli] Upgraded fixtures to expo sdk 42 ([#3675](https://github.com/expo/expo-cli/issues/3675))
- [cli] improve spinners ([#3654](https://github.com/expo/expo-cli/issues/3654))
- [cli] lazy load customize:web diagnostics bundle-assets ([#3676](https://github.com/expo/expo-cli/issues/3676))
- [cli] lazy load install, eject, prebuild, run:ios, run:android ([#3674](https://github.com/expo/expo-cli/issues/3674))
- [cli][run] Cancel run commands better ([#3636](https://github.com/expo/expo-cli/issues/3636))
- [cli][xdl] Upgrade hapi/joi to joi ([#3639](https://github.com/expo/expo-cli/issues/3639))
- [cli][xdl] remove types hapi joi dependency ([#3664](https://github.com/expo/expo-cli/issues/3664))
- [config-types] Update types ([#3657](https://github.com/expo/expo-cli/issues/3657))
- [config] Improve missing file errors ([#3662](https://github.com/expo/expo-cli/issues/3662))
- [dev-server] refactor middleware into other files ([#3666](https://github.com/expo/expo-cli/issues/3666))
- [json-file] Remove fs-extra from json-file ([#3649](https://github.com/expo/expo-cli/issues/3649))
- [metro-config] Upgrade react-native to 63 ([#3640](https://github.com/expo/expo-cli/issues/3640))

### 🐛 Bug fixes

- [cli] Added better default splash screen on iOS - fixes bug when splash empty ([#3671](https://github.com/expo/expo-cli/issues/3671))
- [cli][run][android] fix cannot connect metro in a pure managed app ([#3651](https://github.com/expo/expo-cli/issues/3651))
- [config-plugins] Fix addJavaImports broken for kotlin files ([#3668](https://github.com/expo/expo-cli/issues/3668))
- [config-plugins] Sort results for predictable rewrites ([#3609](https://github.com/expo/expo-cli/issues/3609))
- [dev-server] Remove old types, and upgrade dev server ([#3642](https://github.com/expo/expo-cli/issues/3642))
- [image-utils] Allow any size or resize mode for jimp ([#3644](https://github.com/expo/expo-cli/issues/3644))
- [uri-scheme] Handle empty entries when parsing URL types in iOS projects ([#3627](https://github.com/expo/expo-cli/issues/3627))

### 📦 Packages updated

- @expo/babel-preset-cli@0.2.21
- @expo/config-plugins@3.0.4
- @expo/config-types@42.0.0
- @expo/config@5.0.4
- @expo/dev-server@0.1.79
- @expo/dev-tools@0.13.109
- expo-cli@4.8.0
- expo-codemod@1.1.3
- expo-optimize@0.1.101
- @expo/image-utils@0.3.15
- @expo/json-file@8.2.31
- @expo/metro-config@0.1.79
- @expo/next-adapter@3.0.0
- @expo/osascript@2.0.29
- @expo/package-manager@0.0.44
- pod-install@0.1.24
- @expo/prebuild-config@2.0.4
- expo-pwa@0.0.89
- @expo/schemer@1.3.30
- uri-scheme@1.0.90
- @expo/webpack-config@0.13.0
- xdl@59.0.49

## [Wed, 23 Jun 2021 10:37:34 -0700](https://github.com/expo/expo-cli/commit/caa0173d89632764098ae313768ff9bb18d2fa40)

### 🛠 Breaking changes

- [splash-screen] Extend default theme ([#3558](https://github.com/expo/expo-cli/issues/3558))
- [config-plugins] Make the status bar translucent by default ([#3578](https://github.com/expo/expo-cli/issues/3578))
- [prebuild-config] Created android splash plugin ([#3576](https://github.com/expo/expo-cli/issues/3576))

### 🎉 New features

- [run] prompt for scheme ([#3587](https://github.com/expo/expo-cli/issues/3587))
- [cli] Lazy load heavy modules to improve startup time ([#3598](https://github.com/expo/expo-cli/issues/3598))
- [cli] Import Command as type to reduce bundle size ([#3597](https://github.com/expo/expo-cli/issues/3597))

### 📦 Packages updated

- @expo/config-plugins@3.0.0
- @expo/config@5.0.0
- @expo/dev-server@0.1.75
- @expo/dev-tools@0.13.105
- expo-cli@4.7.0
- expo-optimize@0.1.97
- @expo/metro-config@0.1.75
- @expo/next-adapter@2.1.80
- @expo/prebuild-config@2.0.0
- expo-pwa@0.0.85
- uri-scheme@1.0.86
- @expo/webpack-config@0.12.79
- xdl@59.0.45

## [Mon, 21 Jun 2021 16:24:32 -0700](https://github.com/expo/expo-cli/commit/86ff226740af46ad04f8953114f9f2b1e1c9741a)

### 🎉 New features

- [config-plugins] add config request headers to Updates Config Enum and ExpoPlist Type ([#3571](https://github.com/expo/expo-cli/pull/3571))([##3577](https://github.com/expo/expo-cli/pull/3577))
- [metro] Created a custom metro babel transformer ([#3282](https://github.com/expo/expo-cli/issues/3282))
- [config-plugins] Default version number to 1.0.0 ([#3582](https://github.com/expo/expo-cli/issues/3582))
- [config-plugins] add EXUpdatesRequestHeaders to ExpoPlist type ([#3577](https://github.com/expo/expo-cli/issues/3577))
- [run:ios] Improve multi-target support by signing all targets at once ([#3583](https://github.com/expo/expo-cli/issues/3583))
- [config-plugins] add config request headers enum ([#3571](https://github.com/expo/expo-cli/issues/3571))
- [config-plugins] Remove permission side effects ([#3565](https://github.com/expo/expo-cli/issues/3565))

### 🧹 Chores

- [expo-cli][export] Prevent testing against bundle hashes ([#3580](https://github.com/expo/expo-cli/issues/3580))
- [cli] Add analytics to dev client commands ([#3521](https://github.com/expo/expo-cli/issues/3521))

### 🐛 Bug fixes

- [cli] Remove expo upload:ios cmd copy ([#3593](https://github.com/expo/expo-cli/issues/3593))
- [cli] Add workaround for glob library ([#3585](https://github.com/expo/expo-cli/issues/3585))

### 📦 Packages updated

- @expo/config-plugins@2.0.4
- @expo/config@4.0.4
- @expo/dev-server@0.1.74
- @expo/dev-tools@0.13.104
- expo-cli@4.6.0
- expo-optimize@0.1.96
- @expo/metro-config@0.1.74
- @expo/next-adapter@2.1.79
- @expo/prebuild-config@1.0.5
- expo-pwa@0.0.84
- uri-scheme@1.0.85
- @expo/webpack-config@0.12.78
- xdl@59.0.44

## [Fri, 11 Jun 2021 18:33:29 -0700](https://github.com/expo/expo-cli/commit/d53eadc503c6ff895902a7627ff9326ec61776de)

### 🛠 Breaking changes

- [cli] Remove bare typescript template ([#3562](https://github.com/expo/expo-cli/issues/3562))

### 🎉 New features

- [cli] Add support for Android dev client on managed projects ([#3561](https://github.com/expo/expo-cli/issues/3561))
- [cli] Allow `expo start --dev-client` in managed projects ([#3523](https://github.com/expo/expo-cli/issues/3523))
- [cli] Allow auto plugin adding on install for any version ([#3557](https://github.com/expo/expo-cli/issues/3557))
- [cli] Enhance Hermes support for expo export and publish ([#3536](https://github.com/expo/expo-cli/issues/3536))
- [cli] Use the default scheme to launch managed dev client apps ([#3569](https://github.com/expo/expo-cli/issues/3569))
- [config-plugins] Support android.jsEngine in app.json ([#3530](https://github.com/expo/expo-cli/issues/3530))
- [config-plugins] add styles and colors mods ([#3539](https://github.com/expo/expo-cli/issues/3539))

### 🧹 Chores

- [cli] Add /projects to website build url ([#3542](https://github.com/expo/expo-cli/issues/3542))
- [cli] Bump expo/xcpretty ([#3538](https://github.com/expo/expo-cli/issues/3538))
- [config-plugins] Refactor debug contents on android ([#3566](https://github.com/expo/expo-cli/issues/3566))
- [config-plugins] Removed default push notifications entitlement ([#3497](https://github.com/expo/expo-cli/issues/3497))
- [config] ios splash screen plugin ([#2706](https://github.com/expo/expo-cli/issues/2706))
- [contributing] Improve for newer developers ([#3224](https://github.com/expo/expo-cli/issues/3224))
- [prebuild-config] Add prebuild-config to CI ([#3564](https://github.com/expo/expo-cli/issues/3564))
- [prebuild-config] Added expo-cellular to the list of default plugins ([#3550](https://github.com/expo/expo-cli/issues/3550))
- [prebuild-config] Migrate expo-ads-admob plugin to prebuild-config ([#3520](https://github.com/expo/expo-cli/issues/3520))
- Remove nullthrows ([#3546](https://github.com/expo/expo-cli/issues/3546))
- Update naming to reflect best practices ([#3544](https://github.com/expo/expo-cli/issues/3544))
- Fix a typo in Manifest.ts ([#3541](https://github.com/expo/expo-cli/issues/3541))
- Remove unused transformer ([#3535](https://github.com/expo/expo-cli/issues/3535))
- Silence duplicate file warnings ([#3537](https://github.com/expo/expo-cli/issues/3537))

### 🐛 Bug fixes

- [config-plugins] Add support for legacy android icons ([#3567](https://github.com/expo/expo-cli/issues/3567))
- [config-plugins] Patch android status bar to match the color of the splash screen ([#3563](https://github.com/expo/expo-cli/issues/3563))
- [xdl] Prepend manifest handler to fix bug loading app when index.html in project root ([#3532](https://github.com/expo/expo-cli/issues/3532))
- [xdl] Update watchman version check to allow new format ([#3553](https://github.com/expo/expo-cli/issues/3553))
- Fix "Exception with debug remote enabled" ([#3545](https://github.com/expo/expo-cli/issues/3545))

### 📦 Packages updated

- @expo/config-plugins@2.0.3
- @expo/config@4.0.3
- @expo/dev-server@0.1.73
- @expo/dev-tools@0.13.103
- expo-cli@4.6.0-alpha.0
- expo-optimize@0.1.95
- @expo/metro-config@0.1.73
- @expo/next-adapter@2.1.78
- @expo/prebuild-config@1.0.4
- expo-pwa@0.0.83
- uri-scheme@1.0.84
- @expo/webpack-config@0.12.77
- xdl@59.0.43

## [Tue, 1 Jun 2021 13:02:23 +0200](https://github.com/expo/expo-cli/commit/6cd679038b3474954c8018f539432ff62b2ff72f)

### 🐛 Bug fixes

- [config-plugins] fix finding first native target ([#3533](https://github.com/expo/expo-cli/issues/3533))

### 📦 Packages updated

- @expo/config-plugins@2.0.2
- @expo/config@4.0.2
- @expo/dev-server@0.1.72
- @expo/dev-tools@0.13.102
- expo-cli@4.5.2
- expo-optimize@0.1.94
- @expo/metro-config@0.1.72
- @expo/next-adapter@2.1.77
- @expo/prebuild-config@1.0.3
- expo-pwa@0.0.82
- uri-scheme@1.0.83
- @expo/webpack-config@0.12.76
- xdl@59.0.42

## [Mon, 31 May 2021 15:50:35 -0700](https://github.com/expo/expo-cli/commit/d5cc32c7d0c2ecc960c597ac6ce52de5da12dbee)

### 🛠 Breaking changes

### 🎉 New features

- [expo-cli][dev-server] Export hbc as bundle output if js runtime is hermes ([#3522](https://github.com/expo/expo-cli/issues/3522))
- [dev-server] Add /inspector to for querying or opening js inspector ([#3495](https://github.com/expo/expo-cli/issues/3495))
- [xdl][cli] Adds general expo cli events to unified analytics ([#3519](https://github.com/expo/expo-cli/issues/3519))

### 🧹 Chores

- [expo-cli] Update e2e snapshot

### 🐛 Bug fixes

- [prebuild] Fix object application in iOS base mods ([#3531](https://github.com/expo/expo-cli/issues/3531))

### 📦 Packages updated

- @expo/config-plugins@2.0.1
- @expo/config@4.0.1
- @expo/dev-server@0.1.71
- @expo/dev-tools@0.13.101
- expo-cli@4.5.1
- expo-optimize@0.1.93
- @expo/metro-config@0.1.71
- @expo/next-adapter@2.1.76
- @expo/prebuild-config@1.0.2
- expo-pwa@0.0.81
- uri-scheme@1.0.82
- @expo/webpack-config@0.12.75
- xdl@59.0.41

### 🐛 Bug fixes

## [Wed, 26 May 2021 12:38:22 -0700](https://github.com/expo/expo-cli/commit/315dc74ad3f1c7da5f8beeb804148a5fb8f4bef2)

### 🛠 Breaking changes

### 🎉 New features

- [config-plugins][prebuild-config] Refactor config plugins ([#3514](https://github.com/expo/expo-cli/issues/3514))
- [cli] Show run commands in help ([#3515](https://github.com/expo/expo-cli/issues/3515))

### 🧹 Chores

- [introspect] Add pipe sanitization ([#3517](https://github.com/expo/expo-cli/issues/3517))
- [cli] Only set global git user name on CI

### 📦 Packages updated

- @expo/config-plugins@2.0.0
- @expo/config@4.0.0
- @expo/dev-server@0.1.70
- @expo/dev-tools@0.13.100
- expo-cli@4.5.0
- expo-optimize@0.1.92
- @expo/metro-config@0.1.70
- @expo/next-adapter@2.1.75
- @expo/prebuild-config@1.0.1
- expo-pwa@0.0.80
- uri-scheme@1.0.81
- @expo/webpack-config@0.12.74
- xdl@59.0.40
- @expo/config-types@41.0.0

## [Tue, 25 May 2021 14:15:46 +0200](https://github.com/expo/expo-cli/commit/a90d37dee759078511321fe719c83e45c80dc68c)

### 🛠 Breaking changes

### 🎉 New features

- [config-plugins] make bundle identifier getter aware of multiple targets ([#3483](https://github.com/expo/expo-cli/issues/3483))
- [config plugins] added provider validation ([#3506](https://github.com/expo/expo-cli/issues/3506))
- [expo cli] Enable socket controls in dev-client ([#3502](https://github.com/expo/expo-cli/issues/3502))

### 🧹 Chores

- Delete CustomInfoPlistEntries
- Rename strict to assertMissingModProviders ([#3511](https://github.com/expo/expo-cli/issues/3511))
- Improve legacy plugin creation ([#3512](https://github.com/expo/expo-cli/issues/3512))
- Remove unused slugify ([#3499](https://github.com/expo/expo-cli/issues/3499))
- Use workflow/customizing

### 🐛 Bug fixes

- Prevent resetting entitlements ([#3500](https://github.com/expo/expo-cli/issues/3500))
- Use a better default app id ([#3504](https://github.com/expo/expo-cli/issues/3504))

### 📦 Packages updated

- @expo/config-plugins@1.0.33
- @expo/config@3.3.43
- @expo/dev-server@0.1.69
- @expo/dev-tools@0.13.99
- expo-cli@4.4.9
- expo-optimize@0.1.91
- @expo/metro-config@0.1.69
- @expo/next-adapter@2.1.74
- expo-pwa@0.0.79
- uri-scheme@1.0.80
- @expo/webpack-config@0.12.73
- xdl@59.0.39

## [Thu, 20 May 2021 09:29:50 -0700](https://github.com/expo/expo-cli/commit/a4d6a8389aca6861758af093c096a640d814c9fb)

### 🛠 Breaking changes

### 🎉 New features

- [config plugins] added prebuild introspection config ([#3479](https://github.com/expo/expo-cli/issues/3479))
- Add `originalFullName` to the public config ([#3494](https://github.com/expo/expo-cli/issues/3494))

### 🧹 Chores

### 🐛 Bug fixes

- [cli] Update export snapshots
- Fix CHANGELOG to properly reflect breaking change
- [cli] Fix version check for Node 16
- Bump utils to support apple server errors ([#3496](https://github.com/expo/expo-cli/issues/3496))
- [e2e] fix expo export e2e test ([#3492](https://github.com/expo/expo-cli/issues/3492))

### 📦 Packages updated

- @expo/config-plugins@1.0.32
- @expo/config@3.3.42
- @expo/dev-server@0.1.68
- @expo/dev-tools@0.13.98
- expo-cli@4.4.8
- expo-optimize@0.1.90
- @expo/metro-config@0.1.68
- @expo/next-adapter@2.1.73
- expo-pwa@0.0.78
- uri-scheme@1.0.79
- @expo/webpack-config@0.12.72
- xdl@59.0.38

## [Fri, 14 May 2021 14:16:05 -0700](https://github.com/expo/expo-cli/commit/0e2b0e5dd8d3c0eefa9e18ab32cd98b87d789a01)

### 🛠 Breaking changes

### 🎉 New features

- [config-plugins] detect default build configuration for scheme ([#3474](https://github.com/expo/expo-cli/issues/3474))
- [config-plugins] support PKCS keystores for android builds ([#3472](https://github.com/expo/expo-cli/issues/3472))

### 🧹 Chores

- [cli] Stop running `adb shell monkey` when opening apps other than Expo Go ([#3487](https://github.com/expo/expo-cli/issues/3487))
- [config-plugins] Add noop Swift file to fix builds with Swift deps ([#3488](https://github.com/expo/expo-cli/issues/3488))
- Update to @expo/configure-splash-screen@0.4.0
- Update tsconfig to support node 12 ([#3489](https://github.com/expo/expo-cli/issues/3489))
- Add additional hermes resolution ([#3486](https://github.com/expo/expo-cli/issues/3486))
- disable wiping the console in tsc watch mode ([#3481](https://github.com/expo/expo-cli/issues/3481))

### 🐛 Bug fixes

- [cli] fix expo export so it finds the correct projectDir ([#3485](https://github.com/expo/expo-cli/issues/3485))
- [xdl] Limit manifest serving to a few URLs ([#3491](https://github.com/expo/expo-cli/issues/3491))
- [config] fix return typing of modifyConfigAsync ([#3482](https://github.com/expo/expo-cli/issues/3482))

### 📦 Packages updated

- @expo/config-plugins@1.0.31
- @expo/config@3.3.41
- @expo/dev-server@0.1.67
- @expo/dev-tools@0.13.97
- expo-cli@4.4.7
- expo-codemod@1.1.2
- expo-optimize@0.1.89
- @expo/image-utils@0.3.14
- @expo/json-file@8.2.30
- @expo/metro-config@0.1.67
- @expo/next-adapter@2.1.72
- @expo/osascript@2.0.28
- @expo/package-manager@0.0.43
- @expo/pkcs12@0.0.5
- @expo/plist@0.0.13
- pod-install@0.1.23
- expo-pwa@0.0.77
- @expo/schemer@1.3.29
- uri-scheme@1.0.78
- @expo/webpack-config@0.12.71
- xdl@59.0.37

## [Tue, 11 May 2021 14:19:49 -0700](https://github.com/expo/expo-cli/commit/79e6091d479a1ab7abd7dc07c61bfa37beee6680)

### 🧹 Chores

- [cli] Improve unlikely error message

### 🐛 Bug fixes

- [cli] Add missing nullthrows package

### 📦 Packages updated

- expo-cli@4.4.6

## [Tue, 11 May 2021 14:01:05 -0700](https://github.com/expo/expo-cli/commit/f8cbaef2ab4708ada6159e9eee65bfa3cb55cea0)

### 🧹 Chores

- [cli] Update supported Node versions validation
- [workspace] update TypeScript to latest release ([#3454](https://github.com/expo/expo-cli/issues/3454))

### 🐛 Bug fixes

- [config-plugins] ignore case when reading scheme ([#3465](https://github.com/expo/expo-cli/issues/3465))
- [cli] Remove URL mismatch warning ([#3467](https://github.com/expo/expo-cli/issues/3467))

### 📦 Packages updated

- @expo/config-plugins@1.0.30
- @expo/config@3.3.40
- @expo/dev-server@0.1.66
- @expo/dev-tools@0.13.96
- expo-cli@4.4.5
- expo-optimize@0.1.88
- @expo/metro-config@0.1.66
- @expo/next-adapter@2.1.71
- expo-pwa@0.0.76
- uri-scheme@1.0.77
- @expo/webpack-config@0.12.70
- xdl@59.0.36

## [Thu, 6 May 2021 19:37:12 -0700](https://github.com/expo/expo-cli/commit/f7dfc87744de00e98fdb301b4814e7fca61a1465)

### 🛠 Breaking changes

### 🎉 New features

- [cli] use bundledNativeModules.json from api ([#3444](https://github.com/expo/expo-cli/issues/3444))
- [cli] Added expo-dev-client to auto plugins ([#3436](https://github.com/expo/expo-cli/issues/3436))
- [cli] "expo is not installed" error ([#3425](https://github.com/expo/expo-cli/issues/3425))
- [install] add config plugins automatically ([#3437](https://github.com/expo/expo-cli/issues/3437))
- [run] add --no-bundler option ([#3460](https://github.com/expo/expo-cli/issues/3460))
- [prebuild] Added template prop ([#3439](https://github.com/expo/expo-cli/issues/3439))
- [run] output logs and clear on pod folder ([#3457](https://github.com/expo/expo-cli/issues/3457))
- [CI] add tests on Windows ([#3428](https://github.com/expo/expo-cli/issues/3428))
- [workspace] deduplicate yarn lock in `postinstall` ([#3418](https://github.com/expo/expo-cli/issues/3418))
- [cli] validate dependencies also on `doctor` run ([#3416](https://github.com/expo/expo-cli/issues/3416))
- Deep link into dev menu when it's installed ([#3405](https://github.com/expo/expo-cli/issues/3405))
- Improve errors when a package doesn't have a valid plugin ([#3421](https://github.com/expo/expo-cli/issues/3421))
- Added a flag to skip git status check ([#3401](https://github.com/expo/expo-cli/issues/3401))
- Add port selection to start --dev-client ([#3409](https://github.com/expo/expo-cli/issues/3409))

### 🧹 Chores

- Pad titles in log formatter and add duration ([#3466](https://github.com/expo/expo-cli/issues/3466))
- [cli] remove dead code ([#3455](https://github.com/expo/expo-cli/issues/3455))
- [electron] migrate to new repo ([#3446](https://github.com/expo/expo-cli/issues/3446))
- [configure-splash-screen]: remove core-js dependency ([#3422](https://github.com/expo/expo-cli/issues/3422))
- [configure-splash-screen] remove deep-equal dependency ([#3417](https://github.com/expo/expo-cli/issues/3417))
- [workspace] update ESLint and Prettier ([#3427](https://github.com/expo/expo-cli/issues/3427))
- [cli][xdl] return correct project page url after expo publish ([#3398](https://github.com/expo/expo-cli/issues/3398))
- Expand Info.plist type ([#3442](https://github.com/expo/expo-cli/issues/3442))
- bump minimum Node target to 12 ([#3434](https://github.com/expo/expo-cli/issues/3434))
- Delete `publishSourceMapPath` ([#3430](https://github.com/expo/expo-cli/issues/3430))
- Improve ios start up times ([#3413](https://github.com/expo/expo-cli/issues/3413))
- Improve cocoapods error messages ([#3411](https://github.com/expo/expo-cli/issues/3411))

### 🐛 Bug fixes

- Fix bundle identifier validation ([#3443](https://github.com/expo/expo-cli/issues/3443))
- Fix running dev client from the terminal UI using wrong bundle identifier ([#3407](https://github.com/expo/expo-cli/issues/3407))

### 📦 Packages updated

- @expo/config-plugins@1.0.29
- @expo/config@3.3.39
- @expo/dev-server@0.1.65
- @expo/dev-tools@0.13.95
- expo-cli@4.4.4
- expo-optimize@0.1.87
- @expo/metro-config@0.1.65
- @expo/next-adapter@2.1.70
- @expo/osascript@2.0.27
- @expo/package-manager@0.0.42
- pod-install@0.1.22
- expo-pwa@0.0.75
- uri-scheme@1.0.76
- @expo/webpack-config@0.12.69
- xdl@59.0.35

## [Tue, 20 Apr 2021 19:53:53 -0700](https://github.com/expo/expo-cli/commit/af417362f24d74af76ceb4ff82699c16d17025d4)

### 🛠 Breaking changes

### 🎉 New features

- Enable socket controls in run:ios and run:android ([#3403](https://github.com/expo/expo-cli/issues/3403))

### 🧹 Chores

- Remove readConfigJsonAsync shim ([#3402](https://github.com/expo/expo-cli/issues/3402))

### 🐛 Bug fixes

- [config-plugins] Make user interface style default to light if not specified ([#3404](https://github.com/expo/expo-cli/issues/3404))

### 📦 Packages updated

- @expo/config-plugins@1.0.28
- @expo/config@3.3.38
- @expo/dev-server@0.1.64
- @expo/dev-tools@0.13.94
- @expo/electron-adapter@0.0.55
- expo-cli@4.4.3
- expo-optimize@0.1.86
- @expo/metro-config@0.1.64
- @expo/next-adapter@2.1.69
- expo-pwa@0.0.74
- uri-scheme@1.0.75
- @expo/webpack-config@0.12.68
- xdl@59.0.34

## [Mon, 19 Apr 2021 17:00:03 -0700](https://github.com/expo/expo-cli/commit/50562c70e9cda584465b01c4520ac82d29a4738f)

### 🛠 Breaking changes

- Force overwriting by default in export, remove `--force` flag ([#3395](https://github.com/expo/expo-cli/issues/3395))

### 🎉 New features

- [config-plugins] feat: enable splash screen plugin for any SDK greater than 38 ([#3397](https://github.com/expo/expo-cli/issues/3397))
- print bundle sizes in export ([#3393](https://github.com/expo/expo-cli/issues/3393))

### 🧹 Chores

- improve cocoapods manager ([#3399](https://github.com/expo/expo-cli/issues/3399))
- [xdl][expo-cli] Adds action event to unified project ([#3372](https://github.com/expo/expo-cli/issues/3372))
- Add known packages to improve tracing ([#3392](https://github.com/expo/expo-cli/issues/3392))
- [metro-config] Skip babel runtime helpers ([#3391](https://github.com/expo/expo-cli/issues/3391))
- remove node 10 support and assert wrapper ([#3356](https://github.com/expo/expo-cli/issues/3356))

### 📦 Packages updated

- @expo/babel-preset-cli@0.2.20
- @expo/config-plugins@1.0.27
- @expo/config@3.3.37
- @expo/dev-server@0.1.63
- @expo/dev-tools@0.13.93
- @expo/electron-adapter@0.0.54
- expo-cli@4.4.2
- expo-codemod@1.1.1
- expo-optimize@0.1.85
- @expo/image-utils@0.3.13
- @expo/json-file@8.2.29
- @expo/metro-config@0.1.63
- @expo/next-adapter@2.1.68
- @expo/osascript@2.0.26
- @expo/package-manager@0.0.41
- pod-install@0.1.21
- expo-pwa@0.0.73
- @expo/schemer@1.3.28
- uri-scheme@1.0.74
- @expo/webpack-config@0.12.67
- xdl@59.0.33

## [Wed, 14 Apr 2021 12:36:03 -0700](https://github.com/expo/expo-cli/commit/30b4a040a81de0c73103e51ae38bbf4be8a58898)

### 🧹 Chores

- Update schema cache for SDK 41. Get a cool matching version: expo-cli@4.4.1 for SDK 41.

### 📦 Packages updated

- @expo/dev-tools@0.13.92
- expo-cli@4.4.1
- xdl@59.0.32

## [Wed, 14 Apr 2021 11:54:49 -0700](https://github.com/expo/expo-cli/commit/6bf320b102933730a9611011e46aac419736396c)

### 🛠 Breaking changes

### 🎉 New features

- [cli] Handle async storage package rename in upgrade command ([#3386](https://github.com/expo/expo-cli/issues/3386))

### 🧹 Chores

- Update test.yml to test against Node 12 and 14 ([#3388](https://github.com/expo/expo-cli/issues/3388))
- [config-plugins] Replace docs in README with link to Expo docs ([#3384](https://github.com/expo/expo-cli/issues/3384))
- [cli] Add deprecation message to --config flag ([#3382](https://github.com/expo/expo-cli/issues/3382))
- [dev-tools] flip `noEmit` flag to preserve server build ([#3379](https://github.com/expo/expo-cli/issues/3379))

### 🐛 Bug fixes

- Support building apps with escaped names ([#3383](https://github.com/expo/expo-cli/issues/3383))
- [codemod] Removed version gate ([#3390](https://github.com/expo/expo-cli/issues/3390))

### 📦 Packages updated

- @expo/config-plugins@1.0.26
- @expo/config@3.3.36
- @expo/dev-server@0.1.62
- @expo/dev-tools@0.13.91
- @expo/electron-adapter@0.0.53
- expo-cli@4.4.0
- expo-codemod@1.1.0
- expo-optimize@0.1.84
- @expo/metro-config@0.1.62
- @expo/next-adapter@2.1.67
- @expo/package-manager@0.0.40
- pod-install@0.1.20
- expo-pwa@0.0.72
- uri-scheme@1.0.73
- @expo/webpack-config@0.12.66
- xdl@59.0.31

## [Fri, 9 Apr 2021 15:05:32 -0700](https://github.com/expo/expo-cli/commit/31ce5bb9a78be83ee46a98a72d41652c05aa374c)

### 🎉 New features

- Added `currentFullName` to the public config ([#3376](https://github.com/expo/expo-cli/issues/3376))
- Added getUserProjectIdAsync method ([#3359](https://github.com/expo/expo-cli/issues/3359))
- Profile android build time ([#3348](https://github.com/expo/expo-cli/issues/3348))

### 🧹 Chores

- Simplify Config module ([#3373](https://github.com/expo/expo-cli/issues/3373))
- Clean up logging messages ([#3357](https://github.com/expo/expo-cli/issues/3357))
- Delete Api module ([#3360](https://github.com/expo/expo-cli/issues/3360))
- Improve no xcode warnings ([#3363](https://github.com/expo/expo-cli/issues/3363))
- Improve bundle identifier regex ([#3355](https://github.com/expo/expo-cli/issues/3355))
- Improved ios package logging ([#3353](https://github.com/expo/expo-cli/issues/3353))
- Remove deprecated property "xde" from the manifest ([#3366](https://github.com/expo/expo-cli/issues/3366))
- Remove Config.offline ([#3374](https://github.com/expo/expo-cli/issues/3374))
- Remove Config.helpUrl, use learnMore ([#3364](https://github.com/expo/expo-cli/issues/3364))
- Remove unused ncp ([#3367](https://github.com/expo/expo-cli/issues/3367))
- Remove unused TerminalLink.fallbackToUrl from XDL ([#3368](https://github.com/expo/expo-cli/issues/3368))
- Move dev dep ([#3362](https://github.com/expo/expo-cli/issues/3362))
- [config-plugins] Throw better error message when target does not exists ([#3350](https://github.com/expo/expo-cli/issues/3350))
- [dev-client] Allow running projects without app.json ([#3371](https://github.com/expo/expo-cli/issues/3371))
- [next-adapter] update RNW peer, remove deprecated types ([#3377](https://github.com/expo/expo-cli/issues/3377))
- [xdl] Remove unused xde spawn script ([#3365](https://github.com/expo/expo-cli/issues/3365))

### 🐛 Bug fixes

- [expo-cli] Fix missing/extraneous dependencies
- [xdl] Fix missing/extraneous dependencies ([#3369](https://github.com/expo/expo-cli/issues/3369))
- Fix prompt bug when opening on iOS ([#3358](https://github.com/expo/expo-cli/issues/3358))
- Fix product name getter ([#3354](https://github.com/expo/expo-cli/issues/3354))

### 📦 Packages updated

- @expo/config-plugins@1.0.25
- @expo/config@3.3.35
- @expo/dev-server@0.1.61
- @expo/dev-tools@0.13.90
- @expo/electron-adapter@0.0.52
- expo-cli@4.3.5
- expo-optimize@0.1.83
- @expo/metro-config@0.1.61
- @expo/next-adapter@2.1.66
- expo-pwa@0.0.71
- uri-scheme@1.0.72
- @expo/webpack-config@0.12.65
- xdl@59.0.30

## [Thu, 1 Apr 2021 14:25:44 -0700](https://github.com/expo/expo-cli/commit/4bbb35de0096a6369d38e5369c1120cead620ae4)

### 🎉 New features

- Activate android emulator window ([#3345](https://github.com/expo/expo-cli/issues/3345))
- Created unversioned react-native-maps plugin ([#3343](https://github.com/expo/expo-cli/issues/3343))
- Add migration from @react-native-community/async-storage ([#3342](https://github.com/expo/expo-cli/issues/3342))
- Run built APK on device ([#3338](https://github.com/expo/expo-cli/issues/3338))
- Added expo config command to expo-cli ([#3323](https://github.com/expo/expo-cli/issues/3323))
- Added device selection prop to run:android ([#3331](https://github.com/expo/expo-cli/issues/3331))
- Pipe ora output to stdout in non-interactive mode ([#3329](https://github.com/expo/expo-cli/issues/3329))
- Sort code signing identities by last selected ([#3321](https://github.com/expo/expo-cli/issues/3321))
- Allow single platform for dev client schemes ([#3309](https://github.com/expo/expo-cli/issues/3309))
- Improve single platform dev client ([#3337](https://github.com/expo/expo-cli/issues/3337))
- Improve running in a project with single platform ([#3336](https://github.com/expo/expo-cli/issues/3336))
- Code signing xcode projects automatically in development ([#3317](https://github.com/expo/expo-cli/issues/3317))
- Auto install ios-deploy ([#3308](https://github.com/expo/expo-cli/issues/3308))
- Improved device deployment ([#3306](https://github.com/expo/expo-cli/issues/3306))
- Created ios command ([#3303](https://github.com/expo/expo-cli/issues/3303))

### 🧹 Chores

- Remove gulp and build with tsc from xdl ([#3334](https://github.com/expo/expo-cli/issues/3334))
- Create cocoapods dep check file sooner ([#3346](https://github.com/expo/expo-cli/issues/3346))
- Improve bplist parsing ([#3330](https://github.com/expo/expo-cli/issues/3330))
- Updated metro config warning to reflect SDK 41 by default. ([#3325](https://github.com/expo/expo-cli/issues/3325))
- Added spinner for device searching ([#3328](https://github.com/expo/expo-cli/issues/3328))
- Improve IOSDeploy logging ([#3326](https://github.com/expo/expo-cli/issues/3326))
- Remove -showBuildSettings usages ([#3318](https://github.com/expo/expo-cli/issues/3318))
- Update xmldom and xcode dependencies ([#3314](https://github.com/expo/expo-cli/issues/3314))
- Remove windows extraction binary ([#3165](https://github.com/expo/expo-cli/issues/3165))

### 🐛 Bug fixes

- Prevent removing existing schemes from AndroidManifest.xml ([#3324](https://github.com/expo/expo-cli/issues/3324))
- Fix a bug where an IntentFilter could be overridden by the Scheme plugin. ([#3319](https://github.com/expo/expo-cli/issues/3319))
- Fix broken debug spinner ([#3322](https://github.com/expo/expo-cli/issues/3322))

### 📦 Packages updated

- @expo/babel-preset-cli@0.2.19
- @expo/config-plugins@1.0.24
- @expo/config@3.3.34
- @expo/dev-server@0.1.60
- @expo/dev-tools@0.13.88
- @expo/electron-adapter@0.0.51
- expo-cli@4.3.3
- expo-codemod@1.0.31
- expo-optimize@0.1.82
- @expo/image-utils@0.3.12
- @expo/json-file@8.2.28
- @expo/metro-config@0.1.60
- @expo/next-adapter@2.1.65
- @expo/osascript@2.0.25
- @expo/package-manager@0.0.39
- @expo/plist@0.0.12
- pod-install@0.1.19
- expo-pwa@0.0.70
- @expo/schemer@1.3.27
- uri-scheme@1.0.71
- @expo/webpack-config@0.12.64
- xdl@59.0.28

## [Fri, 19 Mar 2021 10:26:48 -0700](https://github.com/expo/expo-cli/commit/c4b3c767269e6e5efd1abd9fa3b72b066eed2a00)

### 🐛 Bug fixes

- [cli] hide run:android
- [xdl] facebookReactNativeVersionToExpoVersionAsync: only map to released versions ([#3305](https://github.com/expo/expo-cli/issues/3305))
- [xdl] show uncaught exceptions ([#3302](https://github.com/expo/expo-cli/issues/3302))

### 📦 Packages updated

- @expo/config-plugins@1.0.23
- @expo/config@3.3.33
- @expo/dev-server@0.1.59
- @expo/dev-tools@0.13.87
- @expo/electron-adapter@0.0.50
- expo-cli@4.3.2
- expo-optimize@0.1.81
- @expo/metro-config@0.1.59
- @expo/next-adapter@2.1.64
- expo-pwa@0.0.69
- uri-scheme@1.0.70
- @expo/webpack-config@0.12.63
- xdl@59.0.27

## [Thu, 18 Mar 2021 12:11:59 -0700](https://github.com/expo/expo-cli/commit/10162d5800ed830d9bbce56973e8f063e1d69c7c)

### 🛠 Breaking changes

### 🎉 New features

- [cli] Added devClient option to mobile options ([#3301](https://github.com/expo/expo-cli/issues/3301))
- [cli] Added socket controls ([#3280](https://github.com/expo/expo-cli/issues/3280))
- [cli] skip update check when EAS_BUILD=1 ([#3290](https://github.com/expo/expo-cli/issues/3290))
- [config-plugins] Added withGradleProperties mod ([#3298](https://github.com/expo/expo-cli/issues/3298))
- [config-plugins] Created withSwiftBridgingHeader ([#3284](https://github.com/expo/expo-cli/issues/3284))
- [config-plugins] add expo-ads-facebook to list of auto plugins ([#3289](https://github.com/expo/expo-cli/issues/3289))
- [doctor] Re-enable checking reachability of exp.host domain ([#3285](https://github.com/expo/expo-cli/issues/3285))
- [eject] preserve expo dev client scripts ([#3300](https://github.com/expo/expo-cli/issues/3300))
- [expo-cli] skip updating dependencies in package.json in `expo prebuild` ([#3278](https://github.com/expo/expo-cli/issues/3278))
- [init] Change template project default branch from master to main ([#3297](https://github.com/expo/expo-cli/issues/3297))
- [logs] Improve errors thrown by invariant ([#3281](https://github.com/expo/expo-cli/issues/3281))
- [logs] Mute regenerator runtime and setimmediate stack traces ([#3294](https://github.com/expo/expo-cli/issues/3294))
- [prebuild] Added clean flag to prebuild ([#3295](https://github.com/expo/expo-cli/issues/3295))
- [run] Add a command to build and run on Android ([#3239](https://github.com/expo/expo-cli/issues/3239))
- [run] Added debug simctl logger ([#3293](https://github.com/expo/expo-cli/issues/3293))

### 🐛 Bug fixes

- Pause interactions after stopping ([#3286](https://github.com/expo/expo-cli/issues/3286))

### 🧹 Chores

- Move export code from xdl to expo-cli ([#3233](https://github.com/expo/expo-cli/issues/3233))
- Refactor projectDir -> projectRoot ([#3292](https://github.com/expo/expo-cli/issues/3292))
- Remove unused detach code from XDL and rename the package ([#3268](https://github.com/expo/expo-cli/issues/3268))
- updated getenv dependencies to 1.0.0 ([#3299](https://github.com/expo/expo-cli/issues/3299))

### 📦 Packages updated

- @expo/config-plugins@1.0.22
- @expo/config@3.3.32
- @expo/dev-server@0.1.58
- @expo/dev-tools@0.13.86
- @expo/electron-adapter@0.0.49
- expo-cli@4.3.1
- expo-optimize@0.1.80
- @expo/image-utils@0.3.11
- @expo/metro-config@0.1.58
- @expo/next-adapter@2.1.63
- expo-pwa@0.0.68
- uri-scheme@1.0.69
- @expo/webpack-config@0.12.62
- xdl@59.0.26

## [Tue, 9 Mar 2021 11:17:38 -0800](https://github.com/expo/expo-cli/commit/7f66dad2ed570e2d001ea47ed6aabebd16ec8bfe)

### 🛠 Breaking changes

- [cli] Delete e (send to) command from terminal ui ([#3274](https://github.com/expo/expo-cli/issues/3274))

### 🎉 New features

- [cli] Unify terminal stack trace logs ([#3275](https://github.com/expo/expo-cli/issues/3275))
- [cli] Collapse first frame if it's useless ([#3276](https://github.com/expo/expo-cli/issues/3276))
- [cli][xdl] Rename Expo client to Expo Go wherever it makes sense

### 🐛 Bug fixes

- [cli] Remove Slack link from README
- [config-plugins] eas build:configure fixes for Windows ([#3266](https://github.com/expo/expo-cli/issues/3266))
- [config-plugins] Add release channel key to updates modules
- [config-plugins] Support quote marks in target name in pbxproj ([#3264](https://github.com/expo/expo-cli/issues/3264))
- [metro-config] Use relative asset registry path ([#3273](https://github.com/expo/expo-cli/issues/3273))
- [xdl] Fix launching Android and iOS from terminal UI in unversioned apps

### 📦 Packages updated

- @expo/config-plugins@1.0.21
- @expo/config@3.3.31
- @expo/dev-server@0.1.57
- @expo/dev-tools@0.13.85
- @expo/electron-adapter@0.0.48
- expo-cli@4.3.0
- expo-optimize@0.1.79
- @expo/metro-config@0.1.57
- @expo/next-adapter@2.1.62
- expo-pwa@0.0.67
- uri-scheme@1.0.68
- @expo/webpack-config@0.12.61
- @expo/xdl@59.0.25

## [Wed, 24 Feb 2021 16:05:57 -0800](https://github.com/expo/expo-cli/commit/dd38f7d9c4d218ac6d408c748f2e2f6cde605b7a)

### 🛠 Breaking changes

### 🎉 New features

- [prebuild] Skip overwriting modules that are symlinked ([#3257](https://github.com/expo/expo-cli/issues/3257))
- [cli] Added method profiler helper function ([#3258](https://github.com/expo/expo-cli/issues/3258))
- [eject] Added prompt to clear malformed projects ([#3256](https://github.com/expo/expo-cli/issues/3256))

### 🐛 Bug fixes

- [cli] Fix double printing `?` command on web
- [cli] Use a more focused babel preset for app.config.js ([#3208](https://github.com/expo/expo-cli/issues/3208))
- [cli] Newline after full log output and skip newline before help output ([#3259](https://github.com/expo/expo-cli/issues/3259))
- [publish] silence workflow warning in 41 ([#3249](https://github.com/expo/expo-cli/issues/3249))
- [xdl] fix unhandled JS exception if no foregroundImage defined for adaptive icon ([#3229](https://github.com/expo/expo-cli/issues/3229))
- [xdl] Update node-forge ([#3252](https://github.com/expo/expo-cli/issues/3252))

### 📦 Packages updated

- @expo/config-plugins@1.0.20
- @expo/config@3.3.30
- @expo/dev-server@0.1.56
- @expo/dev-tools@0.13.84
- @expo/electron-adapter@0.0.47
- expo-cli@4.2.1
- expo-optimize@0.1.78
- @expo/metro-config@0.1.56
- @expo/next-adapter@2.1.61
- expo-pwa@0.0.66
- uri-scheme@1.0.67
- @expo/webpack-config@0.12.60
- @expo/xdl@59.0.24

## [Fri, 19 Feb 2021 11:46:06 -0800](https://github.com/expo/expo-cli/commit/3aff32603996f381482bc6c3239e6f70bf098b70)

### 🛠 Breaking changes

- [cli] redesign startup logs ([#3209](https://github.com/expo/expo-cli/issues/3209))
- [json-file] Remove undocumented support for multi-part keys in `getAsync` and `setAsync` ([#3019](https://github.com/expo/expo-cli/pulls/3019))
- [xdl] Remove Project methods `getLatestReleaseAsync`, `findReusableBuildAsync`, `getBuildStatusAsync`, `startBuildAsync` ([#3187](https://github.com/expo/expo-cli/pulls/3187))
- [xdl] Remove Project types `BuildCreatedResult`, `TurtleMode`, `BuildJobFields`, `BuildStatusResult` ([#3187](https://github.com/expo/expo-cli/pulls/3187))

### 🎉 New features

- [configure-splash-screen] Remove @react-native-community/cli-tools ([#3178](https://github.com/expo/expo-cli/issues/3178))
- [cli] deprecate .expo extension for start command ([#3216](https://github.com/expo/expo-cli/issues/3216))
- [cli] Improve server stopping ([#3210](https://github.com/expo/expo-cli/issues/3210))
- [cli] Combine stop methods ([#3237](https://github.com/expo/expo-cli/issues/3237))
- [cli] Persist dev tools preference ([#3207](https://github.com/expo/expo-cli/issues/3207))
- [cli] Added profiling ([#3217](https://github.com/expo/expo-cli/issues/3217))
- [cli] Added clear flag to expo export ([#3205](https://github.com/expo/expo-cli/issues/3205))
- [cli] Improve keytool errors when not installed ([#3190](https://github.com/expo/expo-cli/issues/3190))
- [xdl] Use devcert fork to reduce install size ([#3175](https://github.com/expo/expo-cli/issues/3175))
- [xdl] Add Dev Client simulator flow v0 for Android devices ([#3194](https://github.com/expo/expo-cli/issues/3194))
- [xdl] Allow dev client apps to be launched in the iOS simulator ([#3182](https://github.com/expo/expo-cli/issues/3182))

### 🐛 Bug fixes

- [cli][prebuild] Clean up debug error messages ([#3201](https://github.com/expo/expo-cli/issues/3201))
- [cli] Cancel upgrade command on ctrl+c within prompt ([#3188](https://github.com/expo/expo-cli/issues/3188))
- [config-plugins] fix detecting application target ([#3215](https://github.com/expo/expo-cli/issues/3215))
- [next-adapter]: Move @types/next to devDependencies ([#3238](https://github.com/expo/expo-cli/issues/3238))
- [xdl] refactor start command folder ([#3186](https://github.com/expo/expo-cli/issues/3186))
- [xdl] split up Project module ([#3164](https://github.com/expo/expo-cli/issues/3164))
- [webpack-config] Update web index.html to fix the screen height in the web when the statusBar is transparent ([#3199](https://github.com/expo/expo-cli/issues/3199))
- [webpack-config] Fixed support for disabling automatic manifest.json tag injection ([#3189](https://github.com/expo/expo-cli/issues/3189))

### 📦 Packages updated

- @expo/config-plugins@1.0.19
- @expo/config@3.3.29
- @expo/dev-server@0.1.55
- @expo/dev-tools@0.13.83
- @expo/electron-adapter@0.0.46
- expo-cli@4.2.0
- expo-optimize@0.1.77
- @expo/metro-config@0.1.55
- @expo/next-adapter@2.1.60
- expo-pwa@0.0.65
- uri-scheme@1.0.66
- @expo/webpack-config@0.12.59
- @expo/xdl@59.0.23

## [Mon, 1 Feb 2021 21:22:35 -0800](https://github.com/expo/expo-cli/commit/d7b35c0c8bca99d3a5ea6ea1599d1a3c254f3d40)

### 🛠 Breaking changes

- [cli] Drop `nodeModulesPath` support (only known use was in former Expo monorepo) ([#3141](https://github.com/expo/expo-cli/issues/3141))

### 🎉 New features

- [xdl] Automatically fall back to offline mode when manifest can't be signed. ([#3148](https://github.com/expo/expo-cli/pull/3148))

### 🐛 Bug fixes

- [cli] fix init visual regresion ([#3173](https://github.com/expo/expo-cli/issues/3173))
- [config-plugins] Rename `IOSConfig.BundleIdenitifer` to `IOSConfig.BundleIdentifier` ([#3161](https://github.com/expo/expo-cli/issues/3161))

### 📦 Packages updated

- @expo/config-plugins@1.0.18
- @expo/config@3.3.28
- @expo/dev-server@0.1.54
- @expo/dev-tools@0.13.82
- @expo/electron-adapter@0.0.45
- expo-cli@4.1.6
- expo-optimize@0.1.76
- @expo/json-file@8.2.27
- @expo/metro-config@0.1.54
- @expo/next-adapter@2.1.59
- @expo/package-manager@0.0.38
- pod-install@0.1.18
- expo-pwa@0.0.64
- @expo/schemer@1.3.26
- uri-scheme@1.0.65
- @expo/webpack-config@0.12.58
- @expo/xdl@59.0.22

## [Tue, 01 Feb 2021 08:55:22 -0800](https://github.com/expo/expo-cli/commit/51c6adb941b74df413834ab3ae3f2578e336d60d)

### 🛠 Breaking changes

### 🎉 New features

### 🐛 Bug fixes

- [xdl] Define max content and body lengths in Axios 0.21 ([#3162](https://github.com/expo/expo-cli/pull/3162))

### 📦 Packages updated

- @expo/dev-tools@0.13.81
- expo-cli@4.1.5
- @expo/xdl@59.0.21

## [Tue, 26 Jan 2021 18:21:34 -0800](https://github.com/expo/expo-cli/commit/ee77eaa57684c3ac496eae24b5e10b8acb6b6e32)

### 🛠 Breaking changes

### 🎉 New features

### 🐛 Bug fixes

- [xdl] Fix flicker when switching to tunnel connection due to null urlType

### 📦 Packages updated

- @expo/dev-tools@0.13.79
- expo-cli@4.1.3
- @expo/xdl@59.0.19

## [Tue, 26 Jan 2021 17:34:40 -0800](https://github.com/expo/expo-cli/commit/c9a57c31bc2309de5c8ddfa13986209c5dffcecf)

### 🛠 Breaking changes

### 🎉 New features

- [xdl] Use global ngrok for xdl ([#3123](https://github.com/expo/expo-cli/issues/3123))
- [configure-splash-screen] publish @expo/configure-splash-screen

### 🐛 Bug fixes

- [cli] prevent throwing duplicate warning ([#3130](https://github.com/expo/expo-cli/issues/3130))
- [cli] Auto-login when envvars are defined ([#3127](https://github.com/expo/expo-cli/issues/3127))
- [cli] Improve handling of no answer for customize:web ([#3128](https://github.com/expo/expo-cli/issues/3128))
- [xdl] Support Expo Go name in shellapp template ([#3125](https://github.com/expo/expo-cli/issues/3125))

### 📦 Packages updated

- @expo/config-plugins@1.0.17
- @expo/config@3.3.26
- @expo/dev-server@0.1.52
- @expo/dev-tools@0.13.78
- @expo/electron-adapter@0.0.43
- expo-cli@4.1.2
- expo-optimize@0.1.74
- @expo/metro-config@0.1.52
- @expo/next-adapter@2.1.57
- @expo/package-manager@0.0.36
- pod-install@0.1.16
- expo-pwa@0.0.62
- uri-scheme@1.0.63
- @expo/webpack-config@0.12.56
- @expo/xdl@59.0.18

## [Mon, 25 Jan 2021 11:50:33 -0800](https://github.com/expo/expo-cli/commit/ded0c2af2180d76dd9f420f00b92b5167ab52312)

### 🛠 Breaking changes

- [cli] Open signup page in browser instead of CLI-based registration
- [config] Only use wasm on web platforms ([#3100](https://github.com/expo/expo-cli/issues/3100))

### 🎉 New features

- [cli] Auto configure TypeScript ([#3096](https://github.com/expo/expo-cli/issues/3096))
- [cli] Use the versions endpoint for TypeScript packages ([#3109](https://github.com/expo/expo-cli/issues/3109))
- [cli] Copy over EAS Apple API methods ([#3113](https://github.com/expo/expo-cli/issues/3113))
- [cli] add --experimental-bundle flag to 'export' command ([#3074](https://github.com/expo/expo-cli/issues/3074))
- [config-plugins] improve monorepo support - fix setting path to create-manifest-\* script ([#3103](https://github.com/expo/expo-cli/issues/3103))
- [config-plugins] export more types from config-plugins ([#3083](https://github.com/expo/expo-cli/issues/3083))
- [metro-config] Enable allowOptionalDependencies by default ([#3088](https://github.com/expo/expo-cli/issues/3088))
- [xdl] improve simulator errors ([#3104](https://github.com/expo/expo-cli/issues/3104))

### 🐛 Bug fixes

- [cli] Check for optional `devDependencies` ([#3121](https://github.com/expo/expo-cli/issues/3121))
- [cli] Validate project owner when publishing ([#3061](https://github.com/expo/expo-cli/issues/3061))
- [cli] Remove EAS Build related code ([#3079](https://github.com/expo/expo-cli/issues/3079))
- [cli] add option to assign created push key to current project ([#3098](https://github.com/expo/expo-cli/issues/3098))
- [cli] Only change react-native version when it's a fork ([#3097](https://github.com/expo/expo-cli/issues/3097))
- [cli] remove lottie extra step warning ([#3099](https://github.com/expo/expo-cli/issues/3099))
- [cli] improvement: Handle keychain save error ([#3067](https://github.com/expo/expo-cli/issues/3067))
- [config-plugins] Prevent adding duplicate Xcode references for files ([#3107](https://github.com/expo/expo-cli/issues/3107))
- [config-plugins] Fix app gradle versionName replacement after ejecting twice ([#3082](https://github.com/expo/expo-cli/issues/3082))
- [xdl] fix expo export --dump-sourcemap for sdk 40+ and bare projects ([#3095](https://github.com/expo/expo-cli/issues/3095))

### 📦 Packages updated

- @expo/config-plugins@1.0.15
- @expo/config@3.3.24
- @expo/dev-server@0.1.50
- @expo/dev-tools@0.13.76
- @expo/electron-adapter@0.0.41
- expo-cli@4.1.0
- expo-optimize@0.1.72
- @expo/metro-config@0.1.50
- @expo/next-adapter@2.1.55
- expo-pwa@0.0.60
- uri-scheme@1.0.61
- @expo/webpack-config@0.12.54
- @expo/xdl@59.0.16

## [Thu Jan 14 14:34:05 2021 +0100](https://github.com/expo/expo-cli/commit/e8dfcc425fa8128aeaf21fb8bbba6760dc196fcf)

### 🛠 Breaking changes

- [cli] Environment variables matching `EXPO_` or `REACT_NATIVE_` are no longer exposed publicly to the development-mode app or website ([#3063](https://github.com/expo/expo-cli/issues/3063))
- [cli] Remove EAS Build code, it now lives in `eas-cli` ([#3079](https://github.com/expo/expo-cli/pull/3079))

### 🎉 New features

- [config-plugins] ProvisioningProfile: allow setting provisioning profile for a particular target (not only for the first one)

### 📦 Packages updated

- @expo/config-plugins@1.0.14
- @expo/config@3.3.23
- @expo/dev-server@0.1.49
- @expo/dev-tools@0.13.75
- @expo/electron-adapter@0.0.40
- expo-cli@4.0.18
- expo-codemod@1.0.30
- expo-optimize@0.1.71
- @expo/image-utils@0.3.10
- @expo/metro-config@0.1.49
- @expo/next-adapter@2.1.54
- expo-pwa@0.0.59
- uri-scheme@1.0.60
- @expo/webpack-config@0.12.53
- @expo/xdl@59.0.15

## [Sun, 27 Dec 2020 13:14:17 -0800](https://github.com/expo/expo-cli/commit/a14f18284efda89a08910d5a753b1749897f54a2)

### 🛠 Breaking changes

- [cli] Mark expo upload:ios as unsupported ([#3030](https://github.com/expo/expo-cli/issues/3030))

### 📦 Packages updated

- expo-cli@4.0.17

## [Mon, 21 Dec 2020 18:18:20 -0800](https://github.com/expo/expo-cli/commit/62339b5fb7300569ca6cbb034251070bf8a63999)

### 🛠 Breaking changes

- [xdl] Update iOS deployment target in ejected Podfile (internal)

### 🎉 New features

- [xdl][dev-tools][cli] Update --dev-client for new requirements ([#2938](https://github.com/expo/expo-cli/issues/2938))

### 📦 Packages updated

- @expo/dev-server@0.1.48
- @expo/dev-tools@0.13.74
- kkexpo-cli@4.0.16
- @expo/metro-config@0.1.48
- @expo/xdl@59.0.14

## [Mon, 14 Dec 2020 20:47:39 -0800](https://github.com/expo/expo-cli/commit/ad6570659b8ad9fccdec8c79791b6f5d6578b824)

### 🐛 Bug fixes

- [configure-splash-screen][config-plugins] Bump @expo/configure-splash-screen
- [configure-splash-screen] Remove peer dependency
- [english] effect -> affect ([#3013](https://github.com/expo/expo-cli/issues/3013))

### 📦 Packages updated

- @expo/config-plugins@1.0.12
- @expo/dev-tools@0.13.72
- expo-cli@4.0.14
- uri-scheme@1.0.58
- @expo/xdl@59.0.12

## [Wed, 9 Dec 2020 17:12:12 -0800](https://github.com/expo/expo-cli/commit/cbbfa68a6eac9639b4217a9bcc0ca3ce30eb1378)

### 🐛 Bug fixes

- [cli][xdl] Clear versions cache when running expo upgrade, to be safe
- [config] fix mod serialization ([#3008](https://github.com/expo/expo-cli/issues/3008))
- [config-plugins] use env variable for debug when \_internal isn't defined ([#3011](https://github.com/expo/expo-cli/issues/3011))

### 📦 Packages updated

- @expo/config-plugins@1.0.11
- @expo/config@3.3.21
- @expo/dev-server@0.1.46
- @expo/dev-tools@0.13.71
- @expo/electron-adapter@0.0.38
- expo-cli@4.0.13
- expo-optimize@0.1.69
- @expo/metro-config@0.1.46
- @expo/next-adapter@2.1.52
- expo-pwa@0.0.57
- uri-scheme@1.0.57
- @expo/webpack-config@0.12.51
- @expo/xdl@59.0.11

## [Tue, 8 Dec 2020 18:21:57 -0800](https://github.com/expo/expo-cli/commit/a875d06d4ab529ff9b4e7fe570692a47bf46f1b6)

### 🎉 New features

- [cli] Add expo-random when upgrading to >= SDK 40 with expo-auth-session
- [cli] Add cmd.exe detection on windows & warn about it ([#2838](https://github.com/expo/expo-cli/issues/2838))
- [cli] Skip warning about expo-constants when ejecting in SDK 40 and greater ([#3006](https://github.com/expo/expo-cli/issues/3006))
- [xdl] Add robots as new supported user type ([#2440](https://github.com/expo/expo-cli/issues/2440))

### 📦 Packages updated

- @expo/dev-tools@0.13.70
- expo-cli@4.0.12
- @expo/xdl@59.0.10

## [Mon, 7 Dec 2020 22:27:44 -0800](https://github.com/expo/expo-cli/commit/3fb08fdff7a03fb49a1f2ddc6d968ceb14be9519)

### 🎉 New features

- [config-plugins] Added support for static plugins ([#2943](https://github.com/expo/expo-cli/issues/2943))
- [config-plugins] Support splash screen config on SDK 40 ([#3003](https://github.com/expo/expo-cli/issues/3003))
- [config-plugins] added method for adding frameworks ([#2997](https://github.com/expo/expo-cli/issues/2997))

### 🐛 Bug fixes

- [xdl] Check for client updates for the given sdk version by default
- [cli] fix windows post install message
- [cli] Use unified website route for all builds (no more /v2) ([#2995](https://github.com/expo/expo-cli/issues/2995))

### 📦 Packages updated

- @expo/config-plugins@1.0.10
- @expo/config@3.3.20
- @expo/dev-server@0.1.45
- @expo/dev-tools@0.13.69
- @expo/electron-adapter@0.0.37
- expo-cli@4.0.11
- expo-optimize@0.1.68
- @expo/metro-config@0.1.45
- @expo/next-adapter@2.1.51
- pod-install@0.1.14
- expo-pwa@0.0.56
- @expo/schemer@1.3.23
- uri-scheme@1.0.56
- @expo/webpack-config@0.12.50
- @expo/xdl@59.0.9

## [Fri, 4 Dec 2020 10:38:20 -0800](https://github.com/expo/expo-cli/commit/65cb9a64cfa4cc6fb89bdc2a432acd16c6043def)

### 🎉 New features

- [cli] Added ability to skip platforms when ejecting ([#2988](https://github.com/expo/expo-cli/issues/2988))
- [cli] Fallback to jest-expo@sdkVersion-beta when using beta sdk if not otherwise defined ([#2985](https://github.com/expo/expo-cli/issues/2985))
- [cli] Update supported Node version ranges
- [xdl] Install the client version for the given SDK by default when opening project ([#2986](https://github.com/expo/expo-cli/issues/2986))

### 📦 Packages updated

- @expo/config-plugins@1.0.7
- @expo/dev-tools@0.13.66
- expo-cli@4.0.8
- uri-scheme@1.0.53
- @expo/xdl@59.0.6

## [Tue, 1 Dec 2020 16:30:17 -0800](https://github.com/expo/expo-cli/commit/bc951645e2b7771ad2c2e81dbb50d1ffa7b22dc1)

### 🛠 Breaking changes

### 🎉 New features

### 🐛 Bug fixes

- [cli] Fix installing client for selected target SDK version in upgrade ([#2981](https://github.com/expo/expo-cli/issues/2981))

### 📦 Packages updated

- @expo/config-plugins@1.0.6
- expo-cli@4.0.7
- uri-scheme@1.0.52

## [Mon, 30 Nov 2020 15:41:46 -0800](https://github.com/expo/expo-cli/commit/d68bfc944016efa0c553109ffca3d3222b1a92ac)

### 🛠 Breaking changes

### 🎉 New features

- [config-plugins] Add withInternal plugin ([#2975](https://github.com/expo/expo-cli/issues/2975))
- [config-plugins] Created withRunOnce ([#2965](https://github.com/expo/expo-cli/issues/2965))
- [config-plugins] fix isPlistVersionConfigurationSynced condition ([#2974](https://github.com/expo/expo-cli/issues/2974))

### 🐛 Bug fixes

- [xdl][cli] Fix beta integration of init ([#2978](https://github.com/expo/expo-cli/issues/2978))

### 📦 Packages updated

- @expo/config-plugins@1.0.5
- @expo/config@3.3.18
- @expo/dev-server@0.1.43
- @expo/dev-tools@0.13.64
- @expo/electron-adapter@0.0.35
- expo-cli@4.0.5
- expo-optimize@0.1.66
- @expo/metro-config@0.1.43
- @expo/next-adapter@2.1.49
- expo-pwa@0.0.54
- uri-scheme@1.0.51
- @expo/webpack-config@0.12.48
- @expo/xdl@59.0.4

## [Sat, 28 Nov 2020 12:49:14 -0800](https://github.com/expo/expo-cli/commit/57ddd2cadfc85b663df7dbb23dc442b9d5803b7c)

### 🎉 New features

- [config] fill \_internal object ([#2968](https://github.com/expo/expo-cli/issues/2968))

### 🐛 Bug fixes

- [cli] Fix register command and some cleanup on messaging ([#2971](https://github.com/expo/expo-cli/issues/2971))

### 📦 Packages updated

- @expo/config-plugins@1.0.4
- @expo/config@3.3.17
- @expo/dev-server@0.1.42
- @expo/dev-tools@0.13.63
- @expo/electron-adapter@0.0.34
- expo-cli@4.0.4
- expo-optimize@0.1.65
- @expo/metro-config@0.1.42
- @expo/next-adapter@2.1.48
- expo-pwa@0.0.53
- uri-scheme@1.0.50
- @expo/webpack-config@0.12.47
- @expo/xdl@59.0.3

## [Fri, 27 Nov 2020 14:33:45 -0800](https://github.com/expo/expo-cli/commit/7bb61ba51da0eafce3faa8cbf59124f56ebe7e7d)

### 🎉 New features

- [image-utils] Upgraded jimp to the smaller version ([#2963](https://github.com/expo/expo-cli/issues/2963))
- [cli] Make it possible to run expo upgrade with beta release prior to actually setting beta flag ([#2967](https://github.com/expo/expo-cli/issues/2967))

### 📦 Packages updated

- @expo/config-plugins@1.0.3
- @expo/dev-tools@0.13.62
- @expo/electron-adapter@0.0.33
- expo-cli@4.0.3
- expo-optimize@0.1.64
- @expo/image-utils@0.3.9
- @expo/next-adapter@2.1.47
- expo-pwa@0.0.52
- uri-scheme@1.0.49
- @expo/webpack-config@0.12.46
- @expo/xdl@59.0.2

## [Fri, 27 Nov 2020 10:31:00 -0800](https://github.com/expo/expo-cli/commit/939de8ba6eb90979f7975de5ae2197208319773b)

### 🛠 Breaking changes

### 🎉 New features

### 🐛 Bug fixes

- [cli] fix prompt selection ([#2966](https://github.com/expo/expo-cli/issues/2966))

### 📦 Packages updated

- expo-cli@4.0.2

## [Thu, 26 Nov 2020 16:54:28 -0800](https://github.com/expo/expo-cli/commit/1995c2f93d03a733480d95f22145170622158b01)

### 🛠 Breaking changes

### 🎉 New features

### 🐛 Bug fixes

- [cli] Disable strikethrough in expo-cli select prompts
- [config] Run splash first config in dangerous configs to fix race condition ([#2959](https://github.com/expo/expo-cli/issues/2959))

### 📦 Packages updated

- @expo/config-plugins@1.0.2
- @expo/dev-tools@0.13.61
- expo-cli@4.0.1
- uri-scheme@1.0.48
- @expo/xdl@59.0.1

## [Thu, 26 Nov 2020 12:25:12 -0800](https://github.com/expo/expo-cli/commit/a69fdfdcda48ca1ebf09b1e862fe84043f569d9d)

### 🛠 Breaking changes

- [cli] Removed `generate-module` command ([#2903](https://github.com/expo/expo-cli/pull/2903))
- [cli] Use submission service by default ([#2876](https://github.com/expo/expo-cli/issues/2876))
- [cli] Delete apply command in favor of eject. Don't worry, you probably were not using this command anyways. ([#2899](https://github.com/expo/expo-cli/issues/2899))

### 🎉 New features

- [cli] Record simctl error ([#2887](https://github.com/expo/expo-cli/issues/2887))
- [cli] Replace process.exits with errors ([#2901](https://github.com/expo/expo-cli/issues/2901))
- [cli] Support grouping and hiding in the introspect script ([#2931](https://github.com/expo/expo-cli/issues/2931))
- [cli] debug logging ([#2946](https://github.com/expo/expo-cli/issues/2946))
- [config plugins] Implement debug logging for mods ([#2950](https://github.com/expo/expo-cli/issues/2950))
- [config plugins] Prevent passing a plugin that requires props without props ([#2937](https://github.com/expo/expo-cli/issues/2937))
- [config plugins] Support updating the project settings.gradle name ([#2955](https://github.com/expo/expo-cli/issues/2955))
- [config plugins] base mod improvements ([#2948](https://github.com/expo/expo-cli/issues/2948))
- [config plugins] name all config plugins ([#2949](https://github.com/expo/expo-cli/issues/2949))
- [config-plugins] create package ([#2956](https://github.com/expo/expo-cli/issues/2956))
- [config] add option to get public expo config method ([#2863](https://github.com/expo/expo-cli/issues/2863))
- [config] android plugins ([#2849](https://github.com/expo/expo-cli/issues/2849))
- [deps] remove inquirer
- [deps] upgrade react-dev-utils to 11.0.1 ([#2906](https://github.com/expo/expo-cli/issues/2906))
- [deps] upgrade to bunyan 4.0.0 ([#2920](https://github.com/expo/expo-cli/issues/2920))
- [web] Improve PWA warning ([#2907](https://github.com/expo/expo-cli/issues/2907))
- [web] promote web warning to late beta ([#2889](https://github.com/expo/expo-cli/issues/2889))
- [xdl] Switch to in-process Metro JS bundling through `@expo/dev-server` starting from SDK 40 ([#2921](https://github.com/expo/expo-cli/pull/2921))

### 🐛 Bug fixes

- [actions] Upgrade cache to v2 ([#2872](https://github.com/expo/expo-cli/issues/2872))
- [cli] Fix build/status return types ([#2915](https://github.com/expo/expo-cli/issues/2915))
- [cli] Replace inquirer with prompts in init ([#2905](https://github.com/expo/expo-cli/issues/2905))
- [cli] Resolve main fields to determine if an index.js should be generated ([#2874](https://github.com/expo/expo-cli/issues/2874))
- [cli] delete generate-module ([#2903](https://github.com/expo/expo-cli/issues/2903))
- [cli][upgrade] support projects without a config ([#2888](https://github.com/expo/expo-cli/issues/2888))
- [config plugins] Enable notifications by default ([#2958](https://github.com/expo/expo-cli/issues/2958))
- [config plugins] add files to 'copy bundle resources', not 'compile sources' build phase ([#2936](https://github.com/expo/expo-cli/issues/2936))
- [config] permissions plugins ([#2871](https://github.com/expo/expo-cli/issues/2871))
- [config][xdl] migrate project/publish to getPublicExpoConfig ([#2864](https://github.com/expo/expo-cli/issues/2864))
- [eject] Added more packages with extra setup ([#2870](https://github.com/expo/expo-cli/issues/2870))
- [image-utils] Fix blurry web favicon ([#2914](https://github.com/expo/expo-cli/issues/2914))
- [traveling-fastlane] add slightly modified manage_provisioning_profile ([#2928](https://github.com/expo/expo-cli/issues/2928))
- [xdl] On Android remove default template splash image when no splash image is specified in the app manifest ([#2883](https://github.com/expo/expo-cli/pull/2883))
- [xdl] Switch to in-process Metro JS bundling starting from SDK 40 ([#2921](https://github.com/expo/expo-cli/issues/2921))
- [xdl] Update web terminal UI ([#2890](https://github.com/expo/expo-cli/issues/2890))

### 📦 Packages updated

- @expo/config-plugins@1.0.1
- @expo/config@3.3.16
- @expo/dev-server@0.1.41
- @expo/dev-tools@0.13.60
- @expo/electron-adapter@0.0.32
- expo-cli@4.0.0
- expo-optimize@0.1.63
- @expo/image-utils@0.3.8
- @expo/json-file@8.2.25
- @expo/metro-config@0.1.41
- @expo/next-adapter@2.1.46
- @expo/package-manager@0.0.34
- pod-install@0.1.13
- expo-pwa@0.0.51
- @expo/schemer@1.3.22
- uri-scheme@1.0.47
- @expo/webpack-config@0.12.45
- @expo/xdl@59.0.0

## [Thu Nov 26 12:36:20 2020 +0100](https://github.com/expo/expo-cli/commit/5c432616d39fe0a8894b50d2e613284674a536e1)

### 🐛 Bug fixes

- [configure-splash-screen] On iOS fix auto-configuration when there's no PBXVariantGroup in the project ([#2945](https://github.com/expo/expo-cli/pull/2945))

### 📦 Packages updated

- @expo/configure-splash-screen@0.3.1

## [Mon, 9 Nov 2020 13:44:59 -0800](https://github.com/expo/expo-cli/commit/d5b8759b32d5a7747067a969728d9ba732926824)

### 🛠 Breaking changes

### 🎉 New features

- [cli] Added support for a custom scheme property ([#2860](https://github.com/expo/expo-cli/issues/2860))
- [cli] Clarify the experimental nature of the --dev-client flag
- [cli] Created scheme resolver for dev-client ([#2861](https://github.com/expo/expo-cli/issues/2861))
- [uri-scheme] sort Info.plist files by length ([#2859](https://github.com/expo/expo-cli/issues/2859))

### 🐛 Bug fixes

- [xdl] speed improvement - remove extra config read when resolving entry point ([#2836](https://github.com/expo/expo-cli/issues/2836))
- [xdl] fix updates ON_ERROR_RECOVERY setting for SDK 39 ([#2856](https://github.com/expo/expo-cli/issues/2856))

### 📦 Packages updated

- @expo/config@3.3.15
- @expo/dev-server@0.1.40
- @expo/dev-tools@0.13.59
- @expo/electron-adapter@0.0.31
- expo-cli@3.28.6
- expo-optimize@0.1.62
- @expo/metro-config@0.1.40
- @expo/next-adapter@2.1.45
- expo-pwa@0.0.50
- uri-scheme@1.0.46
- @expo/webpack-config@0.12.44
- @expo/xdl@58.0.20

## [Wed, 4 Nov 2020 19:04:11 -0800](https://github.com/expo/expo-cli/commit/4a29c163952ea8f4a27e3621b2aa08fce164923e)

### 🛠 Breaking changes

### 🎉 New features

- [xdl][cli] <feat>: Add READMEs to the .expo & .expo-shared folders ([#2830](https://github.com/expo/expo-cli/issues/2830))

### 🐛 Bug fixes

- [configure-splash-screen] Use proper bin paths to files ([#2840](https://github.com/expo/expo-cli/issues/2840))
- [config] android fixes ([#2851](https://github.com/expo/expo-cli/issues/2851))
- [config] iOS fix types ([#2852](https://github.com/expo/expo-cli/issues/2852))
- [config] Updated Android Facebook module to better accommodate plugins ([#2848](https://github.com/expo/expo-cli/issues/2848))
- [pkcs12] add fingerprint support for unparseable x509 certs ([#2854](https://github.com/expo/expo-cli/issues/2854))
- [traveling-fastlane] publish 1.15.2
- [travelling-fastlane] Update app_produce to return App ID ([#2855](https://github.com/expo/expo-cli/issues/2855))

### 📦 Packages updated

- @expo/config@3.3.14
- @expo/dev-server@0.1.39
- @expo/dev-tools@0.13.58
- @expo/electron-adapter@0.0.30
- expo-cli@3.28.5
- expo-optimize@0.1.61
- @expo/metro-config@0.1.39
- @expo/next-adapter@2.1.44
- @expo/pkcs12@0.0.4
- expo-pwa@0.0.49
- uri-scheme@1.0.45
- @expo/webpack-config@0.12.43
- @expo/xdl@58.0.19

## [Tue, 3 Nov 2020 10:49:55 -0800](https://github.com/expo/expo-cli/commit/de4124a9cfc50715e0c9748151dfdbe254e57074)

### 🛠 Breaking changes

### 🎉 New features

- [config] config plugins iOS ([#2789](https://github.com/expo/expo-cli/issues/2789))

### 🐛 Bug fixes

- [cli] Use exact @expo/eas-build-job version, update it, and fix related TS errors ([#2850](https://github.com/expo/expo-cli/issues/2850))
- [cli] Fix eas gradle script not working when used with react-native-config
- [config] Force entitlement paths to be in posix ([#2841](https://github.com/expo/expo-cli/issues/2841))

### 📦 Packages updated

- @expo/config@3.3.13
- @expo/dev-server@0.1.38
- @expo/dev-tools@0.13.57
- @expo/electron-adapter@0.0.29
- expo-cli@3.28.4
- expo-optimize@0.1.60
- @expo/metro-config@0.1.38
- @expo/next-adapter@2.1.43
- expo-pwa@0.0.48
- uri-scheme@1.0.44
- @expo/webpack-config@0.12.42
- @expo/xdl@58.0.18

## [Thu, 22 Oct 2020 15:31:16 -0700](https://github.com/expo/expo-cli/commit/8def7d96509daf819754b0b7af09e1f3159896c1)

### 🛠 Breaking changes

### 🎉 New features

- [cli] Support --platform option for eas:build:init
- [cli] Update --latest flag help message
- [cli] Validate the credentials for android keystore

### 🐛 Bug fixes

- [cli][xdl] Pass owner through to findReusableBuildAsync
- [xdl] Rename debug to expo raw log to avoid collision ([#2818](https://github.com/expo/expo-cli/issues/2818))

### 📦 Packages updated

- @expo/dev-tools@0.13.55
- expo-cli@3.28.2
- @expo/xdl@58.0.16

## [Mon, 19 Oct 2020 16:43:59 -0700](https://github.com/expo/expo-cli/commit/1062d0bba966500dba751a890938445ee195d919)

### 🎉 New features

- [cli] Add support for --latest flag in client:install:x ([#2804](https://github.com/expo/expo-cli/issues/2804))
- [cli] Add `releaseChannel` field to the profile in `eas.json`
- [config] Created AssetContents ([#2798](https://github.com/expo/expo-cli/issues/2798))
- [config] disjointed features from plugins ios ([#2811](https://github.com/expo/expo-cli/issues/2811))
- [pkcs12] return null if pkcs keystore has no cert under friendly name ([#2805](https://github.com/expo/expo-cli/issues/2805))
- [pkcs12] amend readme with updated method names

### 🐛 Bug fixes

- [config] fix entitlements functionality ([#2797](https://github.com/expo/expo-cli/issues/2797))
- [config] setFacebookConfig needs to be async function due to ensureFacebookActivityAsync
- [cli] Use expo/plist instead of xdl IosPlist ([#2799](https://github.com/expo/expo-cli/issues/2799))
- [cli] Fix custom Expo client build ([#2796](https://github.com/expo/expo-cli/issues/2796))

### 📦 Packages updated

- @expo/config@3.3.11
- @expo/dev-server@0.1.36
- @expo/dev-tools@0.13.54
- @expo/electron-adapter@0.0.27
- expo-cli@3.28.1
- expo-optimize@0.1.58
- @expo/metro-config@0.1.36
- @expo/next-adapter@2.1.41
- @expo/pkcs12@0.0.2
- expo-pwa@0.0.46
- uri-scheme@1.0.42
- @expo/webpack-config@0.12.40
- @expo/xdl@58.0.15

## [Wed, 14 Oct 2020 14:27:23 -0700](https://github.com/expo/expo-cli/commit/0fde837f6024c2cd53e089df894063b3f4b38ca2)

### 🎉 New features

- [configure-splash-screen] Added `--version, -V` option for version printing. ([#2785](https://github.com/expo/expo-cli/pull/2785))
- [pkcs12] new package for PKCS#12 utilities ([#2773](https://github.com/expo/expo-cli/issues/2773))
- [config] Created paths module for ios ([#2784](https://github.com/expo/expo-cli/issues/2784))
- [cli] Skip ejecting iOS on Windows - this doesn't work properly at the moment, so we instead encourage people to use macOS or Linux for ejecting the iOS project.
- [cli] Update expo.io URLs used in expo-cli to match changes to the website ([#2767](https://github.com/expo/expo-cli/issues/2767))

### 🐛 Bug fixes

- [cli] Fix parallel uploads ([#2736](https://github.com/expo/expo-cli/issues/2736))
- [cli] Add "client" copy to Android and iOS open option ([#2778](https://github.com/expo/expo-cli/issues/2778))
- [cli] Add a EAS_OUTPUT_JOB_JSON environment variable to output JSON for the job
- [cli] Update Android install/uninstall copy ([#2763](https://github.com/expo/expo-cli/issues/2763))
- [cli] Disable error message when aborting ([#2751](https://github.com/expo/expo-cli/issues/2751))
- [cli] use correct description for openDevToolsAtStartup in the ? message ([#2755](https://github.com/expo/expo-cli/issues/2755))
- [config] minor plugin updates ([#2788](https://github.com/expo/expo-cli/issues/2788))
- [config] Fix Android scandir error when ejecting on windows ([#2774](https://github.com/expo/expo-cli/issues/2774))

### 📦 Packages updated

- @expo/config@3.3.10
- @expo/configure-splash-screen@0.3.0
- @expo/dev-server@0.1.35
- @expo/dev-tools@0.13.53
- @expo/electron-adapter@0.0.26
- expo-cli@3.28.0
- expo-optimize@0.1.57
- @expo/metro-config@0.1.35
- @expo/next-adapter@2.1.40
- @expo/pkcs12@0.0.1
- expo-pwa@0.0.45
- uri-scheme@1.0.41
- @expo/webpack-config@0.12.39
- @expo/xdl@58.0.14

## [Sat, 3 Oct 2020 22:11:17 -0700](https://github.com/expo/expo-cli/commit/6d8f7c734f501b9f194d232df7a0f65d9b9415e7)

### 🛠 Breaking changes

### 🎉 New features

### 🐛 Bug fixes

- [xdl] Revert regex replace for < SDK 39 splash screen
- [expo-cli] Disable TerminalUI sign in/out method (s) ([#2752](https://github.com/expo/expo-cli/issues/2752))

### 📦 Packages updated

- @expo/dev-tools@0.13.52
- expo-cli@3.27.14
- @expo/xdl@58.0.13

## [Fri, 2 Oct 2020 11:17:40 -0700](https://github.com/expo/expo-cli/commit/b02ce39f257045aa512ead62bdffa3a766a02c97)

### 🛠 Breaking changes

### 🎉 New features

- [cli] Add two-factor authentication to login ([#2581](https://github.com/expo/expo-cli/issues/2581))
- [cli] Make `expo install` pass through to npm or yarn directly when running it in a bare React Native app without the expo package installed. ([#2729](https://github.com/expo/expo-cli/issues/2729))
- [cli] EAS Build: Configure `expo-updates` automatically if it's installed when running `eas:build:init` [#2587](https://github.com/expo/expo-cli/pull/2587)
- [cli] Support absolute path in credentials.json for gradle

### 🐛 Bug fixes

- [config] Fix relative module resolution for config files ([#2744](https://github.com/expo/expo-cli/issues/2744))
- [configure-splash-screen] don't export color-string types ([#2739](https://github.com/expo/expo-cli/issues/2739))
- [cli] Fix simulator picking when multiple device versions exist ([#2742](https://github.com/expo/expo-cli/issues/2742))
- [cli] Fix EXPO_DEBUG on expo upgrade
- [cli] Fix command help options order ([#2721](https://github.com/expo/expo-cli/issues/2721))
- [xdl] Add support for splash screen SDK-39 standalone app configuration & building ([#2747](https://github.com/expo/expo-cli/issues/2747))

### 📦 Packages updated

- @expo/config@3.3.9
- @expo/dev-server@0.1.34
- @expo/dev-tools@0.13.51
- @expo/electron-adapter@0.0.25
- expo-cli@3.27.13
- expo-optimize@0.1.56
- @expo/image-utils@0.3.7
- @expo/metro-config@0.1.34
- @expo/next-adapter@2.1.39
- expo-pwa@0.0.44
- uri-scheme@1.0.40
- @expo/webpack-config@0.12.38
- @expo/xdl@58.0.12

## [Mon, 28 Sep 2020 12:02:49 -0700](https://github.com/expo/expo-cli/commit/19e206bdc3973aa5263a11999c9624ef3590b00d)

### 🛠 Breaking changes

- [config-types] remove loading key ([#2722](https://github.com/expo/expo-cli/issues/2722))

### 🎉 New features

- [config-types] Split up platform configs ([#2716](https://github.com/expo/expo-cli/issues/2716))
- [config-types] Rename root config file to ExpoConfig ([#2715](https://github.com/expo/expo-cli/issues/2715))

### 🐛 Bug fixes

- [config-types] android.intentFilters.data type fix ([#2707](https://github.com/expo/expo-cli/issues/2707))
- [cli] Fix typo when JS installation fails on eject ([#2712](https://github.com/expo/expo-cli/issues/2712))
- [cli] Revert "Improved package name validation ([#2687](https://github.com/expo/expo-cli/issues/2687))"
- [cli] Fix link to hashAsseFiles information on eject
- [cli] Remove short form of --count (-count didn't work, -c is taken)
- [cli] Fix windows build compatibility ([#2705](https://github.com/expo/expo-cli/issues/2705))

### 📦 Packages updated

- @expo/config@3.3.7
- @expo/configure-splash-screen@0.2.1
- @expo/dev-server@0.1.32
- @expo/dev-tools@0.13.49
- @expo/electron-adapter@0.0.23
- expo-cli@3.27.11
- expo-optimize@0.1.54
- @expo/metro-config@0.1.32
- @expo/next-adapter@2.1.37
- expo-pwa@0.0.42
- uri-scheme@1.0.38
- @expo/webpack-config@0.12.36
- @expo/xdl@58.0.10

## [Mon, 28 Sep 2020 15:47:29 +0200](https://github.com/expo/expo-cli/commit/3407fb46596c77197b8dd140046a5388026aec36)

### 🎉 New features

- [configure-splash-screen]<feat>: Accommodate Android singletons.SplashScreen import from the subpackage ([#2699](https://github.com/expo/expo-cli/issues/2699))
- [configure-splash-screen]<feat>: Make Android configuration conform to the new native API ([#2698](https://github.com/expo/expo-cli/issues/2698))

## [Thu, 24 Sep 2020 16:18:06 -0700](https://github.com/expo/expo-cli/commit/8443580c8093f28550c7ebbb8d1b66bacc83a201)

### 🛠 Breaking changes

### 🎉 New features

### 🐛 Bug fixes

- [config] Disable splash screen applying on eject until we fix issue with @expo/configure-splash-screen versioning. [#2700](https://github.com/expo/expo-cli/pull/2700).

### 📦 Packages updated

- @expo/config@3.3.6
- @expo/dev-server@0.1.31
- @expo/dev-tools@0.13.48
- @expo/electron-adapter@0.0.22
- expo-cli@3.27.10
- expo-optimize@0.1.53
- @expo/metro-config@0.1.31
- @expo/next-adapter@2.1.36
- expo-pwa@0.0.41
- uri-scheme@1.0.37
- @expo/webpack-config@0.12.35
- @expo/xdl@58.0.9

## [Thu, 24 Sep 2020 15:27:32 -0700](https://github.com/expo/expo-cli/commit/c76d808751c8f20203b0d3555ec3a210a37d0d1d)

### 🎉 New features

- [cli] Improved package name validation ([#2687](https://github.com/expo/expo-cli/issues/2687))
- [cli] Recommend Transporter.app if expo upload:ios fails
- [cli] Only show upload:ios command when build is for an iOS archive
- [config] Created XML module ([#2694](https://github.com/expo/expo-cli/issues/2694))
- [config][eject] Added ios.entitlements ([#2624](https://github.com/expo/expo-cli/issues/2624))
- [config] Created Paths module ([#2695](https://github.com/expo/expo-cli/issues/2695))
- [config] Resolve inline locales ([#2691](https://github.com/expo/expo-cli/issues/2691))
- [config-types] Update for schema changes ([#2690](https://github.com/expo/expo-cli/issues/2690))
- [xdl] use `process.env.METRO_NODE_OPTIONS` when starting Metro ([#2401](https://github.com/expo/expo-cli/issues/2401))

### 🐛 Bug fixes

- [xdl] add export modificator for Project.startExpoServerAsync function ([#2697](https://github.com/expo/expo-cli/issues/2697))

### 📦 Packages updated

- @expo/config@3.3.5
- @expo/dev-server@0.1.30
- @expo/dev-tools@0.13.47
- @expo/electron-adapter@0.0.21
- expo-cli@3.27.9
- expo-optimize@0.1.52
- @expo/metro-config@0.1.30
- @expo/next-adapter@2.1.35
- expo-pwa@0.0.40
- uri-scheme@1.0.36
- @expo/webpack-config@0.12.34
- @expo/xdl@58.0.8

## [Tue, 22 Sep 2020 22:27:01 -0700](https://github.com/expo/expo-cli/commit/877053dc8395e1cd98d2296eccf336d4f7c08f05)

### 🛠 Breaking changes

- [xdl] Deprecated `Project.getManifestUrlWithFallbackAsync()` in favor of `UrlUtils.constructManifestUrlAsync()`. [#2684](https://github.com/expo/expo-cli/pull/2684)
- [xdl] Deprecated `Project.getUrlAsync()` in favor of `UrlUtils.constructManifestUrlAsync()`. [#2684](https://github.com/expo/expo-cli/pull/2684)
- [xdl] Removed `Project.getSlugAsync()`, `Project.stopTunnelsAsync()`, `Project.startExpoServerAsync()`, `Project.stopExpoServerAsync()`, `Project.ProjectStatus`. [#2684](https://github.com/expo/expo-cli/pull/2684)

### 🎉 New features

- [expo-cli] replace @expo/build-tools with @expo/eas-build-job to reduce dependencies size. [#2679](https://github.com/expo/expo-cli/pull/2679)
- [expo-cli] Upgrade - skip installing the expo package if it is already set to the correct version
- [expo-cli] Upgrade - link to upgrade-helper in bare workflow when relevant

### 🐛 Bug fixes

- [config] improve modules ([#2674](https://github.com/expo/expo-cli/issues/2674))
- [expo-cli] Support unauthorized devices ([#2681](https://github.com/expo/expo-cli/issues/2681))

### 📦 Packages updated

- @expo/config@3.3.4
- @expo/dev-server@0.1.29
- @expo/dev-tools@0.13.46
- @expo/electron-adapter@0.0.20
- expo-cli@3.27.8
- expo-optimize@0.1.51
- @expo/metro-config@0.1.29
- @expo/next-adapter@2.1.34
- expo-pwa@0.0.39
- uri-scheme@1.0.35
- @expo/webpack-config@0.12.33
- @expo/xdl@58.0.7

## [Mon, 21 Sep 2020 19:11:42 -0700](https://github.com/expo/expo-cli/commit/d77fcb4613fa535ca809c833acc016759d93d996)

### 🛠 Breaking changes

### 🎉 New features

- [configure-splash-screen] Simplified and unified arguments, parameters and `--help` output. See `configure-splash-screen --help` to see the changes. [#2297](https://github.com/expo/expo-cli/pull/2297)

### 🐛 Bug fixes

- [xdl] Fix downloadApkAsync so it uses passed in URL rather than always depending on versions endpoint `androidUrl`
- [cli] Bring back support for EXPO_APPLE_ID ([#2671](https://github.com/expo/expo-cli/issues/2671))

### 📦 Packages updated

- @expo/config@3.3.3
- @expo/configure-splash-screen@0.1.19
- @expo/dev-server@0.1.28
- @expo/dev-tools@0.13.45
- @expo/electron-adapter@0.0.19
- expo-cli@3.27.7
- expo-optimize@0.1.50
- @expo/metro-config@0.1.28
- @expo/next-adapter@2.1.33
- expo-pwa@0.0.38
- uri-scheme@1.0.34
- @expo/webpack-config@0.12.32
- @expo/xdl@58.0.6

## [Fri, 18 Sep 2020 12:23:25 -0700](https://github.com/expo/expo-cli/commit/a5eb9cafd0b46120d3fcafa861b4fac164c7d978)

### 🛠 Breaking changes

### 🎉 New features

- [json-file] Add `ensureDir` option [#2664](https://github.com/expo/expo-cli/pull/2664)
- [configure-splash-screen] Refactor and integrate with `@expo/config` ([#2297](https://github.com/expo/expo-cli/issues/2297))

### 🐛 Bug fixes

- [cli] `build:android` fix missing keytool warning if user want to specify ceredentials manually [#2662](https://github.com/expo/expo-cli/pull/2662)
- [cli] Re-use source root lookup from @expo/config to fix updates config on init for projects with names that are altered for native project compat
- [cli] fix prompt helpers ([#2667](https://github.com/expo/expo-cli/issues/2667))
- [xdl] Build iOS shell app artifact in the current directory (instead of one level up). ([#2608](https://github.com/expo/expo-cli/issues/2608))
- [next-adapter] ReferenceError Html is not defined ([#2666](https://github.com/expo/expo-cli/issues/2666))

### 📦 Packages updated

- @expo/config@3.3.2
- @expo/configure-splash-screen@0.1.17
- @expo/dev-server@0.1.27
- @expo/dev-tools@0.13.44
- @expo/electron-adapter@0.0.18
- expo-cli@3.27.6
- expo-optimize@0.1.49
- @expo/json-file@8.2.24
- @expo/metro-config@0.1.27
- @expo/next-adapter@2.1.32
- @expo/package-manager@0.0.33
- pod-install@0.1.12
- expo-pwa@0.0.37
- uri-scheme@1.0.33
- @expo/webpack-config@0.12.31
- @expo/xdl@58.0.5

## [Thu, 17 Sep 2020 13:28:59 -0700](https://github.com/expo/expo-cli/commit/f0c9270058f38cc1b58bd03765e3e1de747c7b39)

### 🛠 Breaking changes

- [cli] Remove deprecated --web-only flag from start command

### 🎉 New features

- [cli] EAS Build: Improve errors and warnings when deprecating API [#2639](https://github.com/expo/expo-cli/pull/2639)
- [cli] support `--config` flag in `expo credentials:manager` [#2641](https://github.com/expo/expo-cli/pull/2641)
- [cli] warn the user when the bundle ID or package name is already in use ([#2616](https://github.com/expo/expo-cli/issues/2616))
- [cli] Make gitignore and native project step idempotent in eject ([#2620](https://github.com/expo/expo-cli/issues/2620))
- [cli] Added no-install and npm args to eject ([#2621](https://github.com/expo/expo-cli/issues/2621))
- [cli] Improve JSON error formatting ([#2635](https://github.com/expo/expo-cli/issues/2635))
- [cli] warn about Constants.manifest and assetBundlePatterns on eject ([#2648](https://github.com/expo/expo-cli/issues/2648))
- [cli] Log about upload after build:ios completes ([#2649](https://github.com/expo/expo-cli/issues/2649))
- [config-types] Generate types for Expo config ([#2622](https://github.com/expo/expo-cli/issues/2622))
- [optimize] Compile expo/config in expo-optimize - faster install time! ([#2643](https://github.com/expo/expo-cli/issues/2643))
- [xdl] Exclude IDFA code from Branch ([#2655](https://github.com/expo/expo-cli/issues/2655))

### 🐛 Bug fixes

- [configure-splash-screen] Fix error when project's name contains only numeric characters [#2657](https://github.com/expo/expo-cli/pull/2657)
- [cli] Fix credential fetching for team members acting on behalf of a project owner [#2660](https://github.com/expo/expo-cli/pull/2660)
- [cli] Fix errors preventing expo eas:build:init from working
- [cli] add missing owner query param ([#2660](https://github.com/expo/expo-cli/issues/2660))
- [next-adapter] Next warning Expected Document Component Html was not rendered ([#2661](https://github.com/expo/expo-cli/issues/2661))
- [config] Disable using the project's babel.config.js for transpiling app.config.js ([#2656](https://github.com/expo/expo-cli/issues/2656))
- [configure-splash-screen] Fix error up upon numeric name ([#2657](https://github.com/expo/expo-cli/issues/2657))
- [xdl] resolve locales from project root ([#2647](https://github.com/expo/expo-cli/issues/2647))
- [cli] Remove external config evaluation script ([#2625](https://github.com/expo/expo-cli/issues/2625))
- [cli] remove extra config reads ([#2636](https://github.com/expo/expo-cli/issues/2636))
- [xdl] Fix path to expo-random
- [xdl] Add expo-random to SDK39+ iOS shell apps ([#2640](https://github.com/expo/expo-cli/issues/2640))
- [cli] Added better logs for invalid custom config paths ([#2626](https://github.com/expo/expo-cli/issues/2626))

### 📦 Packages updated

- @expo/babel-preset-cli@0.2.18
- @expo/config@3.3.1
- @expo/configure-splash-screen@0.1.16
- @expo/dev-server@0.1.26
- @expo/dev-tools@0.13.43
- @expo/electron-adapter@0.0.17
- expo-cli@3.27.5
- expo-codemod@1.0.29
- expo-optimize@0.1.48
- @expo/image-utils@0.3.6
- @expo/json-file@8.2.23
- @expo/metro-config@0.1.26
- @expo/next-adapter@2.1.30
- @expo/osascript@2.0.24
- @expo/package-manager@0.0.32
- @expo/plist@0.0.10
- pod-install@0.1.11
- expo-pwa@0.0.36
- @expo/schemer@1.3.21
- uri-scheme@1.0.32
- @expo/webpack-config@0.12.30
- @expo/xdl@58.0.4

## [Wed, 9 Sep 2020 13:28:10 -0700](https://github.com/expo/expo-cli/commit/7b9b00b12095ce6ea5c02c03f793fcc6bf0f55a7)

### 🎉 New features

- [expo-cli] Clean up TerminalUI ([#2614](https://github.com/expo/expo-cli/issues/2614))

### 🐛 Bug fixes

- [expo-cli] Default to silent when installing node dependencies through init

### 📦 Packages updated

- expo-cli@3.27.4

## [Wed, 9 Sep 2020 10:03:41 -0700](https://github.com/expo/expo-cli/commit/2a2a120e30d64ea535fb251ff203c97b457ab8bf)

### 🐛 Bug fixes

- [xdl] Use ~assets for publish and assets for export

### 📦 Packages updated

- @expo/dev-tools@0.13.42
- expo-cli@3.27.3
- @expo/xdl@58.0.3

## [Thu, 9 Sep 2020 16:32:14 +0200](https://github.com/expo/expo-cli/commit/58ac4c43d0b3e7cb8db5b2c46d8602bf101e33db)

### 🎉 New features

- [expo-cli] EAS Build: add `experimental.npmToken` to `credentials.json` [#2603](https://github.com/expo/expo-cli/pull/2603)
- [expo-cli] EAS Build: monorepo support [#2601](https://github.com/expo/expo-cli/pull/2601)

## [Thu, 8 Sep 2020 14:30:14 +0200](https://github.com/expo/expo-cli/commit/f0e24ee436806c109c19329c7e161fee0d2f0c81)

### 🛠 Breaking changes

- [xdl] Delete deprecated `Exp.extractAndInitializeTemplateApp`, `Exp.initGitRepoAsync`, `Exp.installDependenciesAsync`, `Exp.getPublishInfoAsync`, [#2590](https://github.com/expo/expo-cli/pull/2590)
- [expo-cli][export] No longer prompts to automatically delete conflicting files, they must now be manually deleted, or the command must be rerun with `--force` [#2576](https://github.com/expo/expo-cli/pull/2576)
- [xdl] Deleted deprecated `Web` module [#2588](https://github.com/expo/expo-cli/pull/2588)

### 🎉 New features

- [expo-cli][eject] support Facebook props being removed [#2566](https://github.com/expo/expo-cli/pull/2566))
- [expo-cli][config] Generate Android icons on eject and apply [#2087](https://github.com/expo/expo-cli/pull/2087)
- [expo-cli][export] List all conflicting files, allow for tolerable file collisions, prompt for `public-url` when it's not provided in interactive mode [#2576](https://github.com/expo/expo-cli/pull/2576)

### 🐛 Bug fixes

- [webpack] Fix copy webpack plugin for web overrides ([#2558](https://github.com/expo/expo-cli/issues/2558))

## [Thu, 3 Sep 2020 10:30:14 +0200](https://github.com/expo/expo-cli/commit/68920e489dd4508e30f0da14bbe91b36427380a7)

### 🐛 Bug fixes

- [expo-cli] fix Segment context format [#2560](https://github.com/expo/expo-cli/pull/2560)

### 📦 Packages updated

- expo-cli@3.26.2

## [Wed, 2 Sep 2020 11:12:02 -0700](https://github.com/expo/expo-cli/commit/c97aba21376324b2131bb5058d193aab5ceb77f4)

### 🎉 New features

- [expo-cli] EAS Build - track build process with Segment ([#2555](https://github.com/expo/expo-cli/issues/2555))

### 🐛 Bug fixes

- [cli] Fix requested sdk in upgrade command ([#2557](https://github.com/expo/expo-cli/issues/2557))

### 📦 Packages updated

- @expo/dev-tools@0.13.38
- expo-cli@3.26.1
- @expo/xdl@57.9.35

## [Tue, 1 Sep 2020 16:47:59 -0700](https://github.com/expo/expo-cli/commit/b4a945b6243f11555b5f1b37eba98289ca5f342b)

### 🛠 Breaking changes

- [expo-cli] remove `push:web:upload`, `push:web:generate`, `push:web:show`, `push:web:clear` ([#2531](https://github.com/expo/expo-cli/pull/2531) by [@EvanBacon](https://github.com/EvanBacon))

### 🎉 New features

- [expo-cli] expo --help redesigned ([#2538](https://github.com/expo/expo-cli/pull/2538) by [@EvanBacon](https://github.com/EvanBacon))
- [expo-cli] expo upload - support tar.gz files from builds v2 ([#2504](https://github.com/expo/expo-cli/pull/2504) by [@EvanBacon](https://github.com/EvanBacon))
- [expo-cli] Implemented keychain storage for Apple ID ([#2508](https://github.com/expo/expo-cli/pull/2508) by [@EvanBacon](https://github.com/EvanBacon))
- [expo-cli] expo publish - Clean up upload results logs ([#2516](https://github.com/expo/expo-cli/pull/2516) by [@EvanBacon](https://github.com/EvanBacon))
- [expo-cli] expo eject - Added support for locales in eject and apply ([#2496](https://github.com/expo/expo-cli/pull/2496) by [@EvanBacon](https://github.com/EvanBacon))
- [expo-cli] expo publish - Log bundles after building ([#2527](https://github.com/expo/expo-cli/pull/2527) by [@EvanBacon](https://github.com/EvanBacon))
- [expo-cli] Improve warning logging on publish ([#2524](https://github.com/expo/expo-cli/issues/2524) by [@EvanBacon](https://github.com/EvanBacon))
- [expo-cli] Add shift+i hotkey in interactive prompt to select iOS simulator to open ([#2541](https://github.com/expo/expo-cli/pull/2541) by [@EvanBacon](https://github.com/EvanBacon))
- [expo-cli] Add shift+a hotkey in interactive prompt to select Android device/emulator to open ([#2550](https://github.com/expo/expo-cli/pull/2550) by [@EvanBacon](https://github.com/EvanBacon))
- [expo-cli] Improve edge case handling when upgrading Expo client in iOS simulator ([#2541](https://github.com/expo/expo-cli/pull/2541) by [@EvanBacon](https://github.com/EvanBacon))
- [expo-cli] expo eas:build - Add --skip-credentials-check option ([#2442](https://github.com/expo/expo-cli/pull/2442) by [@satya164](https://github.com/satya164))
- [expo-cli] Add a `eas:build:init` command ([#2443](https://github.com/expo/expo-cli/pull/2443) by [@satya164](https://github.com/satya164))
- [expo-cli] expo generate-module - Support for templates with Android native unit tests ([#2548](https://github.com/expo/expo-cli/pull/2548) by [@barthap](https://github.com/barthap))
- [expo-cli] eas build: collect build metadata ([#2532](https://github.com/expo/expo-cli/issues/2532))
- [xdl] Add support for passing app.json updates config to expo-updates in SDK 39 standalone apps ([#2539](https://github.com/expo/expo-cli/pull/2539) by [@esamelson](https://github.com/esamelson))

### 🐛 Bug fixes

- [dev-server] Use minify in prod ([#2526](https://github.com/expo/expo-cli/issues/2526) by [@EvanBacon](https://github.com/EvanBacon))
- [dev-tools] Fix layout shifting when url becomes available by rendering a placeholder for QR code ([c34397c41](https://github.com/expo/expo-cli/commit/c34397c41d2661a37235fa2a8b2dde027e1c5b87) by [@brentvatne](https://github.com/brentvatne))
- [expo-cli] Eas build fix prompt for unsynced credentials ([#2546](https://github.com/expo/expo-cli/issues/2546) by [@wkozyra95](https://github.com/wkozyra95))
- [expo-cli] expo upload:android - fix `--use-submission-service` not resulting in non-zero exit code when upload fails ([#2530](https://github.com/expo/expo-cli/pull/2530) by [@mymattcarroll](https://github.com/mymattcarroll))
- [expo-cli] Fix `generate-module` to support latest `expo-module-template` ([#2510](https://github.com/expo/expo-cli/pull/2510) by [@barthap](https://github.com/barthap))
- [expo-cli] Fix `generate-module` filename generation for modules without `expo-` prefix ([#2548](https://github.com/expo/expo-cli/pull/2548) by [@barthap](https://github.com/barthap))
- [image-utils] Fix setting background color when calling `Jimp.resize` ([#2535](https://github.com/expo/expo-cli/pull/2535) by [@cruzach](https://github.com/cruzach))
- [xdl] Remove undistributable code from root build.gradle ([#2547](https://github.com/expo/expo-cli/issues/2547) by [@sjchmiela](https://github.com/sjchmiela))
- [xdl] Remove expo-image from SDK39 standalone apps ([#2533](https://github.com/expo/expo-cli/issues/2533) by [@sjchmiela](https://github.com/sjchmiela))

### 📦 Packages updated

- @expo/config@3.2.22
- @expo/dev-server@0.1.24
- @expo/dev-tools@0.13.37
- @expo/electron-adapter@0.0.15
- expo-cli@3.26.0
- expo-optimize@0.1.46
- @expo/image-utils@0.3.4
- @expo/metro-config@0.1.24
- @expo/next-adapter@2.1.28
- expo-pwa@0.0.34
- uri-scheme@1.0.30
- @expo/webpack-config@0.12.28
- @expo/xdl@57.9.34

## [Thu Aug 27 10:25:29 2020 -0700](https://github.com/expo/expo-cli/commit/5f41c9306d9da10ab8a85e99659d9a039cf9e90b)

### 🎉 New features

- [eject] Added support for allowBackup ([#2506](https://github.com/expo/expo-cli/pull/2506) by [@EvanBacon](https://github.com/EvanBacon))
- [eject] Warn before ejecting that some config needs to be set on dynamic config ([#1761](https://github.com/expo/expo-cli/pull/1761) by [@brentvatne](https://github.com/brentvatne))
- [expo-cli] Added no-install option to expo init ([#2515](https://github.com/expo/expo-cli/pull/2515) by [@EvanBacon](https://github.com/EvanBacon))

### 🐛 Bug fixes

- [image-utils] Add missing dependencies ([#2512](https://github.com/expo/expo-cli/pull/2512) by [@byCedric](https://github.com/byCedric))
- [webpack-config] fix: handle empty favicons ([#2423](https://github.com/expo/expo-cli/pull/2423) by [@jaulz](https://github.com/jaulz))
- [config] Update "googleMobileAdsAutoInit" to be optional ([#2317](https://github.com/expo/expo-cli/pull/2317) by [@JamieS1211](https://github.com/JamieS1211))
- [webpack-config] add compatibility for node-pushnotifications in service worker ([#1440](https://github.com/expo/expo-cli/pull/1440) by [@jaulz](https://github.com/jaulz))

### 📦 Packages updated

- @expo/config@3.2.21
- @expo/dev-server@0.1.23
- @expo/dev-tools@0.13.36
- @expo/electron-adapter@0.0.14
- expo-cli@3.25.1
- expo-optimize@0.1.45
- @expo/image-utils@0.3.3
- @expo/metro-config@0.1.23
- @expo/next-adapter@2.1.27
- expo-pwa@0.0.33
- uri-scheme@1.0.29
- @expo/webpack-config@0.12.27
- @expo/xdl@57.9.33

## [Wed Aug 26 12:13:11 2020 +0200](https://github.com/expo/expo-cli/commit/7d5820b3d6a32862205355a01684c66f3787354e)

### 🎉 New features

- [expo-cli] EAS Build: warn user when credentials are not git ignored ([#2482](https://github.com/expo/expo-cli/pull/2482) by [@wkozyra95](https://github.com/wkozyra95))
- [expo-cli] EAS Build: tweaks ([#2485](https://github.com/expo/expo-cli/pull/2485) by [@dsokal](https://github.com/dsokal)):
  - initialize a git repository if it does not exist yet
  - improve reading the bundle identifier from the Xcode project (handle the string interpolation case)
- [xdl] Add EXPO_TOKEN authentication method ([#2415](https://github.com/expo/expo-cli/pull/2415) by [@byCedric](https://github.com/byCedric))
- [expo-cli] Generate iOS icons on eject and apply ([#2495](https://github.com/expo/expo-cli/pull/2495) by [@EvanBacon](https://github.com/EvanBacon))
- [expo-cli] expo apply - prompt for bundle ID and package name ([#2498](https://github.com/expo/expo-cli/pull/2498) by [@EvanBacon](https://github.com/EvanBacon))
- [expo-cli] expo eject - added support for device families ([#2505](https://github.com/expo/expo-cli/pull/2505) by [@EvanBacon](https://github.com/EvanBacon))
- [expo-cli] EAS build: allow choosing scheme for ios project build ([#2501](https://github.com/expo/expo-cli/pull/2501) by [@dsokal](https://github.com/dsokal))

### 🐛 Bug fixes

- [expo-cli][xdl] EAS Build: Skip SDK version validation ([#2481](https://github.com/expo/expo-cli/pull/2481) by [@brentvatne](https://github.com/brentvatne))
- [expo-cli] expo apply - fix iOS name changing ([#2497](https://github.com/expo/expo-cli/pull/2497) by [@EvanBacon](https://github.com/EvanBacon))
- [expo-cli] expo apply - fix android schemes being added incorrectly ([#2507](https://github.com/expo/expo-cli/pull/2507) by [@EvanBacon](https://github.com/EvanBacon))
- [expo-cli] Fix progress bar when uploading iOS ([#2502](https://github.com/expo/expo-cli/pull/2502) by [@byCedric](https://github.com/byCedric))
- [expo-cli] Fix default bare project name to match regex in `expo-init` ([#2509](https://github.com/expo/expo-cli/pull/2509) by [@barthap](https://github.com/barthap))

### 📦 Packages updated

- @expo/config@3.2.20
- @expo/dev-server@0.1.22
- @expo/dev-tools@0.13.35
- @expo/electron-adapter@0.0.13
- expo-cli@3.25.0
- expo-optimize@0.1.44
- @expo/image-utils@0.3.2
- @expo/metro-config@0.1.22
- @expo/next-adapter@2.1.26
- expo-pwa@0.0.32
- uri-scheme@1.0.28
- @expo/webpack-config@0.12.26
- @expo/xdl@57.9.32

## [Tue, 18 Aug 2020 21:14:50 -0700](https://github.com/expo/expo-cli/commit/e98f6916378a5db2a670f0a86ad1f5eaccd7a053)

### 🛠 Breaking changes

- [webpack-config] Disable offline support by default in SDK 39 ([#2475](https://github.com/expo/expo-cli/issues/2475) by [@EvanBacon](https://github.com/EvanBacon))

### 🎉 New features

- [expo-cli]: EAS Build: add command `eas:credentials:sync` ([#2460](https://github.com/expo/expo-cli/pull/2460) by [@wkozyra95](https://github.com/wkozyra95))
- [xdl] update ios Podfile excluded unimodules for SDK 39 ([#2471](https://github.com/expo/expo-cli/issues/2471) by [esamelson](https://github.com/esamelson))

### 🐛 Bug fixes

- [expo-cli] Only run expo service checks from the doctor command ([#2474](https://github.com/expo/expo-cli/issues/2474) by [@byCedric](https://github.com/byCedric))

### 📦 Packages updated

- @expo/dev-tools@0.13.34
- @expo/electron-adapter@0.0.12
- expo-cli@3.24.2
- @expo/next-adapter@2.1.25
- @expo/webpack-config@0.12.25
- @expo/xdl@57.9.31

## [Tue Aug 18 14:03:16 2020 +0200](https://github.com/expo/expo-cli/commit/2329769df21245f3cb625fd9b2aeac10baa06969)

### 🛠 Breaking changes

- [expo-cli] EAS Build: Upgrade `@expo/build-tools` to `0.1.14` to add support for glob patterns for `artifactPath`.

### 🎉 New features

- [expo-cli] Force users to confirm deleting android credentials ([#2457](https://github.com/expo/expo-cli/pull/2457) by [@byCedric](https://github.com/byCedric))
- [expo-cli] EAS Build: print credentials source before running build ([#2453](https://github.com/expo/expo-cli/pull/2453) by [@dsokal](https://github.com/dsokal))
- [expo-cli][xdl] expo doctor - add network check ([#2424](https://github.com/expo/expo-cli/pull/2424) by [@byCedric](https://github.com/byCedric))
- [expo-cli] expo eject - support projects with dynamic or missing configs ([#2464](https://github.com/expo/expo-cli/pull/2464) by [@EvanBacon](https://github.com/EvanBacon))
- [config] Allow scheme arrays ([#2462](https://github.com/expo/expo-cli/pull/2462) by [@EvanBacon](https://github.com/EvanBacon))

### 🐛 Bug fixes

- [expo-cli] EAS Build: better error handling when using local credentials.json ([#2452](https://github.com/expo/expo-cli/pull/2452) by [@wkozyra95](https://github.com/wkozyra95))
- [package-manager] fix pod-install for macOS projects ([#2461](https://github.com/expo/expo-cli/pull/2461) by [@Simek](https://github.com/Simek))
- [xdl] Expand Android permissions blacklist and add annotations ([#2458](https://github.com/expo/expo-cli/pull/2458) by [@byCedric](https://github.com/byCedric))

### 📦 Packages updated

- @expo/config@3.2.19
- @expo/dev-server@0.1.21
- @expo/dev-tools@0.13.33
- @expo/electron-adapter@0.0.11
- expo-cli@3.24.1
- expo-optimize@0.1.43
- @expo/metro-config@0.1.21
- @expo/next-adapter@2.1.24
- @expo/package-manager@0.0.31
- pod-install@0.1.10
- expo-pwa@0.0.31
- uri-scheme@1.0.27
- @expo/webpack-config@0.12.24
- @expo/xdl@57.9.30

## [Tue Aug 11 10:28:08 2020 +0200](https://github.com/expo/expo-cli/commit/199f5ef051a5829feb7e27a48031bed4e2f5f40f)

### 🛠 Breaking changes

- [expo-cli][xdl] Stop using api v1 endpoints for credentials ([#2422](https://github.com/expo/expo-cli/pull/2422) by [@wkozyra95](https://github.com/wkozyra95)).
- [expo-cli] Rename eas.json field: `buildCommand` -> `gradleCommand` ([#2432](https://github.com/expo/expo-cli/pull/2432) by [@dsokal](https://github.com/dsokal)).
- [expo-cli] Upgrade `@expo/build-tools` to `0.1.13` to change the default Gradle task (`:app:assembleRelease` -> `:app:bundleRelease`) for generic Android build.

### 🎉 New features

- [expo-cli] Implement auto-configuration for Android projects ([#2427](https://github.com/expo/expo-cli/pull/2427) by [@satya164](https://github.com/satya164)).
- [expo-cli] Make output of the `expo eas:build` command more readable ([#2428](https://github.com/expo/expo-cli/pull/2428) by [@wkozyra95](https://github.com/wkozyra95)).
- [expo-cli] Add `artifactPath` for generic iOS build profiles & set `app-bundle` as the default build type for managed Android builds ([#2435](https://github.com/expo/expo-cli/pull/2435) by [@dsokal](https://github.com/dsokal)).

### 🐛 Bug fixes

- [config] Fix generated orientation in AndroidManifest.xml ([#2431](https://github.com/expo/expo-cli/pull/2431) by [@barthap](https://github.com/barthap)).

### 📦 Packages updated

- @expo/config@3.2.18
- @expo/dev-server@0.1.20
- @expo/dev-tools@0.13.32
- @expo/electron-adapter@0.0.10
- expo-cli@3.24.0
- expo-optimize@0.1.42
- @expo/metro-config@0.1.20
- @expo/next-adapter@2.1.23
- expo-pwa@0.0.30
- uri-scheme@1.0.26
- @expo/webpack-config@0.12.23
- @expo/xdl@57.9.29

## [Tue Aug 4 11:44:18 2020 +0200](https://github.com/expo/expo-cli/commit/1110d7a2526d5c586c057aa1db7191011b6bb508)

### 🛠 Breaking changes

- Renamed commands for EAS Builds ([#2419](https://github.com/expo/expo-cli/pull/2419) by [@dsokal](https://github.com/dsokal)):
  - `expo build` -> `expo eas:build`
  - `expo build-status` -> `expo eas:build:status`

### 🎉 New features

- Reimplement bundling with Metro JS APIs (no file watching or HTTP servers), enabled in `expo publish` and `expo export` when `EXPO_USE_DEV_SERVER` is set to `true`. ([#2149](https://github.com/expo/expo-cli/pull/2149) by [@fson](https://github.com/fson)).
- Implement autoconfiguring bare iOS projects so they are buildable with EAS Builds. ([#2395](https://github.com/expo/expo-cli/pull/2395) by [@dsokal](https://github.com/dsokal)).

### 📦 Packages updated

- @expo/config@3.2.17
- @expo/configure-splash-screen@0.1.14
- @expo/dev-server@0.1.19
- @expo/dev-tools@0.13.30
- @expo/electron-adapter@0.0.9
- expo-cli@3.23.2
- expo-optimize@0.1.41
- @expo/metro-config@0.1.19
- @expo/next-adapter@2.1.22
- expo-pwa@0.0.29
- uri-scheme@1.0.25
- @expo/webpack-config@0.12.22
- @expo/xdl@57.9.27

## [Thu, 30 Jul 2020 13:42:33 -0700](https://github.com/expo/expo-cli/commit/5adda7a1af91bd05b299db8a342ef43e9035dd61)

### 🛠 Breaking changes

- Delete the deprecated `expo android` command ([#2215](https://github.com/expo/expo-cli/issues/2215))
- Delete deprecated `expo ios` command ([#2216](https://github.com/expo/expo-cli/issues/2216))

### 🎉 New features

- [xdl] Log output from Gradle Wrapper is a lot cleaner now. It doesn't print dots when the appropriate Gradle version is being downloaded ([#2355](https://github.com/expo/expo-cli/pull/2355)).
- [expo-cli] expo upload:android - Add better error messages when downloading archive file failed [#2384](https://github.com/expo/expo-cli/pull/2384).
- [expo-cli] perfomance improvment for operations on credentials (more efficient internal caching) [#2380](https://github.com/expo/expo-cli/pull/2380).
- [expo-cli] Add a command to get build status for turtle v2 builds

### 🐛 Bug fixes

- [configure-splash-screen] Bump cli-platform-[ios/android] versions for logkitty security fix
- [nextjs] Fix next.js adapter bug ([#2412](https://github.com/expo/expo-cli/issues/2412))
- [expo-cli] cleanup apple id credentials logic ([#2409](https://github.com/expo/expo-cli/issues/2409))
- [expo-cli] don't print function string in error message ([#2407](https://github.com/expo/expo-cli/issues/2407))
- [expo-cli] fix lint error
- [expo-cli]: IosApi handle properly missing credentials
- [expo-cli] base64 decode when saving p8 file ([#2404](https://github.com/expo/expo-cli/issues/2404))
- [expo-cli] revert PR #2404 and remove encoding from IosPushCredentials ([#2406](https://github.com/expo/expo-cli/issues/2406))
- [expo-cli] check `when` field when prompting in noninteractive mode ([#2393](https://github.com/expo/expo-cli/issues/2393))
- [xdl] Remove UpdateVersions from xdl ([#2387](https://github.com/expo/expo-cli/issues/2387))
- [xdl] Stop ADB daemon only when it was launched by xdl ([#2064](https://github.com/expo/expo-cli/issues/2064))
- [config] Implement "useNextNotificationsApi" configuration SDK 38 ([#2318](https://github.com/expo/expo-cli/issues/2318))
- [configure-splash-screen] fix a command instructions ([#2370](https://github.com/expo/expo-cli/issues/2370))
- [expo-cli] upload:android - add better error messages for issues with downloading archive file ([#2384](https://github.com/expo/expo-cli/issues/2384))
- [expo-cli] submission service: fix passing archive type from command line ([#2383](https://github.com/expo/expo-cli/issues/2383))
- [expo-cli] expo upload:android - fix help output - --latest is not default
- [xdl] Fix incorrect check of the packager port in the "setOptionsAsync" function. Fixes #2270
- [expo-cli] consolidate env variables. ([#2358](https://github.com/expo/expo-cli/issues/2358))

### 📦 Packages updated

- @expo/babel-preset-cli@0.2.17
- @expo/config@3.2.16
- @expo/configure-splash-screen@0.1.13
- @expo/dev-server@0.1.17
- @expo/dev-tools@0.13.28
- @expo/electron-adapter@0.0.8
- expo-cli@3.23.0
- expo-codemod@1.0.28
- expo-optimize@0.1.40
- @expo/image-utils@0.3.1
- @expo/json-file@8.2.22
- @expo/metro-config@0.1.17
- @expo/next-adapter@2.1.21
- @expo/osascript@2.0.23
- @expo/package-manager@0.0.30
- @expo/plist@0.0.9
- pod-install@0.1.9
- expo-pwa@0.0.28
- @expo/schemer@1.3.20
- uri-scheme@1.0.24
- @expo/webpack-config@0.12.21
- @expo/xdl@57.9.25

## [Wed Jul 15 2020 05:42:45 GMT-0700](https://github.com/expo/expo-cli/commit/05a88e6a69a1c0ab78dcb9a523a35b4bba26c694)

### 🛠 Breaking changes

- [expo-cli] Prefer `--apple-id-password` flag to environment variable `EXPO_APPLE_PASSWORD` when both are set([#2280](https://github.com/expo/expo-cli/issues/2280)).
- [expo-cli] Use `EXPO_APPLE_PASSWORD` instead of `EXPO_APPLE_ID_PASSWORD`.

## [Tue, 14 Jul 2020 21:37:53 -0700](https://github.com/expo/expo-cli/commit/2607c01f75eae079dd7ce4a8295cc7f47921096c)

### 🐛 Bug fixes

- [xdl] fix analytics for expo start ([#2357](https://github.com/expo/expo-cli/issues/2357))
- [xdl] Update link to third party library docs

### 📦 Packages updated

- @expo/dev-tools@0.13.27
- expo-cli@3.22.3
- @expo/xdl@57.9.24

## [Thu, 9 Jul 2020 13:45:20 -0700](https://github.com/expo/expo-cli/commit/30981cf510b4f72b365751ca4d83f43ed13a6cdc)

### 🐛 Bug fixes

- [webpack-config] Interop assets like Metro bundler ([#2346](https://github.com/expo/expo-cli/issues/2346))

### 📦 Packages updated

- @expo/dev-tools@0.13.25
- @expo/electron-adapter@0.0.6
- expo-cli@3.22.1
- @expo/next-adapter@2.1.19
- @expo/webpack-config@0.12.19
- @expo/xdl@57.9.22

## [Tue, 7 Jul 2020 11:39:19 -0700](https://github.com/expo/expo-cli/commit/e6de6aae5c90f006bff7b89e55cd702103a177e8)

### 🎉 New features

- [expo-cli] print turtle v2 build logs url
- [cli] add owner support for push:android cmds ([#2330](https://github.com/expo/expo-cli/issues/2330))
- [expo-cli] give another attempt to enter apple id credentials if it fails authentication with Apple ([#2338](https://github.com/expo/expo-cli/issues/2338))
- Add owner field support to expo start ([#2329](https://github.com/expo/expo-cli/issues/2329))
- Updated webpack version ([#2336](https://github.com/expo/expo-cli/issues/2336))
- [expo-cli] implement webhooks v2 ([#2212](https://github.com/expo/expo-cli/issues/2212))
- Add e2e tests for `expo export` ([#2237](https://github.com/expo/expo-cli/issues/2237))
- [expo-cli] Combined ID prompts for build and eject ([#2313](https://github.com/expo/expo-cli/issues/2313))
- Upgraded copy-webpack-plugin ([#2334](https://github.com/expo/expo-cli/issues/2334))

### 🐛 Bug fixes

- fix(config): use basename to avoid mixed path separators from glob ([#2319](https://github.com/expo/expo-cli/issues/2319))
- [webpack-config] Remove yup validation ([#2335](https://github.com/expo/expo-cli/issues/2335))

### 📦 Packages updated

- @expo/config@3.2.15
- @expo/dev-server@0.1.16
- @expo/dev-tools@0.13.24
- @expo/electron-adapter@0.0.5
- expo-cli@3.22.0
- expo-optimize@0.1.38
- @expo/metro-config@0.1.16
- @expo/next-adapter@2.1.18
- expo-pwa@0.0.26
- uri-scheme@1.0.23
- @expo/webpack-config@0.12.18
- @expo/xdl@57.9.21

## [Fri Jun 26 11:37:33 2020 -0700](https://github.com/expo/expo-cli/commit/8a9d17f699c07747c8198d5670eb779006e9b961)

### 🐛 Bug fixes

- Fix bug in credential manager when the user specifies a push key manually and appleCtx is not intialized.
- Simplify findProjectRootAsync to not use getConfig and swallow its errors.
- Workaround for iOS eject entitlements step failing on Windows - try/catch and warn if it doesn't work.

### 📦 Packages updated

- expo-cli@3.21.13

## [Thu Jun 25 14:51:58 2020 -0700](https://github.com/expo/expo-cli/commit/9fcad4c28b250bcf5a7a8c3f91ef79c1420cdeee)

### 🐛 Bug fixes

- Fix `expo upgrade` in projects that use dynamic configuration

### 📦 Packages updated

- @expo/dev-tools@0.13.23
- expo-cli@3.21.12
- @expo/xdl@57.9.20

## [Thu Jun 25 13:06:44 2020 -0700](https://github.com/expo/expo-cli/commit/8a03a18faa1af8711947698bba94c227f6ece5ec)

### 🛠 Breaking changes

- Mark unused XDL functions as deprecated

### 🎉 New features

- Prompt for iOS bundle identifier on build
- Add allowBackup customization feature for android
- Make the tabs template use TypeScript
- Use sudo for CocoaPods installation in pod-install, as recommended by CocoaPods docs

### 🐛 Bug fixes

- Fix `expo credentials:manager` listing all credentials on android and respect owner field` ([#2311](https://github.com/expo/expo-cli/pull/2311) by [@wkozyra95](https://github.com/wkozyra95)).
- Fix client_log warning in SDK 38 apps

### 📦 Packages updated

- @expo/config@3.2.14
- @expo/dev-server@0.1.15
- @expo/dev-tools@0.13.22
- @expo/electron-adapter@0.0.4
- expo-cli@3.21.11
- expo-optimize@0.1.37
- @expo/metro-config@0.1.15
- @expo/next-adapter@2.1.17
- @expo/package-manager@0.0.29
- pod-install@0.1.8
- expo-pwa@0.0.25
- uri-scheme@1.0.22
- @expo/webpack-config@0.12.17
- @expo/xdl@57.9.19

## [Tue Jun 23 17:55:00 2020 -0700](https://github.com/expo/expo-cli/commit/4bc73721d5a46fcac35096a0e86a1ceaa333b459)

### 🎉 New features

- Configure expo-updates on expo init in bare projects.

### 🐛 Bug fixes

- Add ttf and otf to binary extensions to fix font in tabs project.
- Upgrade fastlane.
- Replace calls to /bin/cp and /bin/rm with their xplat equivalents in fs-extra in xdl's IosPlist.

### 📦 Packages updated

- @expo/config@3.2.13
- @expo/dev-server@0.1.14
- @expo/dev-tools@0.13.21
- @expo/electron-adapter@0.0.3
- expo-cli@3.21.10
- expo-optimize@0.1.36
- @expo/metro-config@0.1.14
- @expo/next-adapter@2.1.16
- expo-pwa@0.0.24
- uri-scheme@1.0.21
- @expo/webpack-config@0.12.16
- @expo/xdl@57.9.18

## [Fri Jun 19 11:46:02 2020 -0700](https://github.com/expo/expo-cli/commit/d983fade1414f674c7dfff1c853d3e82fd787207)

### 🎉 New features

- `expo install` now also uses `bundledNativeModules.json` on bare projects.

### 📦 Packages updated

- @expo/dev-tools@0.13.20
- expo-cli@3.21.9
- @expo/xdl@57.9.17

## [Fri Jun 19 10:36:25 2020 +0200](https://github.com/expo/expo-cli/commit/4bc7d72f46f33349a974bfb38f1ee325297a2c16)

### 🎉 New features

- `expo upload:android --use-submission-service` is now ensuring the project is registered on Expo Servers before submitting a build.

### 📦 Packages updated

- @expo/config@3.2.12
- @expo/dev-server@0.1.13
- @expo/dev-tools@0.13.19
- @expo/electron-adapter@0.0.2
- expo-cli@3.21.8
- expo-optimize@0.1.35
- @expo/metro-config@0.1.13
- @expo/next-adapter@2.1.15
- expo-pwa@0.0.23
- uri-scheme@1.0.20
- @expo/webpack-config@0.12.15
- @expo/xdl@57.9.16

## [Thu Jun 18 11:13:34 2020 +0300](https://github.com/expo/expo-cli/commit/d868f8e4340f40a39f8e3a0d3b0c63f0ed116544)

### 🎉 New features

- Add `EXPO_IMAGE_UTILS_NO_SHARP` environment variable: it can be used to disable `sharp-cli` for image processing. ([#2269](https://github.com/expo/expo-cli/pull/2269) by [@EvanBacon](https://github.com/EvanBacon)).

### 🐛 Bug fixes

- Fix `expo build:android` throwing `_joi(...).default.strict is not a function` ([#2277](https://github.com/expo/expo-cli/issues/2277) by [@byCedric](https://github.com/byCedric)).
- Replace `newestSdkVersionAsync` with `newestReleasedSdkVersionAsync` ([#2266](https://github.com/expo/expo-cli/pull/2266) by [@cruzach](https://github.com/cruzach)).
- Use default `splash.resizeMode` on web ([#2268](https://github.com/expo/expo-cli/pull/2268) by [@EvanBacon](https://github.com/EvanBacon)).

### 📦 Packages updated

- @expo/config@3.2.11
- @expo/dev-server@0.1.12
- @expo/dev-tools@0.13.18
- @expo/electron-adapter@0.0.1
- expo-cli@3.21.7
- expo-optimize@0.1.34
- @expo/image-utils@0.3.0
- @expo/metro-config@0.1.12
- @expo/next-adapter@2.1.14
- expo-pwa@0.0.22
- uri-scheme@1.0.19
- @expo/webpack-config@0.12.14
- @expo/xdl@57.9.15

## [Mon Jun 15 14:40:35 2020 +0200](https://github.com/expo/expo-cli/commit/6b4992ca3bc4e23d32c5fc95110d3750c54dedfe)

### 🛠 Breaking changes

- Remove `opt-in-google-play-signing` command ([#2247](https://github.com/expo/expo-cli/pull/2247) by [@wkozyra95](https://github.com/wkozyra95)).
- Drop support for Node.js 13.x.x and 12.0.0-12.13.0 ([#2219](https://github.com/expo/expo-cli/pull/2219) by [@fson](https://github.com/fson)).

### 🎉 New features

- Allow providing a `postExport` hook ([#2227](https://github.com/expo/expo-cli/pull/2227) by [@vernondegoede](https://github.com/vernondegoede)).

### 🐛 Bug fixes

- Set EXPO_TARGET to correct value when starting dev server ([#2250](https://github.com/expo/expo-cli/pull/2250) by [esamelson](https://github.com/esamelson)).

### 📦 Packages updated

- @expo/config@3.2.10
- @expo/configure-splash-screen@0.1.12
- @expo/dev-server@0.1.11
- @expo/dev-tools@0.13.17
- @expo/electron-adapter@0.0.0
- expo-cli@3.21.6
- expo-optimize@0.1.33
- @expo/metro-config@0.1.11
- @expo/next-adapter@2.1.13
- @expo/package-manager@0.0.28
- pod-install@0.1.7
- expo-pwa@0.0.21
- uri-scheme@1.0.18
- @expo/webpack-config@0.12.13
- @expo/xdl@57.9.14

## [Thu Jun 4 10:01:50 2020 +0200](https://github.com/expo/expo-cli/commit/eb8409e9e18ea9c208a79f998596469b40145ca7)

### 🐛 Bug fixes

- Fix behavior of the `--skip-credentials-check` flag for `expo build:ios` ([#2213](https://github.com/expo/expo-cli/pull/2213) by [@quinlanj](https://github.com/quinlanj)).
- Fix buggy import of the `md5-file` package - caused issues with uploading submissions to AWS S3 - ([https://github.com/expo/expo-cli/commit/f875c67e1eb1614031715a9a645a8516e467f620](https://github.com/expo/expo-cli/commit/f875c67e1eb1614031715a9a645a8516e467f620) by [@dsokal](https://github.com/dsokal)).

### 📦 Packages updated

- expo-cli@3.21.5

## [Tue Jun 2 13:03:08 2020 +0200](https://github.com/expo/expo-cli/commit/39a705ade41e7fd6807ab05288ddeab7ca17138d)

### 📦 Packages updated

- @expo/config@3.2.9
- @expo/configure-splash-screen@0.1.10
- @expo/dev-server@0.1.10
- @expo/dev-tools@0.13.16
- @expo/electron-adapter@0.0.0-alpha.60
- expo-cli@3.21.4
- expo-optimize@0.1.32
- @expo/image-utils@0.2.29
- @expo/json-file@8.2.21
- @expo/metro-config@0.1.10
- @expo/next-adapter@2.1.12
- @expo/package-manager@0.0.27
- pod-install@0.1.6
- expo-pwa@0.0.20
- uri-scheme@1.0.17
- @expo/webpack-config@0.12.12
- @expo/xdl@57.9.13

## [Wed May 27 15:42:30 2020 +0300](https://github.com/expo/expo-cli/commit/eaff0bcc27a4a1221e54c453d98a0691af23792c)

### 📦 Packages updated

- @expo/configure-splash-screen@0.1.9
- @expo/dev-tools@0.13.15
- expo-cli@3.21.3
- @expo/xdl@57.9.12

## [Wed May 27 14:40:55 2020 +0300](https://github.com/expo/expo-cli/commit/e5c0a33bc95b222f9df36b5ba97061ddfe539555)

### 📦 Packages updated

- @expo/config@3.2.8
- @expo/dev-server@0.1.9
- @expo/dev-tools@0.13.14
- @expo/electron-adapter@0.0.0-alpha.59
- expo-cli@3.21.2
- expo-codemod@1.0.27
- expo-optimize@0.1.31
- @expo/json-file@8.2.20
- @expo/metro-config@0.1.9
- @expo/next-adapter@2.1.11
- @expo/package-manager@0.0.26
- pod-install@0.1.5
- expo-pwa@0.0.19
- @expo/schemer@1.3.19
- uri-scheme@1.0.16
- @expo/webpack-config@0.12.11
- @expo/xdl@57.9.11

## [Tue May 26 15:46:04 2020 +0200](https://github.com/expo/expo-cli/commit/f115be93ed1054bc09bdd8d2a4b4d6dfb6bf4e17)

### 📦 Packages updated

- expo-cli@3.21.1

## [Tue May 26 14:12:57 2020 +0200](https://github.com/expo/expo-cli/commit/ed5afaafe5388d5d6b6ae02cdf5c9984bae4bea0)

### 📦 Packages updated

- @expo/babel-preset-cli@0.2.16
- @expo/config@3.2.7
- @expo/configure-splash-screen@0.1.8
- @expo/dev-server@0.1.8
- @expo/dev-tools@0.13.13
- @expo/electron-adapter@0.0.0-alpha.58
- expo-cli@3.21.0
- expo-codemod@1.0.26
- expo-optimize@0.1.30
- @expo/image-utils@0.2.28
- @expo/json-file@8.2.19
- @expo/metro-config@0.1.8
- @expo/next-adapter@2.1.10
- @expo/osascript@2.0.22
- @expo/package-manager@0.0.25
- @expo/plist@0.0.8
- pod-install@0.1.4
- expo-pwa@0.0.18
- @expo/schemer@1.3.18
- uri-scheme@1.0.15
- @expo/webpack-config@0.12.10
- @expo/xdl@57.9.10

## [Fri May 15 16:55:55 2020 -0700](https://github.com/expo/expo-cli/commit/b17349f344e165f5ee386f07bae110d73eafefac)

### 📦 Packages updated

- @expo/dev-tools@0.13.12
- expo-cli@3.20.9
- @expo/xdl@57.9.9

## [Fri May 15 12:26:08 2020 -0700](https://github.com/expo/expo-cli/commit/03aa7e0f4ab2f53a29a540a58a7d3efda475eaca)

### 📦 Packages updated

- @expo/babel-preset-cli@0.2.15
- @expo/config@3.2.6
- @expo/configure-splash-screen@0.1.7
- @expo/dev-server@0.1.7
- @expo/dev-tools@0.13.11
- @expo/electron-adapter@0.0.0-alpha.57
- expo-cli@3.20.8
- expo-codemod@1.0.25
- expo-optimize@0.1.29
- @expo/image-utils@0.2.27
- @expo/json-file@8.2.18
- @expo/metro-config@0.1.7
- @expo/next-adapter@2.1.9
- @expo/osascript@2.0.21
- @expo/package-manager@0.0.24
- @expo/plist@0.0.7
- pod-install@0.1.3
- expo-pwa@0.0.17
- @expo/schemer@1.3.17
- uri-scheme@1.0.14
- @expo/webpack-config@0.12.9
- @expo/xdl@57.9.8

## [Thu May 14 22:34:45 2020 -0700](https://github.com/expo/expo-cli/commit/21770d9b7da6e591643be6bc52634a6232b5bea4)

### 📦 Packages updated

- @expo/babel-preset-cli@0.2.14
- @expo/config@3.2.5
- @expo/configure-splash-screen@0.1.6
- @expo/dev-server@0.1.6
- @expo/dev-tools@0.13.10
- @expo/electron-adapter@0.0.0-alpha.56
- expo-cli@3.20.7
- expo-codemod@1.0.24
- expo-optimize@0.1.28
- @expo/image-utils@0.2.26
- @expo/json-file@8.2.17
- @expo/metro-config@0.1.6
- @expo/next-adapter@2.1.8
- @expo/osascript@2.0.20
- @expo/package-manager@0.0.23
- @expo/plist@0.0.6
- pod-install@0.1.2
- expo-pwa@0.0.16
- @expo/schemer@1.3.16
- uri-scheme@1.0.13
- @expo/webpack-config@0.12.8
- @expo/xdl@57.9.7

## [Thu May 14 18:36:58 2020 -0700](https://github.com/expo/expo-cli/commit/ae467cf329a73dbec1e607f6b2a4f9fce5aa63db)

### 📦 Packages updated

- @expo/config@3.2.4
- @expo/configure-splash-screen@0.1.5
- @expo/dev-server@0.1.5
- @expo/dev-tools@0.13.9
- @expo/electron-adapter@0.0.0-alpha.55
- expo-cli@3.20.6
- expo-optimize@0.1.27
- @expo/image-utils@0.2.25
- @expo/json-file@8.2.16
- @expo/metro-config@0.1.5
- @expo/next-adapter@2.1.7
- @expo/osascript@2.0.19
- @expo/package-manager@0.0.22
- @expo/plist@0.0.5
- pod-install@0.1.1
- expo-pwa@0.0.15
- @expo/schemer@1.3.15
- uri-scheme@1.0.12
- @expo/webpack-config@0.12.7
- @expo/xdl@57.9.6

## [Tue May 12 16:09:06 2020 -0700](https://github.com/expo/expo-cli/commit/4b7d38ed4823c9d0cc70dc44cf271d1232fc27ef)

### 📦 Packages updated

- @expo/babel-preset-cli@0.2.13
- @expo/config@3.2.3
- @expo/configure-splash-screen@0.1.4
- @expo/dev-server@0.1.4
- @expo/dev-tools@0.13.8
- @expo/electron-adapter@0.0.0-alpha.54
- expo-cli@3.20.5
- expo-codemod@1.0.23
- expo-optimize@0.1.26
- @expo/image-utils@0.2.24
- @expo/json-file@8.2.15
- @expo/metro-config@0.1.4
- @expo/next-adapter@2.1.6
- @expo/osascript@2.0.18
- @expo/package-manager@0.0.21
- pod-install@0.1.0
- expo-pwa@0.0.14
- @expo/schemer@1.3.14
- uri-scheme@1.0.11
- @expo/webpack-config@0.12.6
- @expo/xdl@57.9.5

## [Mon May 11 13:22:29 2020 -0700](https://github.com/expo/expo-cli/commit/21334851c174e4283a0f1833fc09cc18623091ff)

### 📦 Packages updated

- @expo/babel-preset-cli@0.2.12
- @expo/config@3.2.2
- @expo/configure-splash-screen@0.1.3
- @expo/dev-server@0.1.3
- @expo/dev-tools@0.13.7
- @expo/electron-adapter@0.0.0-alpha.53
- expo-cli@3.20.4
- expo-codemod@1.0.22
- expo-optimize@0.1.25
- @expo/image-utils@0.2.23
- @expo/json-file@8.2.14
- @expo/metro-config@0.1.3
- @expo/next-adapter@2.1.5
- @expo/osascript@2.0.17
- @expo/package-manager@0.0.20
- pod-install@0.0.0-alpha.15
- expo-pwa@0.0.13
- @expo/schemer@1.3.13
- uri-scheme@1.0.10
- @expo/webpack-config@0.12.5
- @expo/xdl@57.9.4

## [Sat May 9 17:18:56 2020 -0700](https://github.com/expo/expo-cli/commit/21995b53c5d70f01ddae9f17c22b475aabfe0e93)

### 📦 Packages updated

- @expo/configure-splash-screen@0.1.2

## [Thu May 7 21:47:13 2020 -0700](https://github.com/expo/expo-cli/commit/000d0d28d3b8a5e4a83bb985d3132a837cbb985d)

### 📦 Packages updated

- @expo/dev-tools@0.13.6
- expo-cli@3.20.3
- @expo/xdl@57.9.3

## [Thu May 7 21:29:36 2020 -0700](https://github.com/expo/expo-cli/commit/4ef85a2a6a286db1dea6b931fa87bcae9de8acde)

### 📦 Packages updated

- @expo/config@3.2.1
- @expo/configure-splash-screen@0.1.1
- @expo/dev-server@0.1.2
- @expo/dev-tools@0.13.5
- @expo/electron-adapter@0.0.0-alpha.52
- expo-cli@3.20.2
- expo-optimize@0.1.24
- @expo/metro-config@0.1.2
- @expo/next-adapter@2.1.4
- @expo/package-manager@0.0.19
- pod-install@0.0.0-alpha.14
- expo-pwa@0.0.12
- uri-scheme@1.0.9
- @expo/webpack-config@0.12.4
- @expo/xdl@57.9.2

## [Thu Apr 30 18:45:00 2020 +0300](https://github.com/expo/expo-cli/commit/efa712a70ce470714129af085ff746eb7e4e323d)

### 🐛 Bug fixes

- Resolve and import metro-config from the project ([#2048](https://github.com/expo/expo-cli/pull/2048) by [@fson](https://github.com/fson)).
- Remove excessive warnings when session is logged out. ([#2053](https://github.com/expo/expo-cli/pull/2053) by [@jkhales](https://github.ciom/jkhales)).

  - @expo/dev-server@0.1.1
  - @expo/dev-tools@0.13.4
  - expo-cli@3.20.1
  - @expo/metro-config@0.1.1
  - @expo/xdl@57.9.1

## [Thu Apr 30 00:23:03 2020 +0300](https://github.com/expo/expo-cli/commit/945feb8b8f7228420e3b7e7918635721f81697f6)

- @expo/babel-preset-cli@0.2.11
- @expo/config@3.2.0
- @expo/dev-server@0.1.0
- @expo/dev-tools@0.13.3
- @expo/electron-adapter@0.0.0-alpha.51
- expo-cli@3.20.0
- expo-codemod@1.0.21
- expo-optimize@0.1.23
- @expo/image-utils@0.2.22
- @expo/json-file@8.2.13
- @expo/metro-config@0.1.0
- @expo/next-adapter@2.1.3
- @expo/osascript@2.0.16
- @expo/package-manager@0.0.18
- pod-install@0.0.0-alpha.13
- expo-pwa@0.0.11
- @expo/schemer@1.3.12
- uri-scheme@1.0.8
- @expo/webpack-config@0.12.3
- @expo/xdl@57.9.0

### 🛠 Breaking changes

- Remove `exp.json` support. Before this, `exp.json` had already been deprecated in favor of [`app.json` or `app.config.js`](https://docs.expo.io/workflow/configuration/). ([#2017](https://github.com/expo/expo-cli/pull/2017) by [@EvanBacon](https://github.com/EvanBacon)).

### 🎉 New features

- Suggest closest match to an unknown command . ([#2007](https://github.com/expo/expo-cli/pull/2007) by [@jamesgeorge007](jamesgeorge007)).
- Add validation for the `--platform` option in `expo apply`. ([#1981](https://github.com/expo/expo-cli/pull/1981) by [@EvanBacon](https://github.com/EvanBacon)).
- Print warning when running on untested newer versions of Node.js ([#1992](https://github.com/expo/expo-cli/pull/1992) by [@LinusU](https://github.com/LinusU))
- Clean up `Expo.plist` artifacts left behind by `expo publish` in a bare project. ([#2028](https://github.com/expo/expo-cli/pull/2028) by [@esamelson](https://github.com/esamelson))
- _Experimental_: add `@expo/dev-server`, a complete rewrite of the development server using Metro and `@react-native-community/cli-server-api`. The experimental dev server can be enabled in SDK 37 projects by setting `EXPO_USE_DEV_SERVER=true` in the environment. ([#1845](https://github.com/expo/expo-cli/pull/1845) by [@fson](https://github.com/fson))

### 🐛 Bug fixes

- Add necessary imports for onConfigurationChanged updates to MainActivity when ejecting. ([#2001](https://github.com/expo/expo-cli/pull/2001) by [@brentvatne](https://github.com/brentvatne)).
- Revert `workbox-webpack-plugin` update ([#2023](https://github.com/expo/expo-cli/pull/2023) by [@EvanBacon](https://github.com/EvanBacon)).

### 💎 Enhancements

- Improve macOS comment in `expo init` ([#2042](https://github.com/expo/expo-cli/issues/2042) by [@Anders-E](https://github.com/Anders-E))
- Add a better default email address in `expo client:ios`. ([#2029](https://github.com/expo/expo-cli/pull/2029) by [@EvanBacon](https://github.com/EvanBacon)).
- Update `expo whoami` and `expo logout` text ([#2019](https://github.com/expo/expo-cli/pull/2019) by [@EvanBacon](https://github.com/EvanBacon)).
- Fix typo in build output. ([#2006](https://github.com/expo/expo-cli/pull/2006) by [@BrodaNoel](https://github.com/BrodaNoel)).

### 🤷‍♂️ Chores

- Test `expo build:ios`. ([#1991](https://github.com/expo/expo-cli/pull/1991) and [#2011](https://github.com/expo/expo-cli/pull/2011) by [@quinlanj](https://github.com/quinlanj)).
- Improve readability of `asyncActionProjectDir`. ([#1989](https://github.com/expo/expo-cli/pull/1989) by [@EvanBacon](https://github.com/EvanBacon) and [@brentvatne](https://github.com/brentvatne)).
- Fetch configuration schemas from APIv2 endpoint. ([#1978](https://github.com/expo/expo-cli/pull/1978) by [@jkhales](https://github.com/jkhales)).
- Migrate to `cli-table3`. ([#2024](https://github.com/expo/expo-cli/pull/2024) by [@jamesgeorge007](https://github.com/jamesgeorge007)).
- Add docs for `uri-scheme`. ([#2026](https://github.com/expo/expo-cli/pull/2026) by [@EvanBacon](https://github.com/EvanBacon)).
- Use comments in the issue template. ([#2027](https://github.com/expo/expo-cli/pull/2027) by [@EvanBacon](https://github.com/EvanBacon)).
- Update `treekill`. ([#2027](https://github.com/expo/expo-cli/issues/2004) by [@brentvatne]).
- Remove `jest-message-utils` ([#2033](https://github.com/expo/expo-cli/issues/2033) by [@EvanBacon](https://github.com/EvanBacon)
- Make clean scripts platform independent ([#2043](https://github.com/expo/expo-cli/issues/2043) by [@Anders-E](https://github.com/Anders-E))

## [Sat Apr 25 16:26:28 2020 -0700](https://github.com/expo/expo-cli/commit/8a805d)

- @expo/babel-preset-cli@0.2.10
- @expo/config@3.1.4
- @expo/dev-tools@0.13.2
- @expo/electron-adapter@0.0.0-alpha.50
- expo-cli@3.19.2
- expo-codemod@1.0.20
- expo-optimize@0.1.22
- @expo/image-utils@0.2.21
- @expo/json-file@8.2.12
- @expo/metro-config@0.0.9
- @expo/next-adapter@2.1.2
- @expo/osascript@2.0.15
- @expo/package-manager@0.0.17
- pod-install@0.0.0-alpha.12
- expo-pwa@0.0.10
- @expo/schemer@1.3.11
- uri-scheme@1.0.7
- @expo/webpack-config@0.12.2
- @expo/xdl@57.8.32

### 🛠 Breaking changes

- Deprecate `expo ios` in favor of `expo start --ios` or pressing `i` in the terminal UI after running `expo start`. ([#1987](https://github.com/expo/expo-cli/pull/1987) by [@evanbacon](https://github.com/evanbacon))
- Deprecate `expo android` in favor of `expo start --android` or pressing `a` in the terminal UI after running `expo start`. ([#1987](https://github.com/expo/expo-cli/pull/1987) by [@evanbacon](https://github.com/evanbacon))

### 🐛 Bug fixes

- Fix bundling assets in bare apps that are using `expo-updates` and `expo export` for self hosting. ([#1999](https://github.com/expo/expo-cli/pull/1999) by [@brentvatne](https://github.com/brentvatne)).
- Use UIStatusBarStyleDefault in standalone apps unless otherwise specified. This fixes a longstanding issue where the status bar style is different between Expo client and standalone apps (https://github.com/expo/expo-cli/commit/474a56e863a16228a641c58f31f3f5c9f3c2d9e8 by [@brentvatne](https://github.com/brentvatne)).
- Fix support for owner field when checking credentials. ([#1942](https://github.com/expo/expo-cli/pull/1941) by [@quinlanj](https://github.com/quinlanj)).

### 🤷‍♂️ Chores

- Add notice about "damage simulator builds" on macOS Catalina (#[1944](https://github.com/expo/expo-cli/pull/1944) by [@byCedric](https://github.com/byCedric)).
- Better build errors when credentials aren't available in non-interactive mode ([#1928](https://github.com/expo/expo-cli/pull/1928) by [@quinlanj](https://github.com/quinlanj)).

## [Wed Apr 22 19:05:40 2020 -0700](https://github.com/expo/expo-cli/commit/3a0e79)

- @expo/babel-preset-cli@0.2.9
- @expo/config@3.1.3
- @expo/dev-tools@0.13.1
- @expo/electron-adapter@0.0.0-alpha.49
- expo-cli@3.19.1
- expo-codemod@1.0.19
- expo-optimize@0.1.21
- @expo/image-utils@0.2.20
- @expo/json-file@8.2.11
- @expo/metro-config@0.0.8
- @expo/next-adapter@2.1.1
- @expo/osascript@2.0.14
- @expo/package-manager@0.0.16
- @expo/plist@0.0.4
- pod-install@0.0.0-alpha.11
- expo-pwa@0.0.9
- @expo/schemer@1.3.10
- uri-scheme@1.0.6
- @expo/webpack-config@0.12.1
- @expo/xdl@57.8.31

### 🐛 Bug fixes

- Fix pasting service account JSON from finder (#1943)
- Add back sharp-cli version check back (#1907).
- Fix the open editor hotkey on Mac with osascript (#1899)
- Fix semver comparison in Node version compatibility check so an appropriate error is provided when using a Node version that is new and not yet supported.

### 🤷‍♂️ Chores

- Ignore mocks and tests in TypeScript builds (#1965)
- Remove the optimize command from expo-cli (#1930)
- Assorted improvements to build, testing, and coverage infra.

## [Tue Apr 21 10:52:42 2020 +0200](https://github.com/expo/expo-cli/commit/771a53)

- @expo/dev-tools@0.13.0
- @expo/electron-adapter@0.0.0-alpha.48
- expo-cli@3.19.0
- @expo/next-adapter@2.1.0
- @expo/webpack-config@0.12.0
- @expo/xdl@57.8.30

### 🐛 Bug fixes

- Assemble/bundle only the :app project on turtle (https://github.com/expo/expo-cli/pull/1937).

### 🤷‍♂️ Chores

- Added default name for projects if no name is given (#1923)
- Log message in `expo bundle-assets` if manifest is empty (#1912)
- Fallback on insecure HTTPS (#1940)

## [Mon Apr 20 14:52:56 2020 +0200](https://github.com/expo/expo-cli/commit/771a53)

- @expo/dev-tools@0.12.6
- expo-cli@3.18.7
- @expo/xdl@57.8.29

### 🤷‍♂️ Chores

- Remove call to check-dynamic-macros (https://github.com/expo/expo-cli/pull/1933).

## [Sat Apr 18 17:58:21 2020 -0700](https://github.com/expo/expo-cli/commit/4e6cfd)

- @expo/dev-tools@0.12.4
- @expo/electron-adapter@0.0.0-alpha.46
- expo-cli@3.18.5
- @expo/next-adapter@2.0.32
- expo-pwa@0.0.7
- uri-scheme@1.0.4
- @expo/webpack-config@0.11.24
- @expo/xdl@57.8.27

### 🐛 Bug fixes

- `expo start -c` will now properly clear cache as expected (https://github.com/expo/expo-cli/commit/48d67f).
- Fix keystore uploading with apiv2 (https://github.com/expo/expo-cli/commit/9fd163).

### 🤷‍♂️ Chores

- Create initial commit for project (https://github.com/expo/expo-cli/commit/22017c).
- Add useful information in uri-scheme when user does not have launchMode singleTask set (https://github.com/expo/expo-cli/commit/15899b).
- Support custom paths in uri-scheme (https://github.com/expo/expo-cli/commit/4d2dd7).

## [Fri Apr 17 11:20:10 2020 -0700](https://github.com/expo/expo-cli/commit/465333)

- @expo/dev-tools@0.12.3
- expo-cli@3.18.4
- @expo/xdl@57.8.26

### 🐛 Bug fixes

- Fix typo that was causing android keystore updates to fail (https://github.com/expo/expo-cli/pull/1909).

## [Fri Apr 17 10:02:10 2020 +0200](https://github.com/expo/expo-cli/commit/850be0)

- @expo/dev-tools@0.12.2
- expo-cli@3.18.3
- @expo/xdl@57.8.25

### 🐛 Bug fixes

- Do not override `google-services.json` contents since SDK 37 (https://github.com/expo/expo-cli/pull/1897).

## [Wed Apr 15 22:08:42 2020 -0700](https://github.com/expo/expo-cli/commit/c4eec5) and [Wed Apr 15 21:58:50 2020 -0700](https://github.com/expo/expo-cli/commit/c614c0)

- @expo/config@3.1.1
- @expo/dev-tools@0.12.1
- @expo/electron-adapter@0.0.0-alpha.45
- expo-cli@3.18.2
- expo-optimize@0.1.19
- @expo/metro-config@0.0.6
- @expo/next-adapter@2.0.31
- @expo/package-manager@0.0.14
- pod-install@0.0.0-alpha.9
- expo-pwa@0.0.6
- uri-scheme@1.0.3
- @expo/webpack-config@0.11.23
- @expo/xdl@57.8.24

### 🎉 New features

- Add offline support to Yarn PackageManager (https://github.com/expo/expo-cli/pull/1892).
- Return the given entry point as-is if it cannot be resolved using our helpers - this makes it easier to use `expo-updates` in certain monorepo setups (https://github.com/expo/expo-cli/commit/e076d56).

### 🐛 Bug fixes

- Temporarily revert build credentials to apiv1 in order to resolve issue with `owner` field not being respected on build (https://github.com/expo/expo-cli/commit/3b2f680).
- Handle Ctrl+C correctly in PowerShell/CMD (https://github.com/expo/expo-cli/pull/1749).

### 🤷‍♂️ Chores

- Better contextual error when a non-interactive build fails in a way that we cannot recover from without user intervention (https://github.com/expo/expo-cli/pull/1891).
- Better support for non-interactive mode in build - auto-select credentials when possible (https://github.com/expo/expo-cli/commit/c94638e).

## [Tue Apr 14 17:47:28 2020 -0700](https://github.com/expo/expo-cli/commit/5bc8404a0d03e0b419ba535501ea07927196ef6a)

### 📦 Packages updated

- @expo/config@3.1.0
- @expo/dev-tools@0.11.0
- @expo/electron-adapter@0.0.0-alpha.44
- expo-cli@3.18.0
- expo-optimize@0.1.18
- @expo/image-utils@0.2.19
- @expo/json-file@8.2.9
- @expo/metro-config@0.0.5
- @expo/next-adapter@2.0.30
- expo-pwa@0.0.5
- uri-scheme@1.0.2
- @expo/webpack-config@0.11.22
- @expo/xdl@57.8.22

### 🛠 Breaking changes

- `expo publish:rollback` now works more like what developers would intuitively expect - users who have already downloaded the bundle that is rolled back will also get rolled back (https://github.com/expo/expo-cli/pull/1707).

### 🎉 New features

- Explain to users on init of bare projects and eject that publishing is needed before creating a release build (https://github.com/expo/expo-cli/commit/3eb9e7ef50214394cca30869a031b384942d3d95).
- Created the `uri-scheme` package to easily interact with schemes on bare projects and test deep linking (https://github.com/expo/expo-cli/commit/3eb9e7ef50214394cca30869a031b384942d3d95).
- `expo build:ios` and `expo build:android` now prompt you to pick a build type in order to make the options more discoverable (https://github.com/expo/expo-cli/pull/1479).
- Added a shortcut to open your editor via expo-cli with the `o` hotkey (https://github.com/expo/expo-cli/pull/1879).

### 🐛 Bug fixes

- Fix Android scheme configuration that is applied on eject (https://github.com/expo/expo/issues/7816).
- Stop adb on Windows when shutting down expo-cli server (https://github.com/expo/expo-cli/pull/1876).
- Always properly terminate the bundle progress bar when completed (https://github.com/expo/expo-cli/pull/1877).

### 🤷‍♂️ Chores

- Replace request with axios due to deprecation of the request package and the mountain of warnings it produces (https://github.com/expo/expo-cli/pull/1809).
- Remove bootstrap from yarn start in the packages directory so it's quicker for collaborators working on expo-cli to get started (https://github.com/expo/expo-cli/pull/1869).
