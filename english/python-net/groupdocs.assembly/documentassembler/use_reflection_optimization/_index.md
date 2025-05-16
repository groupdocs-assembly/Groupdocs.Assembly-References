---
title: use_reflection_optimization property
second_title: GroupDocs.Assembly for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.assembly/documentassembler/use_reflection_optimization/
is_root: false
weight: 70
---

## use_reflection_optimization property


Gets or sets a value indicating whether invocations of custom type members performed via reflection API are 
optimized using dynamic class generation or not. The default value is true.

### Remarks 


There are some scenarios where it is preferrable to disable this optimization. For example, if you are dealing 
with small collections of data items all the time, then an overhead of dynamic class generation can be more 
noticeable than an overhead of direct reflection API calls.

### See Also
* module [`groupdocs.assembly`](../../)
* class [`DocumentAssembler`](/assembly/python-net/groupdocs.assembly/documentassembler)
