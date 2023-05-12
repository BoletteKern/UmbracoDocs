---
title: CalculateOrderLineUnitPriceWithoutAdjustmentsTask
description: API reference for CalculateOrderLineUnitPriceWithoutAdjustmentsTask in Vendr, the eCommerce solution for Umbraco
---
## CalculateOrderLineUnitPriceWithoutAdjustmentsTask

```csharp
public class CalculateOrderLineUnitPriceWithoutAdjustmentsTask : 
    PipelineTaskWithTypedArgsBase<OrderLineCalculationPipelineArgs, OrderLineCalculation>
```

**Inheritance**

* class [PipelineTaskWithTypedArgsBase&lt;!0,!1&gt;](../../../vendr-common/vendr-common-pipelines/pipelinetaskwithtypedargsbase-2/)

**Namespace**
* [Vendr.Core.Pipelines.OrderLine.Tasks](../)

### Constructors

#### CalculateOrderLineUnitPriceWithoutAdjustmentsTask

The default constructor.

```csharp
public CalculateOrderLineUnitPriceWithoutAdjustmentsTask()
```


### Methods

#### Execute

```csharp
public override PipelineResult<OrderLineCalculation> Execute(OrderLineCalculationPipelineArgs args)
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->