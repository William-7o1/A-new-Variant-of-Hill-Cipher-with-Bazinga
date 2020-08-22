# A-new-Variant-of-Hill-Cipher-with-Bazinga
Modified Hill Cipher algorithm

Hill cipher is a polygraphic substitution cipher developed on Linear algebra. However, it could be vulnerable to a known-plaintext attack and another big drawback of hill cipher is the unreliability of whether the key matrix is invertible for the decryption. We have modified the traditional Algorithm by adding a random key generator using python secrets library which always gives a valid key, there is 2 phase padding and by applying bit manipulation algorithm (Bazinga), it overcomes the flaws of the hill cipher, test confirm based on real experiment, the avalanche score increases to 53.2 %
