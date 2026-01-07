# Experiment 7: Encryption of Plaintext Using Twofish Algorithm

## Twofish Algorithm Encryption Process

Twofish is a symmetric key block cipher designed as a finalist for the AES competition. It operates on 128-bit blocks and supports key sizes of 128, 192, or 256 bits. Twofish uses a 16-round Feistel network, combining high security with efficiency. Its design includes key-dependent S-boxes, a Maximum Distance Separable (MDS) matrix, and modular arithmetic to provide strong diffusion and confusion, making it resistant to known attacks like linear and differential cryptanalysis.

The encryption process begins with key whitening, where the plaintext is XORed with portions of the key before entering the Feistel rounds. Each round applies a complex F-function, which mixes the data using key-dependent S-boxes, modular addition, XOR, and rotations. The halves of the data are swapped and combined through these operations, ensuring that each bit of the ciphertext depends on all bits of the plaintext and key, achieving high security and randomness.

Twofish also features an efficient key schedule, generating subkeys for input/output whitening and the F-function in each round. Its flexibility, speed, and strong security make it suitable for software and hardware implementations, file encryption, secure communication, and embedded systems. Overall, Twofish provides a reliable and modern symmetric encryption method for protecting sensitive data.
