---
uid: Microsoft.Quantum.Canon.ApplyMultiControlledCA
title: ApplyMultiControlledCA operation
ms.date: 10/31/2020 12:00:00 AM
ms.topic: article
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Canon
qsharp.name: ApplyMultiControlledCA
qsharp.summary: >-
  Applies a multiply controlled version of a singly controlled
  operation.
  The modifier `CA` indicates that the single-qubit operation is controllable
  and adjointable.
---

# ApplyMultiControlledCA operation

Namespace: [Microsoft.Quantum.Canon](xref:Microsoft.Quantum.Canon)

Package: [](https://nuget.org/packages/)


Applies a multiply controlled version of a singly controlled

```qsharp
operation ApplyMultiControlledCA (singlyControlledOp : (Qubit[] => Unit is Adj), ccnot : Microsoft.Quantum.Canon.CCNOTop, controls : Qubit[], targets : Qubit[]) : Unit
```


## Input

### singlyControlledOp : [Qubit](xref:microsoft.quantum.lang-ref.qubit)[] => [Unit](xref:microsoft.quantum.lang-ref.unit) Adj

An operation controlled on a single qubit.


### ccnot : [CCNOTop](xref:Microsoft.Quantum.Canon.CCNOTop)

The controlled-controlled-NOT gate to use for the construction.


### controls : [Qubit](xref:microsoft.quantum.lang-ref.qubit)[]

The qubits that `singlyControlledOp` is to be controlled on.


### targets : [Qubit](xref:microsoft.quantum.lang-ref.qubit)[]

The target qubits that `singlyControlledOp` acts upon.



## Output : [Unit](xref:microsoft.quantum.lang-ref.unit)



## Remarks

This operation uses only clean ancilla qubits.

## References

- [ *Michael A. Nielsen , Isaac L. Chuang*,

## See Also

- [Microsoft.Quantum.Canon.ApplyMultiControlledC](xref:Microsoft.Quantum.Canon.ApplyMultiControlledC)