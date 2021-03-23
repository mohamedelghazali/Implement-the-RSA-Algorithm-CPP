# Implement-the-RSA-Algorithm-CPP
RSA is an asymmetric cryptography algorithm which works on two keys-public key and private key. In this simple code we will learn how to encrypt the message by this algorithm USING C++




Algorithms

Begin
   1. Choose two prime numbers p and q.
   2. Compute n = p*q.
   3. Calculate phi = (p-1) * (q-1).
   4. Choose an integer e such that 1 < e < phi(n) and gcd(e, phi(n)) = 1; i.e., e and phi(n) are coprime.
   5. Calculate d as d ≡ e−1 (mod phi(n)); here, d is the modular multiplicative inverse of e modulo phi(n).
   6. For encryption, c = me mod n, where m = original message.
   7. For decryption, m = c d mod n.


End
