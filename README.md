# LegoMonitor

## How to use

```pip3 install tls-client``` is the only dependancy you will need to install

- All you need for this is a product ID for the product. You can find this at the end of the product URL. It should only be a few numbers long.
- At the time of writing this, it does not have any webhook support but it is very easy to implement, as all the data you will need for it has been parsed for you.
- Proxy support is optional. The API does not need any form of cookies or authentication but IP throttling may be an issue so the code snippet is there.

- I would recommend adding threading if you plan on monitoring multiple products.
