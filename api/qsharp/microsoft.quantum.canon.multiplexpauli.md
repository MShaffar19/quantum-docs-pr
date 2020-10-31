---
uid: Microsoft.Quantum.Canon.MultiplexPauli
title: MultiplexPauli operation
ms.date: 10/31/2020 12:00:00 AM
ms.topic: article
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Canon
qsharp.name: MultiplexPauli
qsharp.summary: Applies a Pauli rotation conditioned on an array of qubits.
---

# MultiplexPauli operation

Namespace: [Microsoft.Quantum.Canon](xref:Microsoft.Quantum.Canon)

Package: [](https://nuget.org/packages/)


Applies a Pauli rotation conditioned on an array of qubits.

```qsharp
operation MultiplexPauli (coefficients : Double[], pauli : Pauli, control : Microsoft.Quantum.Arithmetic.LittleEndian, target : Qubit) : Unit
```


## Description

This applies a multiply controlled unitary operation that performs

## Input

### coefficients : [Double](xref:microsoft.quantum.lang-ref.double)[]

Array of up to $2^n$ coefficients $\theta_j$. The $j$th coefficient


### pauli : [Pauli](xref:microsoft.quantum.lang-ref.pauli)

Pauli operator $P$ that determines axis of rotation.


### control : [LittleEndian](xref:Microsoft.Quantum.Arithmetic.LittleEndian)

$n$-qubit control register that encodes number states $\ket{j}$ in


### target : [Qubit](xref:microsoft.quantum.lang-ref.qubit)

Single qubit register that is rotated by $e^{i P \theta_j}$.



## Output : [Unit](xref:microsoft.quantum.lang-ref.unit)



## Remarks

`coefficients` will be padded with elements $\theta_j = 0.0$ if

## See Also

- [Microsoft.Quantum.Canon.ApproximatelyMultiplexPauli](xref:Microsoft.Quantum.Canon.ApproximatelyMultiplexPauli)