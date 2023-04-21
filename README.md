# Homomorphic-Encryption-for-Facial-Recoginition


This is a demo code that demonstrates how face recognition can be performed using homomorphic encryption. Homomorphic encryption is a technique that allows computations to be performed on encrypted data without decrypting it, ensuring privacy and security of the data.

This demo code performs face recognition using the Facenet model to extract face embeddings, and then uses homomorphic encryption to compare the embeddings of two faces and determine if they belong to the same person or not.

## Requirements
The following libraries are required to run this code:

TenSeal - A library for homomorphic encryption
deepface - A facial recognition library that uses the Facenet model
base64
math
## Usage
Clone this repository to your local machine.
Install the required libraries using the command pip install -r requirements.txt.
Place two images of faces that you want to compare in the images directory.
Run the face_recognition.py script.
The script will perform the following steps:
Use the Facenet model to extract face embeddings from the two images.
Initialize a homomorphic encryption context and generate Galois keys.
Encrypt the face embeddings using the homomorphic encryption context.
Compare the encrypted face embeddings and determine if they belong to the same person or not.
Print the result of the face recognition.
The result of the face recognition will be printed in the terminal.
## Limitations
Homomorphic encryption is a computationally expensive technique and is not suitable for real-time face recognition applications. This demo code is intended for educational purposes only and should not be used for any production-level applications.

# Sources

[Sefik Ilkin Serengil](https://sefiks.com/2021/12/01/homomorphic-facial-recognition-with-tenseal/)
