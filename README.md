# Secure-Audio-Transmission-using-AES-and-Modified-RSA-
When Audio messages are not encrypted, they are susceptible to hackers and 
third party. Man-in- the-Middle attacks are very common and easy to implement. 
Thus any third party can access your voice recordings and audio. The existing 
audio encryption protocols are slow and space intensive. They need a considerate 
amount of data to be processed and encrypted. The entire process is time 
intensive. Security is another issue. The standard protocols are not secure enough
to be implemented on large scale applications without affecting the performance. 
We need an algorithm with stronger encryption protocols. For Some Algorithms 
The audio data is stored as coordinates which leads to data expansion. Elliptic 
curves have large modulo prime value, so for every small integer representation 
of a message, the expansion in cipher text is massive.

# METHODOLOGY:
• An audio file of .wav format is taken and then using hybrid algorithm (block 
cipher algorithm) is used for encryption. The audio file, an 8 bit .wav file is 
taken and converted to its numeric equivalent for it to be encrypted.
• For encrypting the audio file, it is converted into its numpy array equivalent 
by using the scipy library and then this array of data is encrypted using 
combination of this algorithm. The encrypted file is then decrypted back by 
removing the noise added in the first place.
• The file used is a .wav file. Waveform audio file format was developed by 
Microsoft and IBM and is the main audio format used over the windows 
operating system.
• The bitstream encoding is the linear pulse-code modulation (LPCM) format. 
The file encrypted is an 8 bit audio file.
• For Voice message/data we will use python speechrecognition and pyaudio 
modules.
• Speech to text translation: This is done with the help of Google Speech 
Recognition. This requires an active internet connection to work.
