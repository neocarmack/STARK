# Abstract
We arithmetize the execution trace of the BitVM circuit(represents some computation), and generate off-chain STARK proof for public verification. If the prover can not generate a correct proof, then the verifier only needs to challenge once (open one arbitrary gate) to get the BTC in the 2-sig address. If the prover can generate a correct proof, then he can get BTC by one response. The method in this paper avoids a large amount of on-chain transactions in the challenge-response process, but the amount of off-chain computation will be relatively large, mainly because generating START proof will consume more computing resources.

# The paper

[STARK proof for BitVM circuit execution](https://github.com/neocarmack/STARK/blob/main/STARK%20proof%20for%20BitVM%20circuit%20execution.pdf)

