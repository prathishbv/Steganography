# LSB Steganography

This is the command line application for hiding a message in a image using LSB Steganography

# Installation:
	The project can run in Python 2.7 and above.
	
# Clone the repository
```
git clone https://github.com/prathishbv/Steganography.git
```

# Install the requirements if you need to  execute them as python files for reference:
```
pip install stegano
```

# Navigate to the dist folder by giving
```
cd Steganography
```

# File Structure and explanation 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; I have Used LSB steganography here. In a Greyscale image, each pixel is represented by 8 bits, while in a RGB it is 24 bits
<br />
Suppose the following are some of the bits in a Grayscale image
<br />
11110011<br />
11011011<br />
10110110<br />
11011100<br />
11011111<br />
11010111<br />
00100110<br />
01000011<br />
<br />
You wish to hide "A" in it. The ascii value of "A" is 10000001.<br />
The algorithm simply replaces the last bit of the bytes with the consecutive bits of the letter "A", Giving us
<br />
11110011<br />
11011010<br />
10110110<br />
11011100<br />
11011110<br />
11010110<br />
00100110<br />
01000011<br />


# Points to note:
- This might not be a full-fledged project.
- It can be extendable if needed.
- If you need to know about how every sector works in this application, you might need a python interpreter and the required modules.


