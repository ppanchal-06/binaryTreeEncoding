# binaryTreeEncoding

The 16 bit data stream is entered through the variable inputString. 

The  function binaryTreeEncoder() takes in the parameter of inputString to encode the given string. The function returns the encoded string encodedstring.
Additionally, another function decodeKey() takes in the parameter of inputString to create the decoding key for the bit stream. 

To decode the string to the original data stream, use the function binaryTreeDecoder(). This function takes in the parameter of the decodekey, the start and ending index of the bit stream, and the current decoded string. When calling the function for the first time you only need to input the decodekey parameter. All other parameters are defaulted and adjusted when called recursively within the function. 

EXAMPLE of use: 
inputString = "0011000000011000"


-- encode the string---


binaryTreeEncoder(inputString)


decode_key(inputString)


--to decode the string--


binaryTreeDecoder("111001111101011010")
