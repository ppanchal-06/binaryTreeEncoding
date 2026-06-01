# binaryTreeEncoding

The 16 bit data string is entered through the variable inputString. 

The  function binaryTreeEncoder() takes in the parameter of inputString to encode the given string. The function returns the encoded string encodedstring.
Additionally, another function decodeKey() takes in the parameter of inputString to create the decoding key for the bit string. 

To decode the string to the original data string, use the function binaryTreeDecoder(). This function takes in the parameter of the decodekey, the start and ending index of the bit string, and the current decoded string. When calling the function for the first time you only need to input the decodekey parameter. All other parameters are defaulted and adjusted when called recursively within the function. The function returns the original bit string as well as the length in the format decoded string, length

EXAMPLE of use: 
inputString = "0011000000011000"


-- encode the string---


binaryTreeEncoder(inputString)

decode_key(inputString)


--to decode the string--


binaryTreeDecoder("111001111101011010")



If using code directly after downloading run all blocks. The first block will print the encoded string and decoded key in the following format: encoded string, decode key. The second block will print the decoded input string.
