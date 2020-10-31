---
uid: Microsoft.Quantum.Arithmetic.EvaluatePolynomialFxP
title: EvaluatePolynomialFxP operation
ms.date: 10/31/2020 12:00:00 AM
ms.topic: article
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Arithmetic
qsharp.name: EvaluatePolynomialFxP
qsharp.summary: Evaluates a polynomial in a fixed-point representation.
---

# EvaluatePolynomialFxP operation

Namespace: [Microsoft.Quantum.Arithmetic](xref:Microsoft.Quantum.Arithmetic)

Package: [](https://nuget.org/packages/)


Evaluates a polynomial in a fixed-point representation.

```qsharp
operation EvaluatePolynomialFxP (coefficients : Double[], fpx : Microsoft.Quantum.Arithmetic.FixedPoint, result : Microsoft.Quantum.Arithmetic.FixedPoint) : Unit
```


## Input

### coefficients : [Double](xref:microsoft.quantum.lang-ref.double)[]

Coefficients of the polynomial as a double array, i.e., the array


### fpx : [FixedPoint](xref:Microsoft.Quantum.Arithmetic.FixedPoint)

Input fixed-point number for which to evaluate the polynomial.


### result : [FixedPoint](xref:Microsoft.Quantum.Arithmetic.FixedPoint)

Output fixed-point number which will hold $P(x)$. Must be in state



## Output : [Unit](xref:microsoft.quantum.lang-ref.unit)
