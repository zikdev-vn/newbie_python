# newbie_python

## Background font
```bash
from colorama import Fore
import pyfiglet

font = pyfiglet.figlet_format('Happy New Year')
print('Fore.BLUE+font')
```
## remove img background

```bash
from rembg import remove
from PIL import Image

input_path = 'aaa.jpg'
output_path = 'aaa.png'
inp = Image.open(input_path}
output = remove(inp)
output.save(output_path)

```
