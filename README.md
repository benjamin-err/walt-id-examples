# waltid-examples

<div align="center">
 <h1>walt.id identity examples</h1>
 <p>This repository contains a few examples to quickly get you started with the waltid-identity SDK.
</p>

<a href="https://walt.id/community">
<img src="https://img.shields.io/badge/Join-The Community-blue.svg?style=flat" alt="Join community!" />
</a>
<a href="https://twitter.com/intent/follow?screen_name=walt_id">
<img src="https://img.shields.io/twitter/follow/walt_id.svg?label=Follow%20@walt_id" alt="Follow @walt_id" />
</a>
</div>

For a selection of examples, please take a look at the following table:

| Examples available      | Kotlin                                                                                            | Java                                                                                               |
|-------------------------|---------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------|
| Generate DIDs           | [Yes](https://github.com/walt-id/waltid-examples/blob/main/src/main/kotlin/did/create)            | [Yes](https://github.com/walt-id/waltid-examples/blob/main/src/main/java/waltid/DidExamples.java)  |
| Resolve DIDs            | [Yes](https://github.com/walt-id/waltid-examples/blob/main/src/main/kotlin/did/resolve)           | [Yes](https://github.com/walt-id/waltid-examples/blob/main/src/main/java/waltid/DidExamples.java)  |
| Create Keys             | [Yes](https://github.com/walt-id/waltid-examples/blob/main/src/main/kotlin/crypto/key/create)     | [Yes](https://github.com/walt-id/waltid-examples/blob/main/src/main/java/waltid/KeysExamples.java) |
| Import Keys             | [Yes](https://github.com/walt-id/waltid-examples/blob/main/src/main/kotlin/crypto/key/decode)     | [Yes](https://github.com/walt-id/waltid-examples/blob/main/src/main/java/waltid/KeysExamples.java) |
| Export Keys             | [Yes](https://github.com/walt-id/waltid-examples/blob/main/src/main/kotlin/crypto/key/encode)     | [Yes](https://github.com/walt-id/waltid-examples/blob/main/src/main/java/waltid/KeysExamples.java) |
| Key sign / verify raw   | [Yes](https://github.com/walt-id/waltid-examples/blob/main/src/main/kotlin/crypto/signatures/raw) | [Yes](https://github.com/walt-id/waltid-examples/blob/main/src/main/java/waltid/KeysExamples.java) |
| Key sign / verify JWS   | [Yes](https://github.com/walt-id/waltid-examples/blob/main/src/main/kotlin/crypto/signatures/jws) | [Yes](https://github.com/walt-id/waltid-examples/blob/main/src/main/java/waltid/KeysExamples.java) |
| JWT VC sign / verify    | [Yes](https://github.com/walt-id/waltid-examples/blob/main/src/main/kotlin/vc/jwt)                | [Yes](https://github.com/walt-id/waltid-examples/blob/main/src/main/java/waltid/VcExamples.java)   |
| SD-JWT VC sign / verify | [Yes](https://github.com/walt-id/waltid-examples/blob/main/src/main/kotlin/vc/sdjwt)              | [Yes](https://github.com/walt-id/waltid-examples/blob/main/src/main/java/waltid/VcExamples.java)   |
| VP sign / verify        | [Yes](https://github.com/walt-id/waltid-examples/blob/main/src/main/kotlin/vp)                    | [Yes](https://github.com/walt-id/waltid-examples/blob/main/src/main/java/waltid/VpExamples.java)   |

Follow the link to view the associated code example.

You can also view samples in the test directories of
the [identity repository](https://github.com/walt-id/waltid-identity).

## Running the examples

We're writing our projects with Gradle in mind; however, you can absolutely also use Apache Maven.
Use the repository `https://maven.waltid.dev/releases`. For a web interface to list available artifacts and their
current versions,
visit https://maven.waltid.dev/#/releases/id/walt in your web browser.

If you use Gradle with e.g., IntelliJ IDEA, you can simply run the examples by right-clicking them.

## Join the community

* Connect and get the latest updates: <a href="https://discord.gg/AW8AgqJthZ">
  Discord</a> | <a href="https://walt.id/newsletter">
  Newsletter</a> | <a href="https://www.youtube.com/channel/UCXfOzrv3PIvmur_CmwwmdLA">
  YouTube</a> | <a href="https://mobile.twitter.com/walt_id" target="_blank">Twitter</a>
* Get help, request features and report bugs: <a href="https://github.com/walt-id/.github/discussions" target="_blank">
  GitHub
  Discussions</a>

## License

**Licensed under the [Apache License, Version 2.0](https://github.com/walt-id/waltid-ssikit/blob/master/LICENSE).**
