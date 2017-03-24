Title: Ничего лишнего
Published: 2017-03-23
Tags: .NET
---

Ничего личного

```csharp
namespace System
{
    sealed public class String
    {
        public override string ToString()
        {
            return this;
        }
    }
}
```