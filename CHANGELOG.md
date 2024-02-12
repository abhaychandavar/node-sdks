# livekit-server-sdk

## 2.0.0

### Major Changes

- Change module type to ESM - [#118](https://github.com/livekit/server-sdk-js/pull/118) ([@lukasIO](https://github.com/lukasIO))

- Require node 18 as minimum version - [#118](https://github.com/livekit/server-sdk-js/pull/118) ([@lukasIO](https://github.com/lukasIO))

- Make `WebhookEvent` names type safe - [#125](https://github.com/livekit/server-sdk-js/pull/125) ([@lukasIO](https://github.com/lukasIO))

- Token generation is now async (replaced jsonwebtoken with jose for better JS runtime support) - [#118](https://github.com/livekit/server-sdk-js/pull/118) ([@lukasIO](https://github.com/lukasIO))

- Replace protobufjs with protobuf-es - [#118](https://github.com/livekit/server-sdk-js/pull/118) ([@lukasIO](https://github.com/lukasIO))

### Minor Changes

- Use globally available web crypto API instead of nodeJS crypto module - [#122](https://github.com/livekit/server-sdk-js/pull/122) ([@lukasIO](https://github.com/lukasIO))

### Patch Changes

- Throw error on bad Twirp response status and use async/await instead of promise chaining for improved error catching - [#124](https://github.com/livekit/server-sdk-js/pull/124) ([@lukasIO](https://github.com/lukasIO))