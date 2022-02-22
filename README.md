# Related Work
## PAKE
Encrypted Key Exchange(EKE). Bellovin&Merritt 
[[paper]](https://www.cs.columbia.edu/~smb/papers/neke.pdf)  
Simple Password-Based Encrypted Key   Exchange Protocols 
[[paper]](https://eprint.iacr.org/2005/196.pdf)
Authenticated key exchange secure against dictionary attacks. BPP00
[[paper]](https://eprint.iacr.org/2000/014.pdf) first provable secure PAKE protocol. Secure in ROM.
Session-Key Generation using Human Passwords Only. Goldreich and Lindell.
[[paper]](https://eprint.iacr.org/2000/057.pdf)
the first construction without ROM, based on general assumptions.

### Lattice PAKE
Smooth projective hashing and password-based authenticated key exchange
from lattices.
KV09. 
[[paper]](https://www.cs.umd.edu/~jkatz/papers/lattice-PAK.pdf)  
First lattice PAKE protocol. Alice and Bob
first send a CCA-secure ciphertext to each other. Then, they try to compute approximate smooth
projective hashing (ASPH) values on the ciphertexts and conduct a key reconciliation to derive a
session key. Their key reconciliation mechanism consists of two steps: the first step aims to extract
a bit from the ASPH value which is slightly noisy, while the second step is dedicated to correct the
error using error-correcting code (ECC). This mechanism is relatively inefficient as it can extract
at most one bit per field element. 

A new framework for efficient password-based authenticated key exchange. GK
[[paper]](https://eprint.iacr.org/2010/147.pdf)

Efficient password authenticated key exchange
via oblivious transfer. Ran Canetti
, Dana Dachman-Soled, Vinod Vaikuntanathan, and Hoeteck Wee.
[[paper]](https://user.eng.umd.edu/~danadach/MyPapers/pake.pdf)

Hash Proof Systems over Lattices Revisited. Fabrice Benhamouda
, Olivier Blazy
, Léo Ducas
, and Willy Quach
[[paper]](https://eprint.iacr.org/2017/997.pdf)

Two-Round PAKE from Approximate SPH
and Instantiations from Lattices.Zhang and Yu.
[[paper]](https://eprint.iacr.org/2017/838.pdf)
a new ASPH built on a “splittable CCA-secure encryption”. Realization in ROM.

Provably secure password authenticated key exchange
based on RLWE for the post-quantum world
Ding et al. 
[[paper]](https://eprint.iacr.org/2016/552.pdf)
The idea is to authenticate the lattice Diffie-Hellman using the random oracle protected password. ROM-based. Security claim in BPP. 3 round for Explicit Authenticationa and 2 round implicit. LWE and RLWE.


PAKEs: New Framework, New Techniques and More Efficient
Lattice-Based Constructions in the Standard Model
[[paper]](https://eprint.iacr.org/2020/140.pdf)

## aPAKE
OPAQUE
[[Original paper on eprint]](https://eprint.iacr.org/2018/163.pdf)
[[Slides by Jiayu]](https://eurocrypt.iacr.org/2018/Slides/Thursday/TrackA/02-03.pdf)
[[Slides by Hugo]](https://rwc.iacr.org/2019/slides/opaque-rwc19-posted.pdf)
[[video]](https://www.youtube.com/watch?v=LivwMvoEEKM)
[[Tatiana's blogpost]](https://blog.cloudflare.com/opaque-oblivious-passwords/)    


saPAKE from trapdoor CKEM
[[paper]](https://eprint.iacr.org/2019/647.pdf)

## AKE
HMQV
[[Intro slides of MQV and HMQV]](https://www.aumasson.jp/data/talks/mqv_ic67.pdf)
[[Original HQMV paper]](https://eprint.iacr.org/2005/176.pdf)
[[One-pass version]](https://eprint.iacr.org/2010/638.pdf)

X3DH
[[paper]](https://signal.org/docs/specifications/x3dh/)

## Lattice KEM
#### Saber 
[[website]]()
[[paper]](https://eprint.iacr.org/2018/230.pdf) 
[[PhD Thesis]](https://www.esat.kuleuven.be/cosic/publications/thesis-398.pdf)
#### Kyber 
[[website]]()
[[paper]]()
[[video]](https://www.youtube.com/watch?v=YsnmYl7BsgY)

#### FredoKEM
[[website]](https://frodokem.org/#spec)
[[paper]]()

#### Classic McEliese


#### FO transform
A modular analysis of the fujisakiokamoto transformation
[[paepr]](https://eprint.iacr.org/2017/604.pdf)
[[overview]](https://courses.cs.ut.ee/MTAT.07.022/2018_fall/uploads/Main/reelika-report-f18-19.pdf)

## Quantum Cryptography
protocol secure under RO is still secure under Quantum RO   
How to Record Quantum Queries, and Applications to Quantum Indifferentiability
[[paper]](https://eprint.iacr.org/2018/276.pdf)  
Quantum Lazy Sampling and Game-Playing Proofs for Quantum Indifferentiability
[[paper]](https://eprint.iacr.org/2019/428.pdf)  
Strengths and Weaknesses of Quantum Computing
[[paper]](https://arxiv.org/pdf/quant-ph/9701001.pdf)  


## Secure Aggregation
LightSecAgg
[[paper]](https://arxiv.org/pdf/2109.14236.pdf)




## Awesome links
[[Awesome HE]](https://github.com/jonaschn/awesome-he)
[[Awesome MPC]](https://github.com/rdragos/awesome-mpc)