# Secret-Santa
Use this to generate a pseudo-random Secret Santa ordering when you do not want certain groups of people to be giving gifts to one another (when they are in the same family for instance). Go to https://timetravel-1.github.io/Secret-Santa/.

EDIT: I recently determined that the act of determining whether such an ordering exists is NP-Complete. That is, given a list of people grouped into families (people who will not give each other gifts), determining whether a cycle can be formed where people do not give others in the same family gifts is NP-Complete. Thus, generating such a cycle is at least as difficult. The proof is simple, and is obtained by reducing from the Hamiltonian Path problem. The problem of generating a Secret Santa ordering is therefore in [FNP](https://en.wikipedia.org/wiki/FNP_(complexity)), and those exponential algorithms can solve this completely.
