# Turkish Taboo Words
It is includes turkish taboo words with different formats as JSON, XML and YAML.

## JSON
```json
[
  {
    "word": "SANTRFOR",
    "forbidden_words":[
      "FUTBOL",
      "OYUNCU",
      "SAHA",
      "FORVET",
      "GOL"
    ]
  }
]
```

## YAML
```yaml
-
  word: SANTRFOR
  forbidden_words:
    - FUTBOL
    - OYUNCU
    - SAHA
    - FORVET
```

## XML
```xml
<?xml version="1.0" encoding="UTF-8" ?>
<root>
  <row>
    <word>SANTRFOR</word>
    <forbidden_words>FUTBOL</forbidden_words>
    <forbidden_words>OYUNCU</forbidden_words>
    <forbidden_words>SAHA</forbidden_words>
    <forbidden_words>FORVET</forbidden_words>
    <forbidden_words>GOL</forbidden_words>
  </row>
</root>
```

## Authors
- [@dogukanyilmaz](https://github.com/dogukanyilmaz)
- [@sevvalsaygat](https://github.com/sevvalsaygat)
- [@nejdetkadir](https://github.com/nejdetkadir)

# LICENSE
```
MIT License

Copyright (c) 2022 Nejdet Kadir Bektaş

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```