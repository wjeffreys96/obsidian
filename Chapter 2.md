## Keys, Satellite Data, and Records

**Keys**: Associated with satellite data, they are numbers that a sorting algorithm uses to sort data.

**Satellite Data**: The data that a key is linked to in a record.

**Record**: A key with its associated satellite data.

## Insertion Sort

**Parameters**: A: The array to be sorted, n: the length of the array.

```
For i = 2 to n:
	key = A[i]
	// Insert A[i] into the sorted subarray A[1:i-1]
	j = i - 1
	while j > 0 and A[j] > key
		A[j+1] = A[j]
		j = j-1
	A[j+1] = key	
```

