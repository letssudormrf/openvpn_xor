# openvpn_obfs

Note: The "scramble" option and parameters in the server and client configuration files must match.

    scramble xor_string

    scramble xormask xor_string

These options XOR the bytes in each buffer with xor_string.

    scramble reverse

The "reverse" option reverses order of the bytes in each buffer (except that the first byte is unchanged). So "abcde" becomes "aedcb".

    scramble xorptrpos

The "xorptrpos" option XORs each byte of the buffer of traffic with the position in the buffer.

    scramble obfuscate password

