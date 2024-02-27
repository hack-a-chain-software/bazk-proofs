# Aztec-Noir BAZK Proofs

Repository to deploy BaZK Proofs to generate proofs on Aztec's noir language using the Aztec Barretenberg proving backend.

## Architecture

The solution consists of a Pod application on Phala Network. It runs an SGX server with nargo's basic setup so that it can generate proofs for different ZK programs written in Noir.

## Todo
- [ ] Provision clean SGX on Azure for testing
- [ ] Install nargo on Azure SGX
- [ ] Prove hello_world circuit on SGX
- [ ] Generalize setup for any circuit