---
uid: Microsoft.Quantum.ErrorCorrection.FiveQubitCodeRecoveryFn
title: FiveQubitCodeRecoveryFn function
ms.date: 10/31/2020 12:00:00 AM
ms.topic: article
qsharp.kind: function
qsharp.namespace: Microsoft.Quantum.ErrorCorrection
qsharp.name: FiveQubitCodeRecoveryFn
qsharp.summary: >-
  Returns function that maps error syndrome measurements to the
  appropriate error-correcting Pauli operators by table lookup for
  the ⟦5, 1, 3⟧ quantum code.
---

# FiveQubitCodeRecoveryFn function

Namespace: [Microsoft.Quantum.ErrorCorrection](xref:Microsoft.Quantum.ErrorCorrection)

Package: [](https://nuget.org/packages/)


Returns function that maps error syndrome measurements to the

```qsharp
function FiveQubitCodeRecoveryFn () : Microsoft.Quantum.ErrorCorrection.RecoveryFn
```


## Output : [RecoveryFn](xref:Microsoft.Quantum.ErrorCorrection.RecoveryFn)

Function of type `RecoveryFn` that takes a syndrome measurement

## Remarks

By iterating over all errors of weight $1$, we obtain a total of $3\times 5=15$ possible non-trivial syndromes.

## See Also

- [Microsoft.Quantum.ErrorCorrection.RecoveryFn](xref:Microsoft.Quantum.ErrorCorrection.RecoveryFn)