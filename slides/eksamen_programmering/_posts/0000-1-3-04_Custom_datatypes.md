## Custom datatypes

- Klasser der bruges til at strukturer data.
- Ingen metoder, kun felter
	- Pånær på CapaError

```csharp [9-14]
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Capa_Error_Explorer
{
    internal class CapaUnit
    {
        public int UnitID { get; set; }
        public string Name { get; set; }
        public Guid UUID { get; set; }
    }
}

```