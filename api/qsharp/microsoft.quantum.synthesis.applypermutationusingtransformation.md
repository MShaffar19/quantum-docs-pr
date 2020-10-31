---
uid: Microsoft.Quantum.Synthesis.ApplyPermutationUsingTransformation
title: ApplyPermutationUsingTransformation operation
ms.date: 10/31/2020 12:00:00 AM
ms.topic: article
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Synthesis
qsharp.name: ApplyPermutationUsingTransformation
qsharp.summary: >-
  Permutes the amplitudes in a quantum state given a permutation
  using transformation-based synthesis.
---

# ApplyPermutationUsingTransformation operation

Namespace: [Microsoft.Quantum.Synthesis](xref:Microsoft.Quantum.Synthesis)

Package: [](https://nuget.org/packages/)


Permutes the amplitudes in a quantum state given a permutation

```qsharp
operation ApplyPermutationUsingTransformation (perm : Int[], qubits : Microsoft.Quantum.Arithmetic.LittleEndian) : Unit
```


## Description

This procedure implements the unidirectional transformation based

## Input

### perm : [Int](xref:microsoft.quantum.lang-ref.int)[]

A permutation of $2^n$ elements starting from 0.


### qubits : [LittleEndian](xref:Microsoft.Quantum.Arithmetic.LittleEndian)

A list of $n$ qubits to which the permutation is applied to.



## Output : [Unit](xref:microsoft.quantum.lang-ref.unit)



## References

- [*D. Michael Miller*, *Dmitri Maslov*, *Gerhard W. Dueck*,

## See Also

- [Microsoft.Quantum.Synthesis.ApplyPermutationUsingDecomposition](xref:Microsoft.Quantum.Synthesis.ApplyPermutationUsingDecomposition)