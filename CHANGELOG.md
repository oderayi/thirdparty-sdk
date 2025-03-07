# Changelog: [mojaloop/thirdparty-sdk](https://github.com/mojaloop/thirdparty-sdk)
## [15.1.0](https://github.com/mojaloop/thirdparty-sdk/compare/v15.0.0...v15.1.0) (2022-06-24)


### Features

* add jws validation on inbound server and update reconfig for jws signing ([#151](https://github.com/mojaloop/thirdparty-sdk/issues/151)) ([bc19c32](https://github.com/mojaloop/thirdparty-sdk/commit/bc19c3291b0e55eca92abebead39b1d74a923c1d))


### Maintenance

* fix env variables ([#154](https://github.com/mojaloop/thirdparty-sdk/issues/154)) ([5505711](https://github.com/mojaloop/thirdparty-sdk/commit/550571138ec469a57cb71b6fd3a63dc4db7caf4c))

## [15.0.0](https://github.com/mojaloop/thirdparty-sdk/compare/v14.0.3...v15.0.0) (2022-06-22)


### ⚠ BREAKING CHANGES

* add ws client to pull updated configuration (#147)

### Features

* add ws client to pull updated configuration ([#147](https://github.com/mojaloop/thirdparty-sdk/issues/147)) ([6e2e2a8](https://github.com/mojaloop/thirdparty-sdk/commit/6e2e2a84b71aa7673552a876ecd65682a2f80241))


### Maintenance

* bump dependencies ([#148](https://github.com/mojaloop/thirdparty-sdk/issues/148)) ([a3ef539](https://github.com/mojaloop/thirdparty-sdk/commit/a3ef5393b9b5db0a46840eca86bb4f0dce04109b))
* dep update ([#149](https://github.com/mojaloop/thirdparty-sdk/issues/149)) ([ab527d8](https://github.com/mojaloop/thirdparty-sdk/commit/ab527d80bdfe2048222cfc80103b03e98c491917))
* remove expose ([94cdebb](https://github.com/mojaloop/thirdparty-sdk/commit/94cdebb122b24963a8a098b0b8fcc85e21aba14b))
* update dep and audit ([#152](https://github.com/mojaloop/thirdparty-sdk/issues/152)) ([e78a430](https://github.com/mojaloop/thirdparty-sdk/commit/e78a430e28e1e7383d1c608df526903c24da7b07))

### [14.0.3](https://github.com/mojaloop/thirdparty-sdk/compare/v14.0.2...v14.0.3) (2022-05-31)


### Code Refactor

* refactor config to handle diff inbound/outbound certs ([#146](https://github.com/mojaloop/thirdparty-sdk/issues/146)) ([4649743](https://github.com/mojaloop/thirdparty-sdk/commit/4649743ddb0f8f07bc70f683a960635a35194aa9))

### [14.0.2](https://github.com/mojaloop/thirdparty-sdk/compare/v14.0.1...v14.0.2) (2022-05-24)


### Maintenance

* fix publish job and update packages ([#145](https://github.com/mojaloop/thirdparty-sdk/issues/145)) ([808afd1](https://github.com/mojaloop/thirdparty-sdk/commit/808afd196d852750e0ee61ba6ccbddee4c8975fd))

### [14.0.1](https://github.com/mojaloop/thirdparty-sdk/compare/v14.0.0...v14.0.1) (2022-05-23)


### Maintenance

* conform linting config to typescript-svc-template ([#143](https://github.com/mojaloop/thirdparty-sdk/issues/143)) ([49189c8](https://github.com/mojaloop/thirdparty-sdk/commit/49189c8efb8c0b85cbaa3d4975e72a4bf293d2c4))

## [14.0.0](https://github.com/mojaloop/thirdparty-sdk/compare/v13.0.0...v14.0.0) (2022-05-20)


### ⚠ BREAKING CHANGES

* update nodejs to lts (#142)

### Features

* update nodejs to lts ([#142](https://github.com/mojaloop/thirdparty-sdk/issues/142)) ([f2a352c](https://github.com/mojaloop/thirdparty-sdk/commit/f2a352c563271efb450b5cfa47d6a241c35b627d))


### Maintenance

* remove sonar from build process ([#144](https://github.com/mojaloop/thirdparty-sdk/issues/144)) ([14f9c5b](https://github.com/mojaloop/thirdparty-sdk/commit/14f9c5b559b73cb0d70d7b70cf53c037f777501a))

## [13.0.0](https://github.com/mojaloop/thirdparty-sdk/compare/v12.0.2...v13.0.0) (2022-05-12)


### ⚠ BREAKING CHANGES

* update sdk-scheme-adapter dependency (#141)

### Code Refactor

* update sdk-scheme-adapter dependency ([#141](https://github.com/mojaloop/thirdparty-sdk/issues/141)) ([cccfd0b](https://github.com/mojaloop/thirdparty-sdk/commit/cccfd0b489d496c219b2d0f34d60a961cb26c9db))

### [12.0.2](https://github.com/mojaloop/thirdparty-sdk/compare/v12.0.1...v12.0.2) (2022-03-31)


### Maintenance

* fix spelling mistake ([#137](https://github.com/mojaloop/thirdparty-sdk/issues/137)) ([9892cae](https://github.com/mojaloop/thirdparty-sdk/commit/9892cae514bfc55fe2f173293239849fd11449c8))

### [12.0.1](https://github.com/mojaloop/thirdparty-sdk/compare/v12.0.0...v12.0.1) (2022-03-28)


### Maintenance

* bump packages with ncu -u -t minor ([#136](https://github.com/mojaloop/thirdparty-sdk/issues/136)) ([b1ada38](https://github.com/mojaloop/thirdparty-sdk/commit/b1ada386f848348420af4a2c0c96044844a7c193))
* **deps:** bump tmpl from 1.0.4 to 1.0.5 ([#129](https://github.com/mojaloop/thirdparty-sdk/issues/129)) ([bb65929](https://github.com/mojaloop/thirdparty-sdk/commit/bb659297ddb74df66788ac837c0fcd2d4d989aed))

## [12.0.0](https://github.com/mojaloop/thirdparty-sdk/compare/v11.55.1...v12.0.0) (2022-03-23)


### ⚠ BREAKING CHANGES

* update sdk to use thirdparty api v1.0 (#135)

### Features

* **mojaloop/project#1814:** compile ts to js for production ([#127](https://github.com/mojaloop/thirdparty-sdk/issues/127)) ([e0f3488](https://github.com/mojaloop/thirdparty-sdk/commit/e0f3488381e50f102216ba030712da7d8f062629)), closes [mojaloop/project#1814](https://github.com/mojaloop/project/issues/1814)


### Code Refactor

* update sdk to use thirdparty api v1.0 ([#135](https://github.com/mojaloop/thirdparty-sdk/issues/135)) ([f09d1f9](https://github.com/mojaloop/thirdparty-sdk/commit/f09d1f9e4fd0b7611be304ae46c1558dc2b56461))

### [11.55.1](https://github.com/mojaloop/thirdparty-sdk/compare/v11.55.0...v11.55.1) (2021-10-14)


### Bug Fixes

* **vulns:** run npm audit, fix and ignore unfixable low and a moderate for 1 month ([#126](https://github.com/mojaloop/thirdparty-sdk/issues/126)) ([49f2479](https://github.com/mojaloop/thirdparty-sdk/commit/49f247955bd3b81351954bf440d4f8a11612629e))


### Code Refactor

* rename thirdparty-scheme-adapter to thirdparty-sdk ([#125](https://github.com/mojaloop/thirdparty-sdk/issues/125)) ([3a5eec9](https://github.com/mojaloop/thirdparty-sdk/commit/3a5eec92d74f8ca292889a325f1e12fe08d58226))

## [11.55.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.54.0...v11.55.0) (2021-09-17)


### Features

* **test:** deterministic challenge ([#124](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/124)) ([ea594bf](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/ea594bfb74437eb83e1ea28ef77b091745e5388b))

## [11.54.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.53.0...v11.54.0) (2021-09-17)


### Features

* **linkingModel:** deterministic test consentids ([#123](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/123)) ([4be2f72](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/4be2f727c4271796a853317aece46ead54785bdf))

## [11.53.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.52.0...v11.53.0) (2021-09-09)


### Features

* **dfsp-transaction:** add challenge deriviation, fee summarizing functions ([#122](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/122)) ([7becdfe](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/7becdfefa0cae7a9c52cba93c0a261810f118a29))

## [11.52.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.51.0...v11.52.0) (2021-09-07)


### Features

* **integration:** add small helper library to look up historical requests from the ttk ([a9db17e](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/a9db17e3ab74e37d729d4cb6c4262320e466e370))

## [11.51.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.50.0...v11.51.0) (2021-09-07)


### Features

* **dfsp-tx:** use auth-service to verify a transaction ([#121](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/121)) ([f69f226](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/f69f226b84f7d3d33bb141560db0fd711e9e3545))

## [11.50.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.49.0...v11.50.0) (2021-09-06)


### Features

* **puml:** update the PISP Transaction sequence to use `/tpr/verifications` calls ([#120](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/120)) ([e1fec7f](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/e1fec7f35e059d79b1cbd4697eb535b43eac0553))

## [11.49.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.48.0...v11.49.0) (2021-08-31)


### Features

* **pisp-transaction:** handle outbound put authorization ([#119](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/119)) ([7d6e6d8](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/7d6e6d89b9066e25acfd7ed68e2b9ab754189ef6))

## [11.48.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.47.0...v11.48.0) (2021-08-30)


### Features

* **inbound-api:**  handle inbound post tpr authorizations ([#118](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/118)) ([0c828b0](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/0c828b03923e298a5b01dff055bc04b3edb0df09))

## [11.47.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.46.1...v11.47.0) (2021-08-30)


### Features

* **dfsp-tx:** replace sdk-scheme-adapter call with `/tpr/authorizations` ([#117](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/117)) ([f374196](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/f374196b30df75d2b4056519e9824ae2ba472890))

### [11.46.1](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.46.0...v11.46.1) (2021-08-27)


### Maintenance

* update api-snippets, regenerate and fix schema ([#116](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/116)) ([b6ece59](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/b6ece593ee9f09539590ef3e2edf1e8663823760))

## [11.46.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.45.0...v11.46.0) (2021-08-27)


### Features

* **docs:** update e2e sequences ([#115](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/115)) ([e4f6ad6](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/e4f6ad6608ffa7f81a03bc1a6f7e345a16cd06ab))

## [11.45.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.44.0...v11.45.0) (2021-08-26)


### Features

* **dfsp-transaction:** get consent context ([#114](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/114)) ([29e9d69](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/29e9d693a2b122977892b2988e3dfad3a6172d1d))

## [11.44.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.43.0...v11.44.0) (2021-08-24)


### Features

* **backend-requests:** store consent request id with consent ([#113](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/113)) ([0393cbe](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/0393cbe24ea5854f32a55bc35eef160998a23cfa))

## [11.43.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.42.0...v11.43.0) (2021-08-23)


### Features

* add req in account linking so DFSP can store consent details ([#112](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/112)) ([1b0c45d](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/1b0c45dd1bc13475d795c1676e9efa9a86396cb8))

## [11.42.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.41.1...v11.42.0) (2021-08-05)


### Features

* **outbound:** update the outbound interface ([#110](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/110)) ([fa999f3](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/fa999f32181319eab2d58d62344353fdd7ffdfe5))

### [11.41.1](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.41.0...v11.41.1) (2021-08-03)


### Bug Fixes

* **puml:** missing some payloads, change consentRequestId to valid uuid ([#109](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/109)) ([f7cbd19](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/f7cbd199f2f7b2f45407a87cec7bcfd058cfeac9))

## [11.41.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.40.0...v11.41.0) (2021-07-28)


### Features

* add consentId override and allow pisp to specify scope actions ([#108](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/108)) ([9caff2e](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/9caff2efd35cc52ebb24c288c201d100ba0825e6))

## [11.40.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.39.2...v11.40.0) (2021-07-07)


### Features

* **quotes:** add temporary config to workaround quotes `partyIdType` issue ([#106](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/106)) ([a71a46c](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/a71a46c0e8b677a3b4fe6b44c9882fac730a11ba))

### [11.39.2](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.39.1...v11.39.2) (2021-06-23)


### Maintenance

* **deps:** update dependencies to be able to handle longer clientDataJSON and attestation objects ([#105](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/105)) ([9d59171](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/9d591719875c2063fd80b801b0845c5a06b72fa2))

### [11.39.1](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.39.0...v11.39.1) (2021-06-16)


### Tests

* add robust DFSP side integration tests ([#102](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/102)) ([9dc88b6](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/9dc88b62be63d7d564e58c22463954a9260f7095))

## [11.39.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.38.0...v11.39.0) (2021-06-04)


### Features

* add credential phase handling for DFSP Linking model ([#101](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/101)) ([4b624ce](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/4b624ce0d5d0e8f9f1b2d5e28f346c58743b5f88))

## [11.38.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.37.5...v11.38.0) (2021-05-28)


### Features

* complete PISP side of linking flow ([#100](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/100)) ([23877ab](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/23877abb84eeca30921ed5e4bbeb6a73611d95bd))

### [11.37.5](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.37.4...v11.37.5) (2021-05-27)


### Maintenance

* add interface and types for credential registration phase ([#99](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/99)) ([9fb5071](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/9fb50712b759d53bba00be6b901df2ae9a5e7cbc))

### [11.37.4](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.37.3...v11.37.4) (2021-05-26)


### Code Refactor

* refactor old models into PISP and DFSP Linking Models ([#98](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/98)) ([6953389](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/6953389765a69b31f997639b2896e7fd2c5876f7))

### [11.37.3](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.37.2...v11.37.3) (2021-05-21)


### Maintenance

* **deps:** bump hosted-git-info from 2.8.8 to 2.8.9 ([#93](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/93)) ([fbe4c7d](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/fbe4c7d947746ae6d8220a9465d6b8e4d324c41c))

### [11.37.2](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.37.1...v11.37.2) (2021-05-19)


### Maintenance

* add config setup for services endpoint ([#97](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/97)) ([d6cb511](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/d6cb511fe8a40df90e2ccf3d7c8656db974c8807))

### [11.37.1](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.37.0...v11.37.1) (2021-05-18)


### Code Refactor

* PISP and DFSP Discovery flow, formally the Accounts flow ([#96](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/96)) ([3eaa937](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/3eaa937966659e8d6a01442c21b98ce3e13fe645))

## [11.37.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.36.1...v11.37.0) (2021-05-18)


### Features

* implement pisp prelinking flow ([#95](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/95)) ([244fc74](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/244fc74657711a1602a4d6ed2499157963b87950))

### [11.36.1](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.36.0...v11.36.1) (2021-05-14)


### Maintenance

* add inbound/outbound interfaces for pre-linking and bump dependencies ([#94](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/94)) ([b5f8f0c](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/b5f8f0c3e925caac3f0c1aa6861a4fa09a4fb745))

## [11.36.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.35.3...v11.36.0) (2021-05-11)


### Features

* **dfspTransaction:** workflow, errors, unit & integration tests ([#88](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/88)) ([80bca46](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/80bca46f0543e965abe9a8c86419a4bc02bb4aee))

### [11.35.3](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.35.2...v11.35.3) (2021-05-10)


### Documentation

* add endpoint to handle passing of credential and fix typos ([#91](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/91)) ([02ef1b1](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/02ef1b1b977aa4698cb7b8d4f1b251dc09328ea3))
* add more account linking error scenarios and doc fixes ([#89](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/89)) ([fd8510e](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/fd8510eea261c0704600b931dde8f67513dcf46b))


### Maintenance

* resolve vulnerabilties ([#92](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/92)) ([30b7b95](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/30b7b9592a312df52cebd2a981b0e9b0825955ef))

### [11.35.2](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.35.1...v11.35.2) (2021-04-26)


### Maintenance

* ignore vulnerabilities ([#90](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/90)) ([2ae6ca1](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/2ae6ca17b4fae250747c9948bbc4a725b43f0690))

### [11.35.1](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.35.0...v11.35.1) (2021-04-22)


### Documentation

* add happy path for PISPLinkingModel sequence diagram ([#87](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/87)) ([c2818b9](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/c2818b95769be333aa779f2169f50b75c4ea8655))

## [11.35.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.34.3...v11.35.0) (2021-04-22)


### Features

* 2108 dfsp transaction model ([#79](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/79)) ([272314f](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/272314f97d55f77e3d1a9d2f52a0bc5c35342ae0))

### [11.34.3](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.34.2...v11.34.3) (2021-04-16)


### Documentation

* add sequence diagram for pre-linking flow ([#84](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/84)) ([801e3f6](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/801e3f67a9c6df8d662e549e34e48df965de4ad7))

### [11.34.2](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.34.1...v11.34.2) (2021-04-15)


### Documentation

* add sequence digram for discovery flow ([#85](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/85)) ([e2fbfd0](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/e2fbfd0141583db750fc04bc9820766594151619))

### [11.34.1](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.34.0...v11.34.1) (2021-04-15)


### Maintenance

* update consentRequests simulator resp to support all error cases ([#86](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/86)) ([c81d681](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/c81d681dd490c2c15319ebe253fc3a4edfc977c2))

## [11.34.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.33.0...v11.34.0) (2021-04-14)


### Features

* implement consentRequests( post and put) endpoints ([#80](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/80)) ([a95d6d2](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/a95d6d2c74ebbfe4fbbb7b6f6d4e3acde503c753))

## [11.33.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.32.1...v11.33.0) (2021-04-06)


### Features

* 2060 hazard mitigation ([#77](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/77)) ([71a32ee](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/71a32ee213c7d4a25a87bce4a468f32a6b8f8ddd))

### [11.32.1](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.32.0...v11.32.1) (2021-04-06)

## [11.32.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.31.0...v11.32.0) (2021-04-02)


### Features

* update error codes for authentication step of account linking ([#78](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/78)) ([44e5dc3](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/44e5dc38bdaaf22da10d9bc0cdc73b5ca9b8c39e))

## [11.31.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.30.5...v11.31.0) (2021-04-01)


### Features

* add model and handler of outbound pisp otp validate ([#75](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/75)) ([443cb23](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/443cb23fcd22929f31d421baaa7dbbee65fbe70e))

### [11.30.5](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.30.4...v11.30.5) (2021-04-01)


### Code Refactor

* 2060 use deferredJob in PISPTransactionModel ([#76](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/76)) ([b7ac714](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/b7ac714843f745baf7d4069175b4260438720c11))

### [11.30.4](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.30.3...v11.30.4) (2021-03-30)


### Code Refactor

* 2060 pisp transaction model transaction request ([#74](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/74)) ([6a38727](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/6a387270fd46909af8bad5a43193eb8532a29d18))

### [11.30.3](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.30.2...v11.30.3) (2021-03-26)


### Bug Fixes

* correct getUserAccounts url in dfsp-backend-requests ([#73](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/73)) ([be86853](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/be8685362942439729dba44606cf9975057f295f))

### [11.30.2](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.30.1...v11.30.2) (2021-03-25)


### Code Refactor

* rework inbound DFSP otp validate workflow ([#72](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/72)) ([b98816b](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/b98816bd86a1cd773c5a09fcf19663bfb2b4182d))

### [11.30.1](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.30.0...v11.30.1) (2021-03-25)


### Bug Fixes

* move dependency and fix mocking in tests ([#70](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/70)) ([50087ad](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/50087adefb7d3a8bc6df1d4de8852eb5ea2828f6))

## [11.30.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.29.1...v11.30.0) (2021-03-25)


### Features

* use api-snippets for partyLookup endpoint ([#71](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/71)) ([4677e3e](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/4677e3e08da00175cd77f5706e8f6eb3c6202304))

### [11.29.1](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.29.0...v11.29.1) (2021-03-25)


### Maintenance

* introduce patch /consentRequests and update ttk spec ([#69](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/69)) ([42fcfc7](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/42fcfc7933eb59cc2fc421c961eb30871166ff3f))

## [11.29.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.28.2...v11.29.0) (2021-03-24)


### Features

* use api-snippets(thirdparty-api paths) instead of local defs ([#68](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/68)) ([47f9025](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/47f9025a313b5983811eb7698dc81af3eef07b12))

### [11.28.2](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.28.1...v11.28.2) (2021-03-18)


### Tests

* integration of requestPartiesInformation ([#65](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/65)) ([6a30687](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/6a30687a901894f2a21aba7d2b9b95ded252379c))

### [11.28.1](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.28.0...v11.28.1) (2021-03-17)


### Code Refactor

* 2060 remove notifyThirdpartyAboutTransfer  ([#64](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/64)) ([7edc9ad](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/7edc9ad3bb957f9da4c1ec9d2f2d257f88beb501))

## [11.28.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.27.1...v11.28.0) (2021-03-16)


### Features

* 2060 async2sync model ([#63](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/63)) ([101538b](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/101538b5eca6e2e36cd1c97524fe167d586f19f3))

### [11.27.1](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.27.0...v11.27.1) (2021-03-16)


### Bug Fixes

* unresolved promise warning in authorization model ([#62](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/62)) ([65209e8](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/65209e8016f17fbba14439b9dd2dddfdccf14f35))

## [11.27.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.26.0...v11.27.0) (2021-03-16)


### Features

* add initial inbound handlers for consent request flow ([#58](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/58)) ([0b2dd14](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/0b2dd1493e82fee023df1d88b11cefe4f70ff34a))

## [11.26.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.25.2...v11.26.0) (2021-03-15)


### Features

* 2060 separate backend requests and sdk requests ([#59](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/59)) ([57c5540](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/57c5540ab7b49c8ebb1ea6c0f53dd2237c8b1743)), closes [#51](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/51)

### [11.25.2](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.25.1...v11.25.2) (2021-03-15)


### Maintenance

* modify outbound accounts endpoint path ([#61](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/61)) ([7dbabd0](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/7dbabd0ef7e5a3000e103d472c2b238cfca4e07c))

### [11.25.1](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.25.0...v11.25.1) (2021-03-12)


### Maintenance

* add request headers to accounts endpoint ([#60](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/60)) ([b8b35b6](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/b8b35b693bd2b13ef0a45e884cdc1a4eaf673c6d))

## [11.25.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.24.3...v11.25.0) (2021-03-11)


### Features

* Add Inbound and Outbound accounts endpoints ([#56](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/56)) ([2aa08f7](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/2aa08f7891dadc1081152a26dca8c915558369e9))

### [11.24.3](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.24.2...v11.24.3) (2021-03-11)

### [11.24.2](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.24.1...v11.24.2) (2021-03-10)


### CI/CD

* add build-local dep to publish step ([#57](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/57)) ([a1e3aee](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/a1e3aee880f9e227a1f436db101fc883e9daeafa))

### [11.24.1](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.24.0...v11.24.1) (2021-03-09)


### Bug Fixes

* 2060 api templates generation warning and drop hello example endpoint ([#55](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/55)) ([eb1ed0f](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/eb1ed0fcc71c36f71d7a470149d109632483360d))

## [11.24.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.23.0...v11.24.0) (2021-03-09)


### Features

* Update Inbound & Outbound API defs and typescript definitions ([#52](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/52)) ([8235c3d](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/8235c3dcce02538d2f7104c37fefa19bfd771f0d))


### Maintenance

* disable circleci audit-licenses and license-scan ([#54](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/54)) ([57bd740](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/57bd7400674b77ec26ef6714c93329902438b952))

## [11.23.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.22.0...v11.23.0) (2021-03-08)


### Features

* defferedJob ([#53](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/53)) ([eb9daf8](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/eb9daf8e4140810a90e46e665ef7ab110e0f6629))

## [11.22.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.21.4...v11.22.0) (2021-02-22)


### Features

* introduce shared/http-request base class ([#49](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/49)) ([201591c](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/201591cfd1ebdd022d70e93c4d876ff6e6e59fcf))

### [11.21.4](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.21.3...v11.21.4) (2021-02-19)


### Maintenance

* 2060 latest docker images ([#48](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/48)) ([1bf15be](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/1bf15be5f85d1e30bdd930f158261e77af798f8b))

### [11.21.3](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.21.2...v11.21.3) (2021-02-19)


### Maintenance

* update license file ([#44](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/44)) ([68f8541](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/68f8541524686cec37a91c1413528aa5879f56c1))

### [11.21.2](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.21.1...v11.21.2) (2021-02-19)


### Maintenance

* update deps & audit-resolve ([#47](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/47)) ([2edafa9](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/2edafa966eb0e42cbbb0fb001f9c466e5af2b297))

### [11.21.1](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.21.0...v11.21.1) (2021-01-15)


### Maintenance

* 1942 update deps ([#46](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/46)) ([5d8aeac](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/5d8aeaceaf8b977223d690e5fe1e7b41ffa6e36c))

## [11.21.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.20.2...v11.21.0) (2020-10-24)


### Features

* work in tandem with sdk-scheme-adapter  ([#43](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/43)) ([4f711cd](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/4f711cd7c0041ad8ad2619fb0db4af6797dcb115))

### [11.20.2](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.20.0...v11.20.2) (2020-10-20)


### Bug Fixes

* bump bugfix version to see if that fixes the circleci cache ([4197b53](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/4197b53ef3c83246fb8022c1daef54724441c633))
* **quote:** remove empty quote `note` field, and make optional ([5583eef](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/5583eeffd2aeace741c6838f9ccbc153470e4f3f))
* **tests:** broken quote ids ([99004c3](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/99004c3d683db6db533c2a037260279d2554dcae))
* **tests:** broken quote ids ([4774ca1](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/4774ca161fa053ef43ffe55a11712439604dbd81))


### Maintenance

* remove .only ([63bf3be](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/63bf3be299b2f74e937f0f85dc8c922924193db8))

## [11.20.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.19.0...v11.20.0) (2020-10-13)


### Features

* **api-outbound:** add POST /authorizations integration test ([d5251a5](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/d5251a5c1fa4c34db8d4e7bb7a73e96a8586a089))
* **api-outbound:** add test outbound POST authorizations ([b3348bd](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/b3348bd8b2b4f523280a07891b4815aff3389a9b))
* **api-outbound:** change docker-compose for proper CICD running ([c985c41](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/c985c41c3302cbea6eb377fea7c80886f8627ba7))
* **docker:** setup docker config to run ([e6dead5](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/e6dead57f8b1e3f3a24c342c17436b37479ff17b))


### Bug Fixes

* **api-inbound:** add example for POST authorizations ([d10e332](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/d10e332fc7c80fdb21f1de2e6b72891ed9dd462f))
* **api-outbound:** add example for POST authorizations ([504da8b](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/504da8bbc766e57a726c91629e0fdef8867995e4))
* **circleci-config:** fix wait4 path ([b510803](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/b510803c461263975d321262c295b822599870ab))
* **circleci-config:** remove wait4 and apply review suggestions ([92f4de4](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/92f4de42e7074e7a59be00aca8976d6e2a2bc587))
* **integration-test:** change integration.json value for outboudn api integration test ([b7da0cd](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/b7da0cdfc5d61ddc4718583879e418d06f6b8e69))
* **outbound-api.test:** changes as per reviewer request ([cfdd4b6](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/cfdd4b65e7a584c1b82c3e4b9bc066fa1b92f9de))
* **package-update:** fix conflict on package ([73e3311](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/73e3311ad9d1affe488f39ead35303b7373dc5db))


### Documentation

* **readme:** update Quick Start steps ([a31eb1a](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/a31eb1a7af12c4293ae9a0b30419f88fb4417932))


### Tests

* **circleci-build:** test circleci build ([701c876](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/701c876a5afd62f5d0c2f1024dab7a2ca296c504))
* **circleci-build:** test circleci build with additional containers after core containers ([2effe23](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/2effe239d13b85ef3ecd1647e0b8f5fd678720ca))
* **circleci-build:** test circleci build with master version ([151358e](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/151358e26b0788969b5e58ac747ba6144d4f19e2))
* **circleci-build:** test circleci build with master version of wait4 config ([d9c6ae6](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/d9c6ae67d9bcf56f6c15b084224bd4002180d47d))
* **circleci-build:** test circleci config ([e234273](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/e234273f868fce5d041381f5ff1515d0098fba9b))
* **circleci-build:** test circleci config ([403d343](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/403d343f0e141d96ee1dfeb79c7f6331903c78f3))
* **circleci-build:** test circleci config ([aa2d9a6](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/aa2d9a6eef4036eeaa8c515d7a24fe6cb3245a8a))


### Maintenance

* **package:** update deps ([e93d9a2](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/e93d9a25b79415f5467f8761d50dadb113506a6f))
* **package-update:** update package.json ([6ac1ba5](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/6ac1ba544e4fec3dca6dfa6088aec2e5fc981552))
* **update-package:** update package ([bae4761](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/bae4761ea04c189a0622478cf82f8f12c2ae4e94))

## [11.19.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.18.0...v11.19.0) (2020-10-07)


### Features

* 1671 extend config to have all sdk standard components endpoints ([#40](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/40)) ([86d4ae3](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/86d4ae3d8ae0de8636a3bbb5ea5e2e4d9c91a4dc))

## [11.18.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.17.1...v11.18.0) (2020-10-05)


### Features

* **pips-transaction-request-model:** PISP-side state machine and handlers ([#38](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/38)) ([67093e6](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/67093e6f295aeead789ad522b73d151587ddf0af))

### [11.17.1](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.17.0...v11.17.1) (2020-09-30)


### Bug Fixes

* 1617 signchallenge uri ([#37](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/37)) ([47cff66](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/47cff66dbd7de087b8a0af1efaf991db3bd211e4))

## [11.17.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.16.0...v11.17.0) (2020-09-30)


### Features

* **docs:** first pass at new outbound api docs ([21e0879](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/21e0879a2f2ef6cca746570a3e2ed8413bf31693))
* **docs:** improved sequence diagram ([6dd35dd](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/6dd35dda13ee4853461f1d4aafa01c75ba9088c0))
* **docs:** render sequence diagrams ([11b87b1](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/11b87b15c2c8a187fc1623b1fefb6fec7c674a1c))


### Bug Fixes

* 1617 backend requests & update deps ([#36](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/36)) ([b2588fb](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/b2588fb24ef64b4327035e1917de97d55c623b26))

## [11.16.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.15.0...v11.16.0) (2020-09-18)


### Features

* 427 POST /authorization inbound handler ([#32](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/32)) ([8bb32cd](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/8bb32cd0063a8fce23b5f157f35722625c10540b))

## [11.15.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.14.0...v11.15.0) (2020-09-16)


### Features

* 427 post authorizations.model for inbound service ([#31](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/31)) ([a71f3cd](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/a71f3cd8bd50daf59b497835569d8f3c66f332b3))

## [11.14.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.13.0...v11.14.0) (2020-09-15)


### Features

* 427 add BackendRequests to shared state plugin ([#30](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/30)) ([6268451](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/6268451ae75b0df0b1865da78ba380751d7c882e))

## [11.13.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.12.0...v11.13.0) (2020-09-15)


### Features

* 427 throw exceptions on http non success ([#29](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/29)) ([a485ca0](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/a485ca0b7fb133a814159509456720bc4de1f5ed))

## [11.12.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.11.0...v11.12.0) (2020-09-14)


### Features

* 427 BackendRequests ([#28](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/28)) ([a54659f](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/a54659fd17e3a3757fab2eceb52f21a579b34d57))

## [11.11.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.10.0...v11.11.0) (2020-09-10)


### Features

* 348 inbound put handler & integration tests ([#27](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/27)) ([8eebf08](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/8eebf08b438ab5f877de1d1b3c077c073bff3503))

## [11.10.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.9.1...v11.10.0) (2020-09-08)


### Features

* **endpoints:** Thirdparty inbound and outbound authorizations ([#26](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/26)) ([5ed1c75](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/5ed1c757e4f271635a84d8a2866c29178d2bb320))

### [11.9.1](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.9.0...v11.9.1) (2020-09-07)


### Features

* 348 inbound put handler, unit tests ([#25](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/25)) ([c7f2430](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/c7f2430abbca8fe4a60773fe368a9e00369c5b82))

## [11.9.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.8.0...v11.9.0) (2020-09-07)


### Features

* 348 authorization post handler ([#24](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/24)) ([ca78e65](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/ca78e6525d957d7d3d75d31b9f73c330aae5b729))

## [11.8.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.7.0...v11.8.0) (2020-09-02)


### Features

* **state-plugin:** 423 getWSO2Auth ([#23](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/23)) ([56fef96](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/56fef963047eaa26856b6349c516246c0e635b03))

## [11.7.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.6.0...v11.7.0) (2020-09-02)


### Features

* 423 state plugin ([#22](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/22)) ([2bebf01](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/2bebf01300d6f460548f8a1a3d16f32d85a31d84))

## [11.6.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.5.0...v11.6.0) (2020-09-01)


### Features

* authorization outbound model ([#20](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/20)) ([985ac41](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/985ac41f2f2dec84dde44db28865584298ee5313))


### Tests

* tmp. exclude interface types from coverage ([#21](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/21)) ([d1490ac](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/d1490ac8e0639f1eec20792fc007e41c60477a18))

## [11.5.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.4.4...v11.5.0) (2020-08-31)


### Features

* add inbound POST thirdpartyRequests/transaction handling ([#19](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/19)) ([9e9ab97](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/9e9ab9768fb710e5dce7dc021a99c9484d134b72))

### [11.4.4](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.4.3...v11.4.4) (2020-08-27)


### CI/CD

* use GITHUB_TOKEN and setup mojaloopci user with Mantain access ([1f76c94](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/1f76c94775a726ff17f082d5375a156a0bba6fc4))

### [11.4.3](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.4.2...v11.4.3) (2020-08-27)


### CI/CD

* use GITHUB_RELEASE_TOKEN ([242d1fb](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/242d1fbd3ed2d27317446bf0a1ebb6c3c5b32800))

### [11.4.2](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.4.1...v11.4.2) (2020-08-27)


### CI/CD

* release command generates commit witch doesn't trigger build ([c3302cb](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/c3302cbf7e444e917961ea3816f0cc1973cb88e4))

### [11.4.1](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.4.0...v11.4.1) (2020-08-27)

## [11.4.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.3.0...v11.4.0) (2020-08-27)


### Features

* automated releasing ([#18](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/18)) ([959a342](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/959a342f33f89f0a1d659e57ac9f36f42f894aa6))


### Maintenance

* **package:** setup update policy for audit related dependencies ([213d7ac](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/213d7ac15dfe5441e2a036baec7c1fb7f99aecab))


### CI/CD

* disable image-scan ([635ad2a](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/635ad2af9700bafb425801fb6888fd473ac66fc5))
* fix image-scan ([c95c4bc](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/c95c4bcfedeb6af73a39bae3fd7b1f57314d311a))
* prune --production ([a727fb4](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/a727fb4afb8b08c3aa9e4e19352e4d8f6bd6d3e4))

## [11.3.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.2.0...v11.3.0) (2020-08-26)


### Features

* PersistentModel ([#16](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/16)) ([de44a41](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/de44a418130cd69ad40c827f6b59427c833e1848))


### Maintenance

* **package:** update dependencies ([#17](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/17)) ([272bc52](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/272bc5206cecb8a004cc9d4d61c3af80f554c095))

## [11.2.0](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.1.1...v11.2.0) (2020-08-26)


### Features

* add env variables needed for MojaloopRequests ([aa33204](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/aa332047e9953e3cb37066c415c2de7191fc2a50))
* KVS & PubSub integration tests ([#15](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/15)) ([add5d79](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/add5d79e69af72ecb726a1ddd11f4550737e1ae3))

### [11.1.1](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.1.0...v11.1.1) (2020-08-21)

## 11.1.0 (2020-08-20)


### Features

* RedisConnection & KVS & PubSub ([#12](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/12)) ([1f847b5](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/1f847b508eee4b77235f673ef621cd9456e04339))


### Code Refactor

* move handlers out from server folder ([#9](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/9)) ([dfadd43](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/dfadd43c6d78b7b3a96094274593c7d829ec6ca1))


### Maintenance

* **package:** update dependencies ([#11](https://github.com/mojaloop/thirdparty-scheme-adapter/issues/11)) ([a5ade13](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/a5ade13a463c656c8df35ae648ce66b61ac23084))

### [11.0.5](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.0.4...v11.0.5) (2020-08-14)


### Bug Fixes

* linting smells ([92af96e](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/92af96e7aa2aeb8b87cf5a3a845bfd5b8479897c))

### [11.0.4](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.0.3...v11.0.4) (2020-08-14)

### [11.0.3](https://github.com/mojaloop/thirdparty-scheme-adapter/compare/v11.0.2...v11.0.3) (2020-08-14)

### 11.0.2 (2020-08-14)


### Maintenance

* **package:** fix pre-push hook ([29953b1](https://github.com/mojaloop/thirdparty-scheme-adapter/commit/29953b1d8a182e65e6cbad37aafd26484f8574b3))
