# parsel

Encrypt and decrypt data with a given key.

This library was created to allow an easy data
exchange between Ruby and Node.js.

Check it out the Node.js counter-part: <http://github.com/fnando/parsel-js>.

## Installation

    gem install parsel

## Usage

    require "parsel"

    secret_key = "mysupersecretkeythatnobodyknowsabout"
    encrypted = Parsel.encrypt(secret_key, "hello from ruby!")
    decrypted = Parsel.decrypt(secret_key, encrypted)

## Maintainer

- Nando Vieira (<http://nandovieira.com.br>)

## License

(The MIT License)

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.