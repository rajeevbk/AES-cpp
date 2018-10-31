# AES-cpp
C++ Implementation of Advanced Encryption Standard (AES) using crypto++ (Ubuntu) 
 
 **Install crypto++ for Ubuntu
 
    $ sudo apt-get install libcrypto++-dev libcrypto++-doc libcrypto++-utils
    
 **Check where the library is installed
   
    $ whereis crypto++  # mine gave /usr/include/crypto++ so I will use this as the path for the build command below
    
    
 **Build and run
 
    $ g++ -o aes aes.cpp -L/usr/include/crypto++ -lcrypto++  # make sure you have the correct path, this creates the executable aes
    $ ./aes 
