# CBOR4Swift
IoT 관련된 protocol 중 CBOR 에 대해 알게되었고, swift 로 구현된 것이 있는지 검색해봤으나 아직 decoder 만 구현되어 있는것을 알게 되었다.

지난해 말에 swift3 가 정식으로 릴리즈되었고 부족하지만 올해 짬짬이 swift 로 구현된 CBOR 라이브러리를 개발해볼 예정이다.



### TODO
1. [ ] CBOR Encoder
2. [ ] CBOR Decoder

### Support
* swift3
* TDD



# Reference

### CBOR
* [RFC7049 - Concise Binary Objecct Representation](https://tools.ietf.org/html/rfc7049)

* [RFC7049 - Other CBOR Document](http://www.bortzmeyer.org/7049.html)

* [SwiftCBOR - A CBOR implementation for Swift](https://github.com/myfreeweb/SwiftCBOR)

	CBOR decoder supported. but not support encoder

### Swift
* [Swift.org](https://swift.org)
* Parser
	- lexer & parser in Swift
		* [Writing a lexer in Swift](http://blog.matthewcheok.com/writing-a-lexer-in-swift)
		* [Writing a parser in Swift](http://blog.matthewcheok.com/writing-a-parser-in-swift)
		* [github - Kaleidoscope in Swift](https://github.com/matthewcheok/Kaleidoscope)
	- Parser Combinator in Swift
		* [slide](https://speakerdeck.com/inamiy/parser-combinator-in-swift)
		* [github - TryParsec](https://github.com/tryswift/TryParsec)