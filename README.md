[![Version](https://img.shields.io/nuget/v/Katex?logo=nuget&style=flat-square)](https://www.nuget.org/packages/RamType0.Markdig.Renderers.MudBlazor/)
[![Nuget downloads](https://img.shields.io/nuget/dt/Katex?label=nuget%20downloads&logo=nuget&style=flat-square)](https://www.nuget.org/packages/RamType0.Markdig.Renderers.MudBlazor/)  
# KatexDotNet
KatexDotNet is [KaTeX](https://github.com/KaTeX/KaTeX) integration for Blazor.

## Getting started

You don't need any additional setup, the library will automatically load the required KaTeX JS files.

Just use `KatexView` component and pass the TeX expression as `TexExpression` parameter.


```razor

<KatexView TexExpression="@TexExpression" Options="@Options" />

```
