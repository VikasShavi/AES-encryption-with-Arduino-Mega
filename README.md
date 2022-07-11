<h1> AES-encryption-with-Arduino-Mega </h1>
<h3>We can exchange data with encryption between two arduino mega.</h3>

<h3>Imp Note: </h3>     
            It is still in development. The adding of 128 bit key is still left.

<h3>Completed Part: </h3>

1. Format input into 4x4 matrix(each unit of size 1 byte)

2. Byte Sub: Each value of unit is replaced with corresponding [SBox](https://user-images.githubusercontent.com/83757578/178215026-008ac857-0a64-43d5-8a03-933dee728fde.png) value.

3. Shift Row: It performs a circular shift of each rows a/c with their row numbers.

4. Mix Columns: Here, the input matrix is multiplied with another predefined matrix over Galois Field.
                     
