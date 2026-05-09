# Changelog

## 1.4.1 (2026-05-09)

Full Changelog: [v1.4.0...v1.4.1](https://github.com/uapiq/usdk-python/compare/v1.4.0...v1.4.1)

### Bug Fixes

* **client:** add missing f-string prefix in file type error message ([03cc7e8](https://github.com/uapiq/usdk-python/commit/03cc7e86fc4efe3e8e1fcfea5335a6a3ae2348b7))


### Chores

* **internal:** reformat pyproject.toml ([86bbc7a](https://github.com/uapiq/usdk-python/commit/86bbc7a1107c1b5350ea2b0a12a23e39a6ecab2c))

## 1.4.0 (2026-04-28)

Full Changelog: [v1.3.2...v1.4.0](https://github.com/uapiq/usdk-python/compare/v1.3.2...v1.4.0)

### Features

* support setting headers via env ([45263d9](https://github.com/uapiq/usdk-python/commit/45263d9b85671f894e13b857e743f277fbb94e4f))


### Bug Fixes

* use correct field name format for multipart file arrays ([7735773](https://github.com/uapiq/usdk-python/commit/77357734428d6457f6b31c58b2c27c12480b272e))


### Performance Improvements

* **client:** optimize file structure copying in multipart requests ([36b0819](https://github.com/uapiq/usdk-python/commit/36b0819ef2f66872cef9457881f14b19f62f6053))


### Chores

* **internal:** more robust bootstrap script ([e7c06ad](https://github.com/uapiq/usdk-python/commit/e7c06ad8b2b200c0d195b3361df773b8d0c943db))

## 1.3.2 (2026-04-11)

Full Changelog: [v1.3.1...v1.3.2](https://github.com/uapiq/usdk-python/compare/v1.3.1...v1.3.2)

### Bug Fixes

* ensure file data are only sent as 1 parameter ([a8b2480](https://github.com/uapiq/usdk-python/commit/a8b24803f15f722cf39f9318037fde6c903fca1b))

## 1.3.1 (2026-04-08)

Full Changelog: [v1.3.0...v1.3.1](https://github.com/uapiq/usdk-python/compare/v1.3.0...v1.3.1)

### Bug Fixes

* **client:** preserve hardcoded query params when merging with user params ([caedfd5](https://github.com/uapiq/usdk-python/commit/caedfd5af8017be6518dc30fdd56e51d008ae59e))

## 1.3.0 (2026-03-27)

Full Changelog: [v1.2.3...v1.3.0](https://github.com/uapiq/usdk-python/compare/v1.2.3...v1.3.0)

### Features

* **internal:** implement indices array format for query and form serialization ([4866e03](https://github.com/uapiq/usdk-python/commit/4866e0306cbf50bbfcb8d7cf00dfaeb68a65282e))


### Chores

* **ci:** skip lint on metadata-only changes ([32bccee](https://github.com/uapiq/usdk-python/commit/32bccee63c93e4ac25378ad642a84d78582935cc))
* **internal:** update gitignore ([7dd198a](https://github.com/uapiq/usdk-python/commit/7dd198aa1e98ddb60bfb68477703c57b23592476))

## 1.2.3 (2026-03-20)

Full Changelog: [v1.2.2...v1.2.3](https://github.com/uapiq/usdk-python/compare/v1.2.2...v1.2.3)

### Bug Fixes

* sanitize endpoint path params ([eb24949](https://github.com/uapiq/usdk-python/commit/eb249494e1db3dab7c628bd839a55b7080c6e933))


### Chores

* **internal:** tweak CI branches ([dbc4c5d](https://github.com/uapiq/usdk-python/commit/dbc4c5dbeb0681c2aabcf43f4af4ff27b151862a))

## 1.2.2 (2026-03-17)

Full Changelog: [v1.2.1...v1.2.2](https://github.com/uapiq/usdk-python/compare/v1.2.1...v1.2.2)

### Bug Fixes

* **deps:** bump minimum typing-extensions version ([aa600e8](https://github.com/uapiq/usdk-python/commit/aa600e8e0df9b47fd037fcb550ff793dc8bf3ef2))

## 1.2.1 (2026-03-17)

Full Changelog: [v1.2.0...v1.2.1](https://github.com/uapiq/usdk-python/compare/v1.2.0...v1.2.1)

### Bug Fixes

* **pydantic:** do not pass `by_alias` unless set ([0c4bc69](https://github.com/uapiq/usdk-python/commit/0c4bc694f630bb118a7a01d58657f7b12139da5e))


### Chores

* **ci:** skip uploading artifacts on stainless-internal branches ([d043f0e](https://github.com/uapiq/usdk-python/commit/d043f0ebff27af77f7302f2de46fb7d949bfc7c1))
* format all `api.md` files ([a4cb590](https://github.com/uapiq/usdk-python/commit/a4cb590fd4c14133096f270ed7972644ca762a0f))
* **internal:** add request options to SSE classes ([f20f689](https://github.com/uapiq/usdk-python/commit/f20f6898d03c9d053ec65a8ed9d4527d1498f153))
* **internal:** bump dependencies ([707fe17](https://github.com/uapiq/usdk-python/commit/707fe179cd956323743d188d3bc4652b7c8f4688))
* **internal:** fix lint error on Python 3.14 ([54f60cc](https://github.com/uapiq/usdk-python/commit/54f60ccf361cf9619ee55cf9d980803cce289ebb))
* **internal:** make `test_proxy_environment_variables` more resilient ([fd4d106](https://github.com/uapiq/usdk-python/commit/fd4d106283d4ad1289947d8a862c771daabac7ac))
* **internal:** make `test_proxy_environment_variables` more resilient to env ([5235fdf](https://github.com/uapiq/usdk-python/commit/5235fdf2bf9ae3e8b46e49d131a3269e533ca970))
* **internal:** remove mock server code ([c559627](https://github.com/uapiq/usdk-python/commit/c559627c518d7d5334a9dd453cbee094882fc147))
* update mock server docs ([8ff2dec](https://github.com/uapiq/usdk-python/commit/8ff2decd47b984c5bfe6d247f4c275b61e90669a))

## 1.2.0 (2026-01-30)

Full Changelog: [v1.1.0...v1.2.0](https://github.com/uapiq/usdk-python/compare/v1.1.0...v1.2.0)

### Features

* **client:** add custom JSON encoder for extended type support ([ebe2768](https://github.com/uapiq/usdk-python/commit/ebe276808878e876161cab33ac14b948035f6de4))


### Chores

* **ci:** upgrade `actions/github-script` ([e595ee6](https://github.com/uapiq/usdk-python/commit/e595ee6d76bcaf768667f6223d6c4a54c0c74f13))
* **internal:** update `actions/checkout` version ([ee48ba2](https://github.com/uapiq/usdk-python/commit/ee48ba2c27a046901741a065a4f4b666b0915542))

## 1.1.0 (2026-01-14)

Full Changelog: [v1.0.5...v1.1.0](https://github.com/uapiq/usdk-python/compare/v1.0.5...v1.1.0)

### Features

* **client:** add support for binary request streaming ([c77b22f](https://github.com/uapiq/usdk-python/commit/c77b22f30bc1a66b2b2803995321137658d4f207))


### Chores

* **internal:** add `--fix` argument to lint script ([b3bc81e](https://github.com/uapiq/usdk-python/commit/b3bc81eec1a682da3cec84fa4c99ce3beafc825c))
* **internal:** codegen related update ([5eea90f](https://github.com/uapiq/usdk-python/commit/5eea90fedb9f4206788f16d962afc042cd368b87))

## 1.0.5 (2025-12-18)

Full Changelog: [v1.0.4...v1.0.5](https://github.com/uapiq/usdk-python/compare/v1.0.4...v1.0.5)

### Bug Fixes

* use async_to_httpx_files in patch method ([efdf634](https://github.com/uapiq/usdk-python/commit/efdf634bee0018c7881bc6d76e52477b093a7a94))


### Chores

* **internal:** add missing files argument to base client ([c5e2b68](https://github.com/uapiq/usdk-python/commit/c5e2b68bfa1151f375a99dc758245db2611037fc))
* speedup initial import ([3f7c8d0](https://github.com/uapiq/usdk-python/commit/3f7c8d04e6375dabf92267c72c3b87a4e512de87))

## 1.0.4 (2025-12-09)

Full Changelog: [v1.0.3...v1.0.4](https://github.com/uapiq/usdk-python/compare/v1.0.3...v1.0.4)

### Bug Fixes

* **types:** allow pyright to infer TypedDict types within SequenceNotStr ([ed589b4](https://github.com/uapiq/usdk-python/commit/ed589b4a2c19dc2a65e3cd8ea580db45591b9e15))


### Chores

* **docs:** use environment variables for authentication in code snippets ([3bcaba8](https://github.com/uapiq/usdk-python/commit/3bcaba8716f021a5ed859145961f9ecb18afa2ab))
* update lockfile ([43e973d](https://github.com/uapiq/usdk-python/commit/43e973de48cf6ace9854b1339f5034bb8158d14c))

## 1.0.3 (2025-11-28)

Full Changelog: [v1.0.2...v1.0.3](https://github.com/uapiq/usdk-python/compare/v1.0.2...v1.0.3)

### Bug Fixes

* ensure streams are always closed ([782395e](https://github.com/uapiq/usdk-python/commit/782395e06f79b52a6b75a2e711917744c2ceeaa0))


### Chores

* add Python 3.14 classifier and testing ([c13ba77](https://github.com/uapiq/usdk-python/commit/c13ba7735dcbe87fb34124912121c5e0996dabeb))
* **deps:** mypy 1.18.1 has a regression, pin to 1.17 ([9831cab](https://github.com/uapiq/usdk-python/commit/9831cabd05a0b04721eb37bfd9c3eb927ed431a4))

## 1.0.2 (2025-11-12)

Full Changelog: [v1.0.1...v1.0.2](https://github.com/uapiq/usdk-python/compare/v1.0.1...v1.0.2)

### Bug Fixes

* **compat:** update signatures of `model_dump` and `model_dump_json` for Pydantic v1 ([e1a4d59](https://github.com/uapiq/usdk-python/commit/e1a4d59d6cbe1c4bf54b4db1c875685b46ecf46d))

## 1.0.1 (2025-11-11)

Full Changelog: [v1.0.0...v1.0.1](https://github.com/uapiq/usdk-python/compare/v1.0.0...v1.0.1)

### Bug Fixes

* compat with Python 3.14 ([8b41ed0](https://github.com/uapiq/usdk-python/commit/8b41ed0fb52a95e3fdefe94fe803adf4c5f448d7))


### Chores

* **package:** drop Python 3.8 support ([b02cc61](https://github.com/uapiq/usdk-python/commit/b02cc61ea9ef09e74ee061464157261300bddf44))

## 1.0.0 (2025-11-07)

Full Changelog: [v0.0.1...v1.0.0](https://github.com/uapiq/usdk-python/compare/v0.0.1...v1.0.0)

### Features

* **api:** manual updates ([38b7b86](https://github.com/uapiq/usdk-python/commit/38b7b862430a16be9c5f132baaf41015048c5b77))


### Chores

* update SDK settings ([c849a0f](https://github.com/uapiq/usdk-python/commit/c849a0f78ca1a92ab92182a185a5cc061c4b1cfc))
* update SDK settings ([d46f836](https://github.com/uapiq/usdk-python/commit/d46f836ce48cae2804d12e211cb27ea02a4e0655))
