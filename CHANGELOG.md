# Change Log

## [0.6.0](https://github.com/auth0/jwks-rsa-java/tree/0.6.0) (2018-07-18)
[Full Changelog](https://github.com/auth0/jwks-rsa-java/compare/0.5.0...0.6.0)

**Changed**
- Optional kid on single item JWK sets [\#32](https://github.com/auth0/jwks-rsa-java/pull/32) ([lbalmaceda](https://github.com/lbalmaceda))

## [0.5.0](https://github.com/auth0/jwks-rsa-java/tree/0.5.0) (2018-06-13)
[Full Changelog](https://github.com/auth0/jwks-rsa-java/compare/0.4.0...0.5.0)
**Closed issues**
- Improve release procedure [\#29](https://github.com/auth0/jwks-rsa-java/issues/29)

**Added**
- Optional support for connection / read timeout [\#27](https://github.com/auth0/jwks-rsa-java/pull/27) ([skjolber](https://github.com/skjolber))

**Fixed**
- Improve release procedure [\#30](https://github.com/auth0/jwks-rsa-java/pull/30) ([lbalmaceda](https://github.com/lbalmaceda))

**Security**
- [Snyk] Fix for 6 vulnerable dependencies [\#28](https://github.com/auth0/jwks-rsa-java/pull/28) ([crew-security](https://github.com/crew-security))
- bump commons-io due to security vulnerabilities in that library [\#26](https://github.com/auth0/jwks-rsa-java/pull/26) ([ryber](https://github.com/ryber))

## [0.4.0](https://github.com/auth0/jwks-rsa-java/tree/jwks-rsa-0.4.0) (2018-04-27)
[Full Changelog](https://github.com/auth0/jwks-rsa-java/compare/jwks-rsa-0.3.0...jwks-rsa-0.4.0)

**Added**
- Added url constructor to JwkProviderBuilder [\#22](https://github.com/auth0/jwks-rsa-java/pull/22) ([darthvalinor](https://github.com/darthvalinor))

## [0.3.0](https://github.com/auth0/jwks-rsa-java/tree/jwks-rsa-0.3.0) (2017-11-10)
[Full Changelog](https://github.com/auth0/jwks-rsa-java/compare/jwks-rsa-0.2.0...jwks-rsa-0.3.0)

**Changed**
- Parse 'key_ops' as an Array rather than a String [\#13](https://github.com/auth0/jwks-rsa-java/pull/13) ([chadramsey](https://github.com/chadramsey))
- Remove algorithm (alg tag) from mandatory Jwk attributes [\#10](https://github.com/auth0/jwks-rsa-java/pull/10) ([Colin-b](https://github.com/Colin-b))

## [0.2.0](https://github.com/auth0/jwks-rsa-java/tree/jwks-rsa-0.2.0) (2016-12-05)
[Full Changelog](https://github.com/auth0/jwks-rsa-java/compare/jwks-rsa-0.1.0...jwks-rsa-0.2.0)

**Added**
- Add Rate Limit provider [\#1](https://github.com/auth0/jwks-rsa-java/pull/1) ([lbalmaceda](https://github.com/lbalmaceda))

**Changed**
- Refactor JwkProviderBuilder [\#2](https://github.com/auth0/jwks-rsa-java/pull/2) ([lbalmaceda](https://github.com/lbalmaceda))
- Replace ExecutorService with primitive counters. [\#3](https://github.com/auth0/jwks-rsa-java/pull/3) ([lbalmaceda](https://github.com/lbalmaceda))

## [0.1.0](https://github.com/auth0/jwks-rsa-java/tree/jwks-rsa-0.1.0) (2016-08-30)

JSON Web Token Set parser library for Java. Initial release.


