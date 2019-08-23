# mongodb-queue-ds #

[![NPM](https://nodei.co/npm/mongodb-queue-ds.png?mini=true)](https://www.npmjs.com/package/mongodb-queue-ds/)

This repo is a fork of the very useful mongodb-queue done by Andrew Chilton available at https://github.com/chilts/mongodb-queue

To learn how to use this check official docs and more information check out his repo.

Below is only docs for the methods I've added. 

It should be without bugs but use it at your own risk or contact me.

## Operations ##

### .failed() ###

Returns the total number of messages that exceed max retries.

```js
queue.failed((err, count) => {
    console.log('This queue has %d failed messages', count)
})
```

## Credits ##

```
Andrew Chilton
https://github.com/chilts 

```
## Fork author ##

```
Daniel Santos
https://github.com/danielrmsantos/
danielrmsantos@gmail.com

```

## License ##

MIT - http://chilts.mit-license.org/2014/

(Ends)
