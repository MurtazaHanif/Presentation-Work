
The code is compiled using Google colab


Import the hashlib library to use hashing algorithms.

Define a sample message: "Hello World".

Convert the message into bytes using .encode() because hashing functions require byte input.

Apply the SHA-1 hashing algorithm with hashlib.sha1().

Convert the result into a hexadecimal string using .hexdigest().

Print the original message and its SHA-1 hash
