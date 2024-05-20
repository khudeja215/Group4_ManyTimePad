# Group4_ManyTimePad
Group 4: Emil, Rene, Karan and Khudeja


Briefly inspect the ciphertext to see if you can identify patterns that may hint some things about their origin.
--We inspected the text and noticed that all messages were of different length, second being the longest.

Research based on what we know bout the messages to find clues to help come up with a theory and game plan to complete your task.
1. we researched and figured that when two messages are XOR'd using the same key, the key cancels out. M1+K+K+M2 = M1+ M2
2. XOR message 1 to XOR messsage 2 resulted in
   50602061d07035f4e3553501400004c1e4f1f01451359540c5804110c1c47560a1415491b06454f0e45040816431b144f0f4900450d1501094c1b16550f0b4e151e03031b450b4e020c1a124f020a0a4d09071f16003a0e5011114501494e1655105f0301522a4c2a4d6533114b0e2005151d11014b41402b48260d071a03064b00175c04445920490659530800415e025e540a1a0c5f0a0c5b0f1b0206090a1d0a184c0153034e


Write a program in Rust that finds the key to generate the plaintext from the provided cipher texts.
The general steps are: code attached

Find the length of the longest input cipher text. 
Generate a key of that length.
Find what the correct key is...
Note that this task is intended to be a bit vague, give it your best effort. We will be sharing hints as time progresses for everyone. Don't hesitate to ask for support if you're feeling stuck, or just ask your peers!

