---
uid: Microsoft.Quantum.Arrays.Padded
title: Padded function
ms.date: 10/31/2020 12:00:00 AM
ms.topic: article
qsharp.kind: function
qsharp.namespace: Microsoft.Quantum.Arrays
qsharp.name: Padded
qsharp.summary: >-
  Returns an array padded at with specified values up to a
  specified length.
---

# Padded function

Namespace: [Microsoft.Quantum.Arrays](xref:Microsoft.Quantum.Arrays)

Package: [](https://nuget.org/packages/)


Returns an array padded at with specified values up to a

```qsharp
function Padded<'T> (nElementsTotal : Int, defaultElement : 'T, inputArray : 'T[]) : 'T[]
```


## Input

### nElementsTotal : [Int](xref:microsoft.quantum.lang-ref.int)

The length of the padded array. If this is positive, `inputArray`


### defaultElement : 'T

Default value to use for padding elements.


### inputArray : 'T[]

Array whose values are at the head of the output array.



## Output : 'T[]

An array `output` that is the `inputArray` padded at the head

## Type Parameters

### 'T

The type of the array elements.