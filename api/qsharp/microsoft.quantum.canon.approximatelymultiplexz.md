---
uid: Microsoft.Quantum.Canon.ApproximatelyMultiplexZ
title: ApproximatelyMultiplexZ operation
ms.date: 10/31/2020 12:00:00 AM
ms.topic: article
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Canon
qsharp.name: ApproximatelyMultiplexZ
qsharp.summary: >-
  Applies a Pauli Z rotation conditioned on an array of qubits, truncating
  small rotation angles according to a given tolerance.
---

# ApproximatelyMultiplexZ operation

Namespace: [Microsoft.Quantum.Canon](xref:Microsoft.Quantum.Canon)

Package: [](https://nuget.org/packages/)


Applies a Pauli Z rotation conditioned on an array of qubits, truncating

```qsharp
operation ApproximatelyMultiplexZ (tolerance : Double, coefficients : Double[], control : Microsoft.Quantum.Arithmetic.LittleEndian, target : Qubit) : Unit
```


## Description

This applies the multiply controlled unitary operation that performs

## Input

### tolerance : [Double](xref:microsoft.quantum.lang-ref.double)

A tolerance below which small coefficients are truncated.


### coefficients : [Double](xref:microsoft.quantum.lang-ref.double)[]

Array of up to $2^n$ coefficients $\theta_j$. The $j$th coefficient


### control : [LittleEndian](xref:Microsoft.Quantum.Arithmetic.LittleEndian)

$n$-qubit control register that encodes number states $\ket{j}$ in


### target : [Qubit](xref:microsoft.quantum.lang-ref.qubit)

Single qubit register that is rotated by $e^{i P \theta_j}$.



## Output : [Unit](xref:microsoft.quantum.lang-ref.unit)



## Remarks

`coefficients` will be padded with elements $\theta_j = 0.0$ if

## References

- Synthesis of Quantum Logic Circuits

## See Also

- [Microsoft.Quantum.Canon.MultiplexZ](xref:Microsoft.Quantum.Canon.MultiplexZ)