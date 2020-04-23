# LWICA

An up-to-date DTN implementation.

## Goal of the project

There's few DTN implementations but most of them are outdated.
This implementation aims to follow the last updates of the standards/drafts.

### Standardisation sub-project

Some DTN implementations aren't compatible with other ones because of usage of not well-defined data syntaxes.
This may be caused by foggy or missing definitions.

In our implementation, every occurence of not well-defined data interchange will be first documented in our wikis,
then a notification and the proposal will be submitted to the standard/draft maintainers.

## DTN documents

* Base DTN documents:
  * DTN architecture [[RFC4838](https://tools.ietf.org/html/rfc4838)]
  * Bundle Protocol version 7 [[draft-ietf-dtn-bpbis-24](https://tools.ietf.org/html/draft-ietf-dtn-bpbis-24)]
  * PRoPHET [[RFC6693](https://tools.ietf.org/html/rfc6693)]
  * Licklider Transimssion Protocol [[RFC5326](https://tools.ietf.org/html/rfc5326)]
* Additionnal DTN documents:
  * Compressed Bundle Header Encoding [[RFC6260](https://tools.ietf.org/html/rfc6260)]
  * Additionnal IANA registries informations [[RFC7116](https://tools.ietf.org/html/rfc7116)]
  * HTTP over BP [[draft-perreault-dtnrg-http-00](https://tools.ietf.org/html/draft-perreault-dtnrg-http-00)]
* Data structures:
  * Concise Binary Object Representation [[RFC7049](https://tools.ietf.org/html/rfc7049)]
  * Self-Delimiting Numeric Values (Bundle Protocol version 6) [[RFC5050, section 4.1](https://tools.ietf.org/html/rfc5050#section-4.1)]
