# Masters Work
Project work by masters students supervised by James Wootton at the University of Basel.

**[Universal quantum computation using a hybrid quantum double model](Laubscher_Universal_quantum_computation_using_a_hybrid_quantum_double_model.pdf)**

*Katharina Laubscher*

We present a way to perform universal quantum computation using a hybrid quantum
double model consisting of a lattice divided into two half-planes, where one
is associated with the D(Z_2) quantum double model and the other one with the
D(S_3) quantum double model. Logical information is stored in the D(Z_2) part
of the lattice using the usual hole-pair encoding, for which we perform initial-
ization processes, measurements and the full set of Clifford operations using the
standard procedures. We then use our knowledge of the braiding rules of the
D(S_3) quantum double model to prepare a non-stabilizer state in the D(S_3) part
of the lattice, and propose a protocol to inject such a state state into the D(Z_2)
phase. This allows us to perform universal quantum computation in the D(Z_2)
part of the lattice, replacing the standard magic state distillation procedures by
the injection of a non-stabilizer state from a foreign phase. We also discuss the
reverse process, i.e. the transport of logical information from the D(Z_2) phase
to the D(S_3) phase. This enables us to manipulate logical information in the
D(S_3) part of the lattice, further enlarging the set of possible operations and
providing even more flexibility.

**[Analysis of noisy gates in minimal surface codes](Peter_Analysis_of_noisy_gates_in_minimal_surface_codes.pdf)**

*Andreas Peter*

In order to build a useful quantum computer, the problem of noise
has to be tackled. A promising way to get noise under control is the use of
surface codes. The smallest useful surface code is S 17 , which we will analyse in
this work. Using tensor network methods, we analyse the connection between
the fidelity of the cnot-gates in a code with the performance of the code itself
for one round of error correction. Two scenarios were calculated for different
cnot inspired by quantum dot implementations, one starting in a product
state with one measurement round and final measurement and one starting in
a stabilizer state with one measurement round. For purely decoherent noise we
find that the code performance can be predicted well using the channel fidelity
for both scenarios. For more complicated unitary gates that approximate a
cnot and are derived from floating gate implementations we find that for very
small intervals of channel infidelity there is a large spread in code performance.
This shows that we can not predict the performance of a surface code that uses
specific entangling gates well if we only know the channel infidelity of those
entangling gates.

**[Stabilizer Codes as Resource for non-universal Quantum Information
Processing on the Example of the Quantum Anonymous Broadcast](Kesselring_Stabilizer_codes_as_resource_for_non-universal_quantum_information_processing_on_the_example_of_the_quantum_anonymous_broadcast.pdf)**

*Markus Kesselring*

The quantum anonymous broadcast (QAB) is an example of an information protocol not relying
on the full universal gate set. It can be carried out with gates in the Clifford group alone. This
makes it an interesting candidate for the study of fault tolerant means to achieve it. Systems with
a high resilience against errors, such as surface codes or Majorana zeromodes, have the flaw of not
trivially having access to the whole universal gate set. We study how to implement the QAB in a
variety of fault tolerant systems. In a last section, non-destructive ways to measure the charge of
multiple Majorana zeromodes is discussed.

**[Embedded D(Z_2) Surface Codes & A decoder for imperfectly measured Planar Code](Winkler_Embedded_D(Z_2)_surface_codes.pdf)**

*Janos Winkler*

New topological error correction codes are defined using embedding techniques, where D(Z_2)
Surface Codes serve as the building blocks. The properties of these new codes are thoroughly
investigated and we show that they do not all share the same anyon model.

We developed a decoder under the assumption that noiseless measurement of the stabilizers
is not possible. This decoder is based on the MWPM algorithm and is designed to fix errors on a
Wen style planar code. The decoder was numerically tested and a threshold was obtained for two
rounds of measurements, where measurement errors occurred with a probability of p m = 1%. The
thresholds for the decoder were found in the range of ≈ 6% for independent noise as well as ≈ 9%
for depolarized noise. Furthermore, we show that the decoder is significantly better compared to
regular MWPM for very low error rates.



