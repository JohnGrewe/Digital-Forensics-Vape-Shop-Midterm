

![[Pasted image 20241017081345.png]]
Made a copy of the doc file and removed the multiple lines of zeroes from the file



put doc contents into a text file called shewasmine

![[Pasted image 20241017100042.png]]
found invalid hex values

![[Pasted image 20241020132929.png]]

The hex in the word file also seems to be filled with valid hex values that muddy up the image

![[Pasted image 20241020133040.png]]![[Pasted image 20241020133524.png]]



repeated hex values, probably anti-forensics tactics
Removed them
![[Pasted image 20241020133613.png]]

![[Pasted image 20241020133646.png]]

Decided to backtrack and check the file again since this didnt seem to work



![[Pasted image 20241020185940.png]]
Original had xx and I removed it and put into HxD

![[Pasted image 20241020185903.png]]Saw evidence of potential anti-forensics with the words: She was mine!

![[Pasted image 20241020190057.png]]

Got rid of all hex data before the FF D8 FF E0

![[capturedimage.jpg]]
Got an image with the words: she was mine

Initial hex values that repeated that I thought to be anti-forensics techniques may be corruption of the data, investigators can look further if they want to, but the only anti-forensics seems to be the hex data at the start


![[Pasted image 20241020200432.png]]
0a18f7476d484a461afc9b1ae0a1728d
98cd849a04ce375bd07e2b4c02e9dbc4833d0bc94e9598b784001227ef8eea03
