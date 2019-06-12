<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [iconv-corefoundation](./iconv-corefoundation.md)

## iconv-corefoundation package

## Classes

|  Class | Description |
|  --- | --- |
|  [InvalidEncodedTextError](./iconv-corefoundation.invalidencodedtexterror.md) | Signals that the given encoded text is not valid in the chosen [StringEncoding](./iconv-corefoundation.stringencoding.md)<!-- -->. |
|  [NotRepresentableError](./iconv-corefoundation.notrepresentableerror.md) | Signals that the given text cannot be fully encoded in the chosen [StringEncoding](./iconv-corefoundation.stringencoding.md)<!-- -->. |
|  [StringEncoding](./iconv-corefoundation.stringencoding.md) | A character encoding, known to the Core Foundation framework. |
|  [UnrecognizedEncodingError](./iconv-corefoundation.unrecognizedencodingerror.md) | Signals that the given [StringEncoding](./iconv-corefoundation.stringencoding.md) specifier (IANA character set name, <code>CFStringEncoding</code> constant, or the like) is not recognized or not supported. |

## Functions

|  Function | Description |
|  --- | --- |
|  [decode(text, encoding, options)](./iconv-corefoundation.decode.md) | Convenience alias for [StringEncoding.decode()](./iconv-corefoundation.stringencoding.decode.md)<!-- -->. |
|  [encode(text, encoding, options)](./iconv-corefoundation.encode.md) | Convenience alias for [StringEncoding.encode()](./iconv-corefoundation.stringencoding.encode.md)<!-- -->. |
|  [encodeSmallest(text, options)](./iconv-corefoundation.encodesmallest.md) | Encodes the given text, using the smallest representation supported by Core Foundation. |
|  [encodeSmallest(text, options)](./iconv-corefoundation.encodesmallest_1.md) | Encodes the given text, using the smallest representation supported by Core Foundation. |
|  [encodingExists(encoding)](./iconv-corefoundation.encodingexists.md) | Tests whether an encoding exists and is supported. |
|  [transcode(text, fromEncoding, toEncoding, options)](./iconv-corefoundation.transcode.md) | Converts encoded text from one encoding to another. |
|  [transcodeSmallest(text, fromEncoding, options)](./iconv-corefoundation.transcodesmallest.md) | Converts encoded text from its current encoding to the smallest representation supported by Core Foundation. |
|  [transcodeSmallest(text, fromEncoding, options)](./iconv-corefoundation.transcodesmallest_1.md) | Converts encoded text from its current encoding to the smallest representation supported by Core Foundation. |

## Interfaces

|  Interface | Description |
|  --- | --- |
|  [DecodeOptions](./iconv-corefoundation.decodeoptions.md) | Options for decoding. |
|  [EncodeOptions](./iconv-corefoundation.encodeoptions.md) | Options for encoding. |
|  [SelectAndEncodeOptions](./iconv-corefoundation.selectandencodeoptions.md) | Additional options for encoding with <code>encodeSmallest</code> and <code>transcodeSmallest</code>. |
|  [TextAndEncoding](./iconv-corefoundation.textandencoding.md) | An object containing some encoded text in a <code>Buffer</code>, along with the encoding used. |

## Type Aliases

|  Type Alias | Description |
|  --- | --- |
|  [BufferLike](./iconv-corefoundation.bufferlike.md) | Supported representations of encoded text. |
