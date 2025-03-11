# Hash-Lab
A small lab that demonstates use of hash commands using certutil.

# How is hashing useful?
Hashing a file provides a checksum of characters for a file. It provides integrity. If someone modifies the file, a hash command can be ran and the 
new hash checksum will be completely different from the original. This can show if the file is still authentic or it has been modified.

# My Process
1. Create a text document and put any content in the file and save.
2. Ensure you know the file path when you open the command prompt.
3. Navigate to the directory where the file you are testing is located.
4. Use the following command: certutil -hashfile [filename] [MD5/SHA1/SHA512]
5. This will generate a checksum of some size of bits depending on the hash algorithm selected.
6. Now, go back to the file and modify it. Run the command in the command prompt. The hash will be completely different.
