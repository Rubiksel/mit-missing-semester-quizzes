## Answers

1. Entropy is the measure of uncertainty or randomness. Mathematically, it’s `log₂(#possibilities)` in bits.
2. `log₂(2) = 1 bit`.
3. `log₂(6) ≈ 2.6 bits`.
4. It takes input of variable length and produces a fixed-size output.
5. 160 bits.
6. `printf "hello" | sha1sum`
7. The hash can't be 'reversed' to retrieve the original input.
8. When two different inputs produce the same hash output.
9. To prevent attackers from creating malicious inputs with the same hash as legitimate ones.
10. Git identifies commits and files by their SHA-1 hashes.
11. A function that takes a password or secret and deterministically produces a fixed-length cryptographic key.
12. It makes brute-force and dictionary attacks more time-consuming and expensive.
13. A random string added to the password to prevent attackers from using precomputed hashes.
14. It makes each password hash unique, even for the same password.
15. An encryption method where the same key is used to encrypt and decrypt data.
16. The user loses access to the encrypted data unless the key is derived from a passphrase using a KDF (then the user can simply use the KDF again to retrieve the key).
17. `openssl aes-256-cbc -salt -in README.md -out README.enc.md`
18. `openssl aes-256-cbc -d -in README.enc.md -out README.dec.md`
19. It uses a public/private key pair. Public key encrypts or verifies, private key decrypts or signs.
20. A system that uses asymmetric encryption to securely exchange a symmetric key, then uses symmetric encryption for the data.
