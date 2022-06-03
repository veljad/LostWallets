# Challenge LostWallets
![mii](https://user-images.githubusercontent.com/82582647/170888552-9dbcbde8-8380-4d39-b761-22178e3cc67f.png)</br>
Find password get 50% balance</br></br>

See [**TABLE**](https://github.com/phrutis/LostWallets/blob/main/table.md) with more than 150 wallets with amounts.

## How to search for a password
Download the latest version of hashcat [**here**](https://github.com/hashcat/hashcat/releases)</br>
An example of using masks in hashcat is [**here**](https://cheatsheet.haax.fr/passcracking-hashfiles/hashcat_cheatsheet/)</br>
The hashes of the passwords from all wallets is in the file [hash.txt](https://github.com/phrutis/LostWallets/blob/main/hash.txt)</br>

## Example of starting a search
TEST: ```hashcat.exe -m 11300 -a 3 test.txt foot?l?l?l?l -D 2 -w 3```</br>
Examples:</br>
Run: ```hashcat.exe -m 11300 -a 3 hash.txt ?a?a?a?a?a?a?a?a -D 2 -w 3```</br>
Run: ```hashcat.exe -m 11300 -a 7 --increment hash.txt -1 ?l?d ?l?l?l?l?1?1?1?1 prefix.txt -D 2 -w 3```</br>
Run: ```hashcat.exe -m 11300 -a 1 hash.txt WORDLIST.txt WORDLIST2.txt -D 2 -w 3 -S```</br>
Use your password search prefixes by mask or [dictionaries](https://www.weakpass.com/wordlist)</br>

If you manage to find the passwoed, write to me in telegram ```phrutis```</br>
Do not write me questions, look for answers on the [forum](https://hashcat.net/forum/)</br>

## Frequently asked Questions
**Are your wallets real?**</br>

99% - YES</br>
Wallets were maximally checked for validity.</br>
Coins were sent to some dubious wallets for verification.</br>
There is no way to verify wallet.dat is 100%</br>
This can only be done if the correct password is entered.<hr>

**How do you have so many wallets?**</br>

Jacks were presented to me by various hunters for 25% of the amount of the find.</br>
Hunters received wallet.dat by exchanging with other hunters.<hr>

**Any passwords hints?**</br>

Maybe it's an email ?</br>
Possibly 12 capital letters ?</br>
Possibly word + word + 2011 ?</br>
They are not exact, come up with your own combinations<hr>

**If I find. What are the guarantees of paying me 50% ?**</br>

If you find the hash password.</br>
Write to me in telegram ```phrutis```</br>
After agreeing, and receiving your BTC address from you.</br>
Sending coins to 3 addresses will be prepared.</br>
Your address is 50% 1......</br>
Owner address 25% (btc address from table)</br>
My address is 25% bc1qh2mvnf5fujg93mwl8pe688yucaw9sflmwsukz9</br>

A password will be required to confirm the transfer.</br>
I give you the id of a teamviewer (Windows remote desktop) running bitcoin core.</br>
You connect, you see the active bitcoin core what and where it is sent. </br>
Check your address, enter your password and click send transfer.</br>
So there will be a guarantee and security for all participants.</br>
The characters are hidden in the input window.</br>
An example of a screenshot of entering a password</br>
![out](https://user-images.githubusercontent.com/82582647/171352391-5859c01c-8b91-4e8b-9664-1b1d75231d69.png)
<hr>

**I have a wallet.dat I would like to exchange with you.**</br>

Exchange according to the logic of the challenge is not possible.</br>
Perhaps you have found the password and want to get the wallet.dat you need to collect the full amount.<hr>

**I have an old wallet.dat (not from a table) want 25%**</br>

You can contact me in telegram ```phrutis```</br>
Provide me with the old wallet.dat</br>
After verification, it will be added to the table with your btc address.</br>
If hunters find password you will get 25%<hr>

**I have a wallet.dat with the same hex, there is a different amount, it's empty, it's a fake?**</br>

You may have an older version of wallet.dat</br>
There is a newer one in the challenge.</br>
In a later version, the user could add a new address and receive coins on it.</br>
The old version of wallet.dat does not have this address.</br>
Or vice versa.<hr>

**Why does the number of hashes in a file change?**</br>

New hashes may be added to the hash.txt file.</br>
Or not relevant, doubtful ones will be deleted.</br>
Therefore, update this file at home more often.<hr>

**I want to look only for jacks with a large amount, so the speed will be higher.**</br>

You can search as you feel is correct.</br>
You can use at least one hash.</br>
More chances with a bigger list.<hr>

**Sell me all your wallets**</br>

I don't sell or buy wallet.dat</br>
And I do not advise you to buy.<hr>




