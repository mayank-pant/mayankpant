# Page 2

## Another heading

Some example text and some `code`

### code

whole code block
```java title="Arrays" linenums="1" hl_lines="2 3"
// Convert List<int[]> to int[][]
int[][] arrayOfArrays = listOfArrays.stream()
.toArray(int[][]::new);

// Print the resulting int[][]
Arrays.stream(arrayOfArrays)
    .map(Arrays::toString)
    .forEach(System.out::println);

// print int[]
int[] arr = new int[5]{1,2,3,4,5};
Arrays.stream()
	.forEach(System.out::println);
```

### emoji

:smile:

:fontawesome-regular-face-laugh-wink:

:fontawesome-brands-twitter:{ .twitter }

:octicons-heart-fill-24:{ .heart }