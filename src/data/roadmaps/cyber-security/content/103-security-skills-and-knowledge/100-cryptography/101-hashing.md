# Hashing

In this section, we will discuss the concept of _hashing_, an important cryptographic primitive, and its multiple applications in the realm of cyber security.

**What is Hashing?**

A _hash function_ is a mathematical algorithm that takes an input (or 'message') and returns a fixed-size string of bytes, usually in the form of a hexadecimal number. The output is called the _hash value_ or simply, the _hash_. Some characteristics of a good hash function are:

- _Deterministic_: The same input will always result in the same hash output.
- _Efficient_: The time taken to compute the hash should be as quick as possible.
- _Avalanche Effect_: A tiny change in the input should result in a drastically different hash output.
- _One-way Function_: It should be computationally infeasible to reverse-engineer the input from its hash output.
- _Collision Resistance_: It should be extremely unlikely to find two different inputs that produce the same hash output.

**Common Hashing Algorithms**

There are several widely used hashing algorithms with different strengths and weaknesses. Some of the most common ones include:

- MD5 (Message Digest 5): Produces a 128-bit hash value. It is no longer considered secure due to vulnerability to collision attacks.
- SHA-1 (Secure Hash Algorithm 1): Generates a 160-bit hash value. Like MD5, it is no longer considered secure due to collision attacks and is being phased out.
- SHA-256 and SHA-512: Part of the SHA-2 family, SHA-256 produces a 256-bit hash value, while SHA-512 generates a 512-bit hash value. Both are widely adopted and considered secure.

**Applications of Hashing**

Hashing is a versatile mechanism and serves many purposes in cyber security, such as:

- _Data Integrity_: Hashing can be used to ensure that a file or piece of data hasn't been altered or tampered with. Comparing the hash value of the original and received data can determine if they match.

- _Password Storage_: Storing users' passwords as hashes makes it difficult for attackers to obtain the plain-text passwords even if they gain access to the stored hashes.

- _Digital Signatures_: Digital signatures often rely on cryptographic hash functions to verify the integrity and authenticity of a message or piece of data.

- _Proof of Work_: Hash functions are employed in consensus algorithms like the one used in Bitcoin mining, as they can solve computational challenges.

In conclusion, hashing is a crucial technique in ensuring data integrity and maintaining security in various areas of cyber security. Understanding and adopting secure hashing algorithms is an essential skill for any cyber security professional.
