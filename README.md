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

Python:
```python
# Python program for implementation of Bubble Sort 
def bubbleSort(arr): 
    n = len(arr) 
  
    # Traverse through all array elements 
    for i in range(n-1): 
    # range(n) also work but outer loop will repeat one time more than needed. 
  
        # Last i elements are already in place 
        for j in range(0, n-i-1): 
  
            # traverse the array from 0 to n-i-1 
            # Swap if the element found is greater 
            # than the next element 
            if arr[j] > arr[j+1] : 
                arr[j], arr[j+1] = arr[j+1], arr[j] 


# Driver code to test above 
arr = [64, 34, 25, 12, 22, 11, 90] 
  
bubbleSort(arr) 
  
print ("Sorted array is:") 
for i in range(len(arr)): 
    print ("%d" %arr[i])
```
