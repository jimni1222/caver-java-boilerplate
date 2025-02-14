# caver-java-boilerplate

This project is a caver-java boilerplate project.

## How to use
To connet Klaytn EN, this project used KAS's [NODE API](https://refs.klaytnapi.com/en/node/latest).

If you haven't signed up for [KAS](https://www.klaytnapi.com/ko/landing/main) yet, you need to sign up and get an KAS access key and secret key.
- Set your access key and secret key in BoilerPlate class.
- Copy and paste a test code in test() method.  
- Before running a Main class, You have to decide which network to connect to.
  - If you want to connect testnet, you must use a `connectTestnet()` method.
  - If you want to connect mainnet, you must use a `connectMainnet()` method.
- Run a main method.
  - If you want to execute main method through console, you can you `./gradlew runMain`
     
## License
caver-java-boilerplate is released under the [MIT license](./LICENSE).

```
MIT License

Copyright (c) 2021 caver-java boilerplate Authors

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

