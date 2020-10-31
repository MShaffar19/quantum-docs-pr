---
uid: Microsoft.Quantum.Canon.ControlledOnBitString
title: ControlledOnBitString function
ms.date: 10/31/2020 12:00:00 AM
ms.topic: article
qsharp.kind: function
qsharp.namespace: Microsoft.Quantum.Canon
qsharp.name: ControlledOnBitString
qsharp.summary: Returns a unitary operation that applies an oracle on the target register if the control register state corresponds to a specified bit mask.
---

# ControlledOnBitString function

Namespace: [Microsoft.Quantum.Canon](xref:Microsoft.Quantum.Canon)

Package: [](https://nuget.org/packages/)


Returns a unitary operation that applies an oracle on the target register if the control register state corresponds to a specified bit mask.

```qsharp
function ControlledOnBitString<'T> (bits : Bool[], oracle : ('T => Unit is Adj + Ctl)) : ((Qubit[], 'T) => Unit is Adj + Ctl)
```


## Description

The output of this function is an operation that can be represented by a

## Input

### bits : [Bool](xref:microsoft.quantum.lang-ref.bool)[]

The bit string to control the given unitary operation on.


### oracle : 'T => [Unit](xref:microsoft.quantum.lang-ref.unit) Adj + Ctl

The unitary operation to be applied on the target register.



## Output : ([Qubit](xref:microsoft.quantum.lang-ref.qubit)[],'T) => [Unit](xref:microsoft.quantum.lang-ref.unit) Adj + Ctl

A unitary operation that applies `oracle` on the target register if the control register state corresponds to the bit mask `bits`.

## Type Parameters

### 'T



## Remarks

The pattern given by `bits` may be shorter than `controlRegister`,