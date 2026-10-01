---
title: "ResourceLoadBaseUri"
second_title: "GroupDocs.Assembly für .NET API-Referenz"
description: "Liest oder legt eine Basis-URI fest, um externe Ressourcendateien von relativen URIs in absolute URIs aufzulösen, während ein HTML-Vorlagendokument geladen wird, das zusammengesetzt und in ein Nicht-HTML-Format gespeichert werden soll. Der Standardwert ist eine leere Zeichenfolge."
type: docs
weight: 20
url: /de/net/groupdocs.assembly/loadsaveoptions/resourceloadbaseuri/
---
## LoadSaveOptions.ResourceLoadBaseUri property

Liest oder setzt eine Basis-URI, um relative URIs von externen Ressourcendateien in absolute URIs aufzulösen, während ein HTML-Vorlagendokument geladen wird, das zusammengefügt und in ein Nicht‑HTML‑Format gespeichert wird. Der Standardwert ist eine leere Zeichenkette.

```csharp
public string ResourceLoadBaseUri { get; set; }
```

### Hinweise

Beim Laden eines HTML-Dokuments aus einer Datei wird standardmäßig sein übergeordnetes Verzeichnis als Basis-URI verwendet, was beim Laden eines HTML-Dokuments aus einem Stream nicht möglich ist. Setzen Sie diese Eigenschaft, um einen Basis-URI beim Laden eines HTML-Dokuments aus einem Stream anzugeben oder um den Standard-Basis-URI beim Laden eines HTML-Dokuments aus einer Datei zu überschreiben.

Ein Wert dieser Eigenschaft wird in den folgenden Fällen ignoriert:

* An HTML document being loaded contains a BASE HTML element providing a base URI.
* An HTML document being loaded is to be assembled and saved to HTML (external resource files are not loaded and relative URIs are not changed then).

### Siehe auch

* class [LoadSaveOptions](../../loadsaveoptions)
* namespace [GroupDocs.Assembly](../../loadsaveoptions)
* assembly [GroupDocs.Assembly](../../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.Assembly.dll -->
