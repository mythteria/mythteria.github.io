Title: Ничего лишнего
Published: 23/3/2017
Tags: .NET
---

Только код:

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