# LabReport3
## Part 1
### Failure inducing input
```
@Test 
public void testReverseInPlaceFailure() {
  int[] input = {1, 2, 3, 4, 5, 6}; 
  ArrayExamples.reverseInPlace(input);
  assertArrayEquals(new int[]{6, 5, 4, 3, 2, 1}, input);
}
```
### Non failure inducing input
```
@Test 
public void testReverseInPlaceFailure() {
  int[] input = {2,2,2}; 
  ArrayExamples.reverseInPlace(input);
  assertArrayEquals(new int[]{2,2,2}, input); 
}
```
### Symptom
![Image](IMG_8164.JPG)
### bug and solution 
```
arr[i] = arr[arr.length - i - 1];
```
```
temp = arr[i];
arr[i] = arr[arr.length - i - 1];
arr[arr.length - i - 1] = temp;
```
This fixes the solution because in the initial code the array was getting overwritten as the elements were being assigned new positions in the now reversed array. So they were being assigned the wrong position. In the fixed code there is a temporary variable that holds the value of the current element being swicthed. This ensures that each elemnt can be placed in the correct reversed position.

## Part 2 - Grep
### `-r`
### `-i`
### `-c`
