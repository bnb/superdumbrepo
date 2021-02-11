# superdumbrepo

Hello and welcome to my super dumb repo that doesn't do anything! We just have a README here.

![FUN](https://www.animatedimages.org/data/media/499/animated-fun-image-0392.gif)

## Checkout all these people who looked at my repo:
* 👩🏾


## Fun code times:

TypeScript:
```typescript
export function validateURL(url: string): boolean {
    const protocols = ['http', 'https'];

    try {
        new URL(url);
        const parsed = parse(url);
        logDebug(parsed.protocol);
        return protocols
            ? parsed.protocol
                ? protocols.map(x => `${x.toLowerCase()}:`).includes(parsed.protocol) 
                    ? true : false
                : false
            : true;
    } catch (err) {
        return false;
    }
}
```
