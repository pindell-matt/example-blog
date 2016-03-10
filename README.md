# Breaking the Enigma Machine

During the summer between Junior and Senior year of college, I was privliedged to have the experience of interning at the National Cryptologic Museum at Ft. Meade in Maryland. Tucked away in a converted hotel beside the National Security Agency, the National Cryptologic Museum is a little known treasure - most often eclipsed by the more well known (and equally excellent) free museum options in the D.C. region - even as a History Major in Maryland, I had never heard about it's existence until mere months before applying for the internship.

Over the course of my time at the museum, I learned about the history of cryptology, provided guided tours, and assisted off-site presentations that featured some of the museums many assets. One of the shining exhibits both in-museum and at those off-site presentations was the Enigma Machine.

The [Enigma Machine](https://en.wikipedia.org/wiki/Enigma_machine#Electrical_pathway) is a electro-mechanical rotor cipher machine, known primarily for its role in encrypting Germany's political and military communications in the years leading up to (and including) World War II. 

At first glance, it appears as a simple, portable, rudimentary typewriter - but, instead of printing out letters, the machine encrypts messages on a per-character basis to provide secure communications. A user would type their message in their native tongue and, as they depressed a given key, a different character on a key-map before them would light up, letting them know the matching encoded character. 

This structure is a basic substitution cipher, nothing new to the world of cryptology - but, what differentiated the Enigma was that with each key-press, one of the 7 (or more) rotors housed within the machine would turn - creating an ever shifting substitution cipher that was notoriously hard to crack.

Recently, the Enigma has moved up the pop-culture food chain - after being featured prominently in the Alan Turing biopic, the Imitation Game. And while Turing made fantastic contributions, no one country or team broke the Enigma, rather, it was the concerted efforts of many individuals. Rarely featured are the efforts of [Marian Rejewski](https://en.wikipedia.org/wiki/Cryptanalysis_of_the_Enigma#Polish_breakthrough) and his team of Polish mathematicians who made the first great breakthrough that allowed for later progress. The British Bombe, developed by Turing for the British Government to decrypt Enigma ciphers, was based on the Poles’ own machine, the _bomba kryptologiczna_ (“cryptologic bomb”) in both name and basic functionality.

I’ve since graduated college, and now find myself continuing my education at the Turing School of Software and Design - and was delighted to discover that one of the earliest projects assigned is a rudimentary implementation of the Enigma.


![Alt text](https://theromanroad.files.wordpress.com/2013/01/2009-09-25_3946.jpg)
