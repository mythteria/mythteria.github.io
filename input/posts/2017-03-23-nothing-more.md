Title: Ничего лишнего
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