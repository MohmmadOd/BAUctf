# BAUctf
#docm.com 
Digital forensics
# python code to decrypt AES  algorithm
from Crypto.Cipher import AES
import base64

encrypted_data ="EN7Ct+/txesp5yYm7NeZqH48jegb3fV8C9WOfIq0jAm4"
key = base64.b64decode("xtrqHOKJoDkhWNGWhE6fIg==")
iv = base64.b64decode("CsBfLXk4EOsQZT3VMjAV8A==")


cipher = AES.new(key, AES.MODE_CFB, iv=iv)
decrypted_data = cipher.decrypt(base64.b64decode(encrypted_data))


print("Decrypted data:", decrypted_data.decode("latin1"))
