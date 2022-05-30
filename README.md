# UNICODE-to-ASCII-Replace-Bad-Characters-like-xe2-x84-xa2-in-Python
A quick Function for UNICODE to ASCII Replace (Bad Characters like '\xe2\x84\xa2') in Python
# Below is the Function: 

def unicodetoascii(bstr):

    ByteString = (bstr.
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
            replace(b'\\xe2\\x81\\xbe', b")")

                 )
    return ByteString
