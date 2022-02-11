---
description: "+ (Add) (MDX)"
title: "+ (Add) (MDX) | Microsoft Docs"
ms.date: 06/04/2018
ms.prod: sql
ms.technology: analysis-services
ms.custom: mdx
ms.topic: reference
ms.author: owend
ms.reviewer: owend
author: minewiskan
---
# + (Add) (MDX)


  Performs an arithmetic operation that adds two numbers.  Add a [broken link](broken_file_link.md) for testing validation on public repository
  
## Syntax  
  
```  
  
Numeric_Expression + Numeric_Expression  
```  
  
#### Parameters  
 *Numeric Expression*  
 A valid Multidimensional Expressions (MDX) expression that returns a numeric value.  
  
## Return Value  
 A value with the data type of the parameter that has the higher precedence.  
  
## Remarks  
 Both expressions must be of the same data type, or one expression must be able to be implicitly converted to the data type of the other expression. If one expression evaluates to a null value, the operator returns the result of the other expression.  
  
## See Also  
 [MDX Operator Reference &#40;MDX&#41;](../mdx/mdx-operator-reference-mdx.md)  
  
  
