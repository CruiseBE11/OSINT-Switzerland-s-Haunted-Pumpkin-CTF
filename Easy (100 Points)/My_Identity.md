# My Identity (196 Solves) (100 Points)

## Challenge

<img width="1507" height="1506" alt="image" src="https://github.com/user-attachments/assets/59046231-8db8-45b1-9e15-f7ea0802520d" />

We recorded a grave raider last night.

Every information that can lead finding this person is a big help.

Maybe start with the birtday ?

### Flag Format 
hpCTF{YYYYMMDD}

## Solution

Download the Image.

Zooming in, one can see lettering on the wallet.

<img width="809" height="350" alt="image" src="https://github.com/user-attachments/assets/085b2b2c-0a07-46bd-af07-3db1e3980449" />

"6406121F2801012CHE<<<<<<<<<<<<<<<<SCHWEIZER<SAMPLE<<HELVETIA<<<<" can be deciphered from the wallet. <br>

A Google search of Swiss ID stucture provides the following Wikipedia link (you can trust Wiki this time): https://en.wikipedia.org/wiki/Swiss_identity_card 
There are samples provided.

## Swiss ID Cards

<img width="1898" height="1206" alt="image" src="https://github.com/user-attachments/assets/ba6b1a0c-eb4a-48ec-87ee-e3b358755bc5" />

<img width="1910" height="1217" alt="image" src="https://github.com/user-attachments/assets/5a65cd32-ea07-42a9-9295-5f0a22c3e482" />

The example shows a birthday of 01-08-1995.
The ID number on the back shows the first numbers to be 950801 duplicating the birthdate.
We can use this same approch to the first numbers of the ID provided: 640612

<details>
  <summary>Flag</summary>
  hpCTF{19640612}
</details>
