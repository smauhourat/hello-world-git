# Cabeceras 
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines
Underline 1
-----------

Underline 2
===========

# Formatos de enfasis
- letra *italica* de la primer forma.
- letra _italica_ de la segunda forma.
- formato **bold o strong** de la primer forma.
- formato __bold o strong__ de la segunda forma.
- formato ~~tachado~~, formato normal.


# Listas
1. Este es un item de lista ordenada.
2. Este es un item de lista ordenada.
3. Este es un item de lista ordenada.
   
- Este es un item de lista desordenada.
- Este es un item de lista desordenada.
- Este es un item de lista desordenada.

# Links
- <a href="http://www.google.com">Esto es un link<a/>
- [Esto es un link en Markdown](http://www.google.com)


# Imagenes
![Logo github] (https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

# Code Snippets
### JSON
```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```

### C#
```C#
using System.IO.Compression;

#pragma warning disable 414, 3021

namespace MyApplication
{
    [Obsolete("...")]
    class Program : IInterface
    {
        public static List<int> JustDoIt(int count)
        {
            Span<int> numbers = stackalloc int[length];
            Console.WriteLine($"Hello {Name}!");
            return new List<int>(new int[] { 1, 2, 3 })
        }
    }
}
```

# Tablas
| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Santiago | Mauhourat | 22298232 |
| Juan | Perez | 12298232 |