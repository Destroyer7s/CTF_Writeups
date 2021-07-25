For this one we are only given the link.

![alt text](https://github.com/Destroyer7s/CTF_Writeups/blob/main/picoCTF/Some%20Assembly%20Required%201/Some%20Assembly%20Required%201%20.png)


I was just doing my usual poking around using inspect element when I stumbled apon what was in the networks tab. I saw `/index.html` and didn't find much of use and thought I would continue looking through the other entries in the networks tab just for kicks but ended up finding something useful. 

![alt text](https://github.com/Destroyer7s/CTF_Writeups/blob/main/picoCTF/Some%20Assembly%20Required%201/Some%20Assembly%20Required%201.png)

I saw an interesting mix of information all in a list. I then stumbled apon the `./JIFxzHyW8W` entry in the list and then tried it in the url as a replacment for the original `/index.html` and was able to download a file.

![alt text](https://github.com/Destroyer7s/CTF_Writeups/blob/main/picoCTF/Some%20Assembly%20Required%201/Some%20Assembly%20Required%201%20networks.png)


I opened it in a text editor and there was the flag.

![alt text](https://github.com/Destroyer7s/CTF_Writeups/blob/main/picoCTF/Some%20Assembly%20Required%201/Some%20Assembly%20Required%201%20text.png)


Flag: `picoCTF{d88090e679c48f3945fcaa6a7d6d70c5}`
