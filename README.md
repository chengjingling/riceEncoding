# Rice Encoding

## About

This application showcases the rice encoding and decoding of Sound1.wav and Sound2.wav.

Rice encoding is an algorithm that converts an integer into a series of bits. The integer is first divided by 2^k to return the quotient and remainder. To encode the quotient, a sequence of '1's is generated, with the number of '1's equal to the quotient value, followed by a single '0'. The remainder is encoded by converting it into a binary string. Finally, the encoded quotient and remainder are concatenated to produce the complete encoded value.

**Note:** This application only covers rice encoding, which alone is not effective for data compression. In order to reduce the file size of the audio files, other lossless data compression methods would need to be implemented alongside rice encoding, such as blocking, inter-channel decorrelation and modelling.
