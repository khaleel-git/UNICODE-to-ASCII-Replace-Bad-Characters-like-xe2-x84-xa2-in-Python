# UNICODE-to-ASCII-Replace-Bad-Characters-like-xe2-x84-xa2-in-Python
A quick Function for UNICODE to ASCII Replace (Bad Characters like '\xe2\x84\xa2') in Python

# Below are the two Functions:
# (1) -> First Function is for ByteString
def unicodetoascii(ByteStr):
    finalByteString = (ByteStr.
    replace(b'\\xe2\\x80\\x99', b"'").
    replace(b'\\xc3\\xa9', b'e').
    replace(b'\\xe2\\x80\\x90', b'-').
    replace(b'\\xe2\\x80\\x91', b'-').
    replace(b'\\xe2\\x80\\x92', b'-').
    replace(b'\\xe2\\x80\\x93', b'-').
    replace(b'\\xe2\\x80\\x94', b'-').
    replace(b'\\xe2\\x80\\x94', b'-').
    replace(b'\\xe2\\x80\\x98', b"'").
    replace(b'\\xe2\\x80\\x9b', b"'").
    replace(b'\\xe2\\x80\\x9c', b'"').
    replace(b'\\xe2\\x80\\x9c', b'"').
    replace(b'\\xe2\\x80\\x9d', b'"').
    replace(b'\\xe2\\x80\\x9e', b'"').
    replace(b'\\xe2\\x80\\x9f', b'"').
    replace(b'\\xe2\\x80\\xa6', b'...').
    replace(b'\\xe2\\x80\\xb2', b"'").
    replace(b'\\xe2\\x80\\xb3', b"'").
    replace(b'\\xe2\\x80\\xb4', b"'").
    replace(b'\\xe2\\x80\\xb5', b"'").
    replace(b'\\xe2\\x80\\xb6', b"'").
    replace(b'\\xe2\\x80\\xb7', b"'").
    replace(b'\\xe2\\x81\\xba', b"+").
    replace(b'\\xe2\\x81\\xbb', b"-").
    replace(b'\\xe2\\x81\\xbc', b"=").
    replace(b'\\xe2\\x81\\xbd', b"(").
    replace(b'\\xe2\\x81\\xbe', b")"))
    return finalByteString
    
# (2) -> Second Function is for Simple String
def unicodetoascii(str):
    finalString = (str.
    replace('\\xe2\\x80\\x99', "'").
    replace('\\xc3\\xa9', 'e').
    replace('\\xe2\\x80\\x90', '-').
    replace('\\xe2\\x80\\x91', '-').
    replace('\\xe2\\x80\\x92', '-').
    replace('\\xe2\\x80\\x93', '-').
    replace('\\xe2\\x80\\x94', '-').
    replace('\\xe2\\x80\\x94', '-').
    replace('\\xe2\\x80\\x98', "'").
    replace('\\xe2\\x80\\x9b', "'").
    replace('\\xe2\\x80\\x9c', '"').
    replace('\\xe2\\x80\\x9c', '"').
    replace('\\xe2\\x80\\x9d', '"').
    replace('\\xe2\\x80\\x9e', '"').
    replace('\\xe2\\x80\\x9f', '"').
    replace('\\xe2\\x80\\xa6', '...').#
    replace('\\xe2\\x80\\xb2', "'").
    replace('\\xe2\\x80\\xb3', "'").
    replace('\\xe2\\x80\\xb4', "'").
    replace('\\xe2\\x80\\xb5', "'").
    replace('\\xe2\\x80\\xb6', "'").
    replace('\\xe2\\x80\\xb7', "'").
    replace('\\xe2\\x81\\xba', "+").
    replace('\\xe2\\x81\\xbb', "-").
    replace('\\xe2\\x81\\xbc', "=").
    replace('\\xe2\\x81\\xbd', "(").
    replace('\\xe2\\x81\\xbe', ")"))
    
    return finalString
 
# Explanation:
-> dot (.) is used to do a new line 
-> funciton starts from def (a simple python function)
