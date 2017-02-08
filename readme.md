BTCAddrValidator
=================

This is a simple address validator of Bitcoin support address start with "1" or "3" implemented by Java. You can copy code of BTCAddrValidator.java to your project for bitcoin address check using:

```java
String addr = "1PeFZno9AG3uDeNk57sfpBJ3HMBWLve6Si";
boolean addrIsValid = BTCAddrValidator.validate(addr);
if (addrIsValid) {
  ... do something;
}
```


License
=======

    Copyright 2017 Tim Qi

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.


