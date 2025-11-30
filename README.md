Abstract
Ensuring the security of data transmission is crucial in resource-sharing over data
communication networks. This paper proposes a solution for securely transmitting sensitive
information by integrating encryption and steganography. The process starts with the sender
inputting a plaintext message through a Java-based graphical user interface (GUI). The message
is then converted into ASCII integer values and encrypted using the RSA algorithm, ensuring
confidentiality and integrity. To further conceal the encrypted data, the system employs
steganography, embedding the encoded message within the RGB color channels of an image.
The intensity levels of the red, green, and blue colors are adjusted to hide the encrypted data,
producing an image that appears normal to the human eye. For added security, the image is
embedded in a Microsoft Word document, containing unrelated content to further obscure the
presence of hidden data. This multi-layered approach ensures that, even if intercepted, the hidden
message remains undetectable without knowledge of the encryption and steganography methods
used. The recipient can extract the image, decrypt the data using RSA, and recover the original
message. By combining RSA encryption with text-image-based steganography, this method
provides secure, covert, and reliable transmission of sensitive information.
Key words: RSA Cryptography, Steganography, Text Cover, RGB Encoding.
