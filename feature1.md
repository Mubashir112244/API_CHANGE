title: Add Support for 3D Imaging little change
author: CT Core Team
iteration: VA50A.0.03
changelevel: breaking

---

## Title
Add Support for 3D Imaging

## Change Classification
Change Level: NonBreaking
Change Type: Add

## Changed Building Blocks
CT.Core.ImageProcessor

## Affected Building Blocks
CT.Core.ImageProcessor

## Change Description
Added API to handle 3D image stacks for volume rendering.

## Motivation
Required for supporting newer CT modalities.

## Impact Assessment
n.a.

## Solution
New method `Process3DStack()` added.

## Examples

### New API

```csharp
var result = processor.Process3DStack(volumeData);
