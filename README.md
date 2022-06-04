# Challenge LostWallets
![wallet.dat](https://user-images.githubusercontent.com/82582647/171958917-fc0260dd-1352-4179-ac38-ad8dd16fdeb4.png)</br>
Find password get 50% balance</br></br>

## How to search for a password
Download the latest version of hashcat [**here**](https://github.com/hashcat/hashcat/releases)</br>
An example of using masks in hashcat is [**here**](https://cheatsheet.haax.fr/passcracking-hashfiles/hashcat_cheatsheet/)</br>
The hashes of the passwords from all wallets is in the file [hash.txt](https://github.com/phrutis/LostWallets/blob/main/hash.txt)</br>
Look for the password from all wallets at once, so you will be more likely to find</br>

## Example of starting a search
TEST: ```hashcat.exe -m 11300 -a 3 test.txt foot?l?l?l?l -D 2 -w 3 -o FOUND.txt```</br>
Examples:</br>
Run: ```hashcat.exe -m 11300 -a 3 hash.txt ?a?a?a?a?a?a?a?a -D 2 -w 3 -o FOUND.txt```</br>
Run: ```hashcat.exe -m 11300 -a 7 --increment hash.txt -1 ?l?d ?l?l?l?l?1?1?1?1 prefix.txt -D 2 -w 3 -o FOUND.txt```</br>
Run: ```hashcat.exe -m 11300 -a 1 hash.txt WORDLIST.txt WORDLIST2.txt -D 2 -w 3 -S -o FOUND.txt```</br>
Use your password search prefixes by mask or [dictionaries](https://www.weakpass.com/wordlist)</br>

If you manage to find the passwoed, write to me in telegram ```phrutis```</br>
Do not write me questions, look for answers on the [forum](https://hashcat.net/forum/)</br>

[**Frequently asked Questions**](https://github.com/phrutis/LostWallets#frequently-asked-questions)

### Partner addresses 25%
:one: - 1NEFQpE4qETrAtzzRD8vLGs8FRZmUsV6FF</br>
:two: - bc1qphhedzu5jg7emtw09akwzzdh03mqaytett9zlz</br>
:three: - 1NoName1LLKRfLmoh9jawLWrf6t185bC7v</br>
:four: - bc1qh2mvnf5fujg93mwl8pe688yucaw9sflmwsukz9</br>

|    |  Wallet name    | Balance BTC   | Address     | Your reward | Status | Partner | Update          |
|:---|:----------------|:--------------|:------------|:------------|:-------|:--------|:----------------|
| 1  | wallet_10000.dat| 10000.00417651| [1LfV1tSt3KNyHpFJnAzrqsLFdeD2EvU1MK](https://www.blockchain.com/btc/address/1LfV1tSt3KNyHpFJnAzrqsLFdeD2EvU1MK) | 50%         | :lock: | 3 | 04.06.2022 |
| 2  | 4000.000000.dat | 4000.00222015 | [18eY9oWL2mkXCL1VVwPme2NMmAVhX6EfyM](https://www.blockchain.com/btc/address/18eY9oWL2mkXCL1VVwPme2NMmAVhX6EfyM) | 50%        | :lock: | 2 | 03.06.2022 |
| 3  | 0.00120762.dat | 0.00122539 | [15KeSdnNDVrCQ62TGFRNEx3xedKwXMpvn5](https://www.blockchain.com/btc/address/15KeSdnNDVrCQ62TGFRNEx3xedKwXMpvn5) | 50% | :lock: | 1 | 04.06.2022 |
| 4  | wallet005.dat |  |  | 50% | :lock: | 4 | 00.00.2022 |
| 5  | wallet_2.97.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 6  | wallet_10.83.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 7  | wallet_3.88.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 8  | wallet005.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 9  | wallet_3.98.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 10 | wallet_4.381.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 11 | wallet_10.502.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 12 | wallet_14.35.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 13 | wallet_18.17.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 14 | wallet_22.85.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 15 | wallet_25.999.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 16 | wallet_27.03.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 17 | wallet_31.01.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 18 | wallet_78.569.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 19 | wallet_186.29.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 20 | wallet_177.74.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 21 | wallet_2.16.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 22 | wallet_2.007.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 23 | 0.00900000.dat | 0.00900000 | [16PCQnhRNZoD2jGuCNvfJS3aCZeELsX34A](https://www.blockchain.com/btc/address/16PCQnhRNZoD2jGuCNvfJS3aCZeELsX34A) | 50% | :lock: | 1 | 04.06.2022 |
| 24 | 0.01000000.dat | 0.01000000 | [18MW7RLHthpRDmzcfDjFSaTamxNSSkMs67](https://www.blockchain.com/btc/address/18MW7RLHthpRDmzcfDjFSaTamxNSSkMs67) | 50% | :lock: | 1 | 04.06.2022 |
| 25 | wallet_1.56.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 26 | wallet_50-2.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 27 | new13wallet.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 28 | wallet_42.24.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 29 | new9wallet.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 30 | wallet_50-4.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 31 | wallet_0.072.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 32 | new17wallet.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 33 | new15wallet.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 34 | new7wallet.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 35 | new3wallet.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 36 | new2wallet.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 37 | new1wallet.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 38 | 36.83wallet.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 39 | 30.0.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 40 | 15.99.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 41 | 8.5.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 42 | 4.3.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 43 | 32.2.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 44 | 1.08.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 45 | 1.004wallet.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 46 | 0.0178.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 47 | 0.92.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 48 | 0.01212207.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 49 | 0.01630413.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 50 | 0.01649536.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 51 | 0.04157575.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 52 | 0.06271293.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 53 | 0.21966138.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 54 | 0.36688060.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 55 | 0.53970361.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 56 | 0.92387567.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 57 | 1.00103254.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 58 | 1.09479390.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 59 | 1.39498354.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 60 | 1.44138096.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 61 | 1.65000000.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 62 | 1.83913928.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 63 | 1.83949995.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 64 | 1.84950000.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 65 | 1.92980000.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 66 | 2.00000000.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 67 | 2.03000003.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 68 | 2.04866236.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 69 | 2.05917246.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 70 | 2.28883133.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 71 | 2.29597675.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 72 | 2.40000000.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 73 | 2.50000000.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 74 | 2.53794900.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 75 | 2.68753118.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 76 | 2.69500000.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 77 | 2.74000000.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 78 | 2.74500000.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 79 | 2.82717743.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 80 | 2.96812861.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 81 | 2.97000000.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 82 | 3.01244000.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 83 | 3.02000000.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 84 | 3.08715076.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 85 | 3.17460240.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 86 | 3.36894140.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 87 | 3.73979441.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 88 | 3.85090000.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 89 | 4.00043606.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 90 | 4.02219444.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 91 | 4.82537042.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 92 | 4.85582600.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 93 | 5.08877624.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 94 | 5.89290000.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 95 | 6.19445176.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 96 | 6.29000000.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 97 | 6.33560000.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 98 | 6.33718357.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 99 | 7.00000000.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 100 | 8.77089137.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 101 | 11.26827053.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 102 | 12.82192064.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 103 | 13.47094589.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 104 | 13.76858117.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 105 | 14.00010000.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 106 | 14.60000000.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 107 | 14.70456309.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 108 | 15.01812238.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 109 | 15.71719998.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 110 | 15.75044635.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 111 | 16.13643422.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 112 | 16.23030002.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 113 | 17.08998980.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 114 | 17.09000666.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 115 | 17.19060793.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 116 | 17.20100000.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 117 | 17.82021465.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 118 | 18.00000000.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 119 | 18.72704494.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 120 | 19.28011668.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 121 | 19.30000000.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 122 | 19.33608000.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 123 | 19.43300547.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 124 | 19.88790000.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 125 | 20.00241094.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 126 | 20.11001641.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 127 | 21.89679859.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 128 | 25.00101641.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 129 | 48.92440002.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 130 | 50.00000547.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 131 | 50.00001641.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 132 | 50.00002188.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 133 | 50.00003282.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 134 | 50.43201094.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 135 | 52.08001094.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 136 | 52.55001760.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 137 | 73.50781094.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 138 | 74.16883731.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 139 | 77.98600547.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 140 | 78.60361094.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 141 | 87.86507229.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 142 | 91.00501641.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 143 | 108.06001094.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 144 | 129.66226125.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 145 | 130.00000547.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 146 | 159.89913129.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 147 | 180.77714198.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 148 | 198.00412439.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 149 | 200.00224825.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 150 | 252.20004225.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 151 | 300.00055278.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 152 | 319.00053581.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 153 | 340.00283740.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 154 | 405.00120319.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 155 | 2612.0000000.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 156 | 4000.0000000.dat |  |  | 50% | :lock: | 1 | 00.00.2022 |
| 157 | 5000.01168565.dat | 5000.01168565 | [18xGHNrU26w6HSCEL8DD5o1whfiDaYgp6i](https://www.blockchain.com/btc/address/18xGHNrU26w6HSCEL8DD5o1whfiDaYgp6i) | 50% | :lock: | 1 | 04.06.2022 |
| 158 | wallet_108.06.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |
| 159 | wallet_110.dat |  |  | 50% | :lock: | 3 | 00.00.2022 |


## Heshes table

|    | :arrow_up: Wallet password hash by numbers from the table above :arrow_up: |
|:---|:----------------------------------------------------------------------------------------|
| 1 | $bitcoin$64$f0ef639cd01bb26805c190e0aeba006fbdd6b817e0b6634b0fb11944bc0f19eb$16$d2542bb38e0ee061$76753$2$00$2$00 |
| 2 | $bitcoin$64$ff4eb1d017921e0c7023da7e17aa72bd5f11f9025c844865665932125f79f465$16$6b8207637fc796a0$37698$2$00$2$00 |  
| 3 | $bitcoin$64$234bcceda74df69c8107ea28cb7dda04753a8bab324bfdb175d5552558c689c1$16$599c639c12d31797$70564$2$00$2$00 |
| 4 | $bitcoin$64$c14f56ad41053634a95dfb4d7099c5f0d7b291a7d205ea8f489fb43c023dc6c9$16$d4e4996b4e149a40$158666$2$00$2$00 |
| 5 | $bitcoin$64$5188754f6b4942270d8f1dcaa8b1658b5e82fac953a7394dd8a5d0cf622ae70f$16$6cf03da04dc5b899$72580$2$00$2$00 |
| 6 | $bitcoin$64$6942834a1cdda69705d2cf9ebc3a204d5bfa64ff40d81db0bac6ccf63b3aff8f$16$00aa7d8b96e6174d$37698$2$00$2$00 |
| 7 | $bitcoin$64$226093b84d6c3d0eeeb96e3ccece44068769410cb5968b16430a0d1158a6d071$16$4c9e8811f730201c$37698$2$00$2$00 |
| 8 | $bitcoin$64$c14f56ad41053634a95dfb4d7099c5f0d7b291a7d205ea8f489fb43c023dc6c9$16$d4e4996b4e149a40$158666$2$00$2$00 |
| 9 | $bitcoin$64$71fe0d4dc27b24dcd1ea6639d644e8daeff04c38e30d05f0a74b17d28f25667e$16$df6cabc03425d39a$35714$2$00$2$00 |
| 10 | $bitcoin$64$0e7f3dd3368aa563848291d14059ca6b969fdc6567be670d93f982693c4a913b$16$df1b66a2e41c2eb3$35714$2$00$2$00 |
| 11 | $bitcoin$64$93112f8c11e9cbff7561038eddf268827dd38c72354695fc70d4a01102d22c48$16$14bff2455913f62c$25000$2$00$2$00 |
| 12 | $bitcoin$64$deed81af471f5677b7c11a883237b20c9e6b8738e5e65945f4288ece6f413a57$16$f0bdf179fd204a59$35211$2$00$2$00 |
| 13 | $bitcoin$64$27d8eb445a52382c6cfc18b49286087cf12db2e0ef12c77bd726a30cd72cb7ce$16$1d49acbff96eb626$35714$2$00$2$00 |
| 14 | $bitcoin$64$b5360e667fcdccf601d35c5f8bda852de40464373bb79df247c46ac6b97fa76e$16$8ead40334c7161b9$35714$2$00$2$00 |
| 15 | $bitcoin$64$c1f68299d421f5f2bba2947cc84bf1cd5be222b92db11473c25dd6f763ad40f1$16$57f4b89317e7d3ba$132242$2$00$2$00 |
| 16 | $bitcoin$64$023ebec32970c6ec9453b84cea7bc58e92240534408cc6ea4a22cff2c21d0132$16$ef7b10ba55248b66$132242$2$00$2$00 |
| 17 | $bitcoin$64$bbd2f31a2bf33fcaea5d7f70f66cc1cf7273ba891ced76ced406bf762ee6bdba$16$4b495fa46139cf2f$132242$2$00$2$00 |
| 18 | $bitcoin$64$9e8d5b70d45f8fdeded358b8f72f81c0436398a220081a60044dc7bf5f9ea23e$16$cb9c55df52aa906e$35714$2$00$2$00 |
| 19 | $bitcoin$64$f913fa9e5ea97dad615191c23af0f5ebdbe4693ddbea0903d9230832e7ae36c0$16$4cad32d55bbe6595$37167$2$00$2$00 |
| 20 | $bitcoin$64$16f32e8ac625bd85062124bdee0276b74795a535d299118559560cf2f15d332e$16$656dc3e22ca1a711$131578$2$00$2$00 |
| 21 | $bitcoin$64$bfda1e650f5324d5baf7e8436f0bf1982e2d454eca3cec181f85d573217a5f37$16$235a24fb9826bc63$38193$2$00$2$00 |
| 22 | $bitcoin$64$64668bf6d05f12989ac6e9c290948a87a550b057dafc19e8e0647356b10075a6$16$803496cf5f4a82bc$37698$2$00$2$00 |
| 23 | $bitcoin$64$92c8e00c8537624867d7aaff1a31abc72cf1b97cb923cf802aaab551e6f30623$16$cacbf690816bb4f6$76979$2$00$2$00 |
| 24 | $bitcoin$64$3a34378f68fc6b07a19770a5c839450aa3bdc2b96535ec5937d32d70e2f11e72$16$6740187b4c919c9b$66355$2$00$2$00 |
| 25 | $bitcoin$64$f01e1ef5f265eaaffa747fd13abbf4a6df16216ceb99d37d903e5638b5da0144$16$8422e687825ae181$37167$2$00$2$00 |
| 26 | $bitcoin$64$25e8624d377949f36c4fdf104fa7f3ad3307be3499e72cae367f161b38a062d3$16$9d2eb2ad3e972053$37167$2$00$2$00 |
| 27 | $bitcoin$64$1b291d0c84ab8fe6db5e7fd73ef9f43205c4d6460c886152fe3a39d6d7d1fa89$16$29e9634283b5a70d$181332$2$00$2$00 |
| 28 | $bitcoin$64$b5ee3fb4fdb69a11efa972937e2fd0cf10c749b3d0967947205b4710f89fdbb3$16$00878c494362d4ab$35714$2$00$2$00 |
| 29 | $bitcoin$64$27a7ab539edfe15b9fba66454066c7c68ebea4381a6ba6953d95d68e115aaf63$16$f45481b990eff771$54672$2$00$2$00 |
| 30 | $bitcoin$64$9f4ec3cc5df40ab2f7f961023c9bf4fcf410a9c46116cba0212f3095c1b9caaa$16$702f6ebf489b7aeb$72580$2$00$2$00 |
| 31 | $bitcoin$64$617c4b22fabd578e0f4d030245a0cbebd9da426fbee49c2feb885fa190b65096$16$dff2b89e4d885c28$35714$2$00$2$00 |
| 32 | $bitcoin$64$75f6cc8fef63be469e887450e7396927dc5e1808bf5cf5d45f4a2cd035bf5dd4$16$954d0b14f9ca0012$158653$2$00$2$00 |
| 33 | $bitcoin$64$27bea959add4021eb69b58a8932c19f2adb1966b6593450fde759e4d0f05a3b0$16$0b24950ff8e06137$178571$2$00$2$00 |
| 34 | $bitcoin$64$b3842e23f10ac6c033b834965468b6f5a4bd45278ccd8d593ba13e0e5666f62b$16$405ada708a64f160$131944$2$00$2$00 |
| 35 | $bitcoin$64$dede82c6449d5e1638a8e3a26db5c8e73368d139ff7d6fb7b9fc1ce82120f35c$16$fc83158ec483e01a$216173$2$00$2$00 |
| 36 | $bitcoin$64$f6f42a9e0cb0eda2669fa8fb6e8a69ab42c753165427559c4828637f1142fef1$16$4f4624841b9317e4$191354$2$00$2$00 |
| 37 | $bitcoin$64$7f9cfa79f17275c95dc0876283de90f287aece404c1fd11115c059b3d88fd386$16$f328cdce4388a454$105603$2$00$2$00 |
| 38 | $bitcoin$64$5b2f6e4398004a207eea181b9db111971ab9749c19451a5f0926d1000d70b682$16$d72f084441487b68$25000$2$00$2$00 |
| 39 | $bitcoin$64$50bb9ef9cad87bf2b865b060e80c72c52f5ff496dbefa0bcfc6c3b5e0b86050e$16$f63cb4696e604d94$128289$2$00$2$00 |
| 40 | $bitcoin$64$2ecb6691460c19de44584d2b22d201597874ec4ced76c806455e079e6d811da8$16$fbf192d3baf6bb02$126145$2$00$2$00 |
| 41 | $bitcoin$64$ff134f9f03da571e5b256dec561730aaa674ff37d8a698d3c2c5e66fdbb07335$16$125d64b2bab4c437$136217$2$00$2$00 |
| 42 | $bitcoin$64$958ac143fee6e57e819669853da15bc41da8881b3b99d50d26bfa4fa118661ee$16$b6db137df5385a14$59688$2$00$2$00 |
| 43 | $bitcoin$64$8ff0c52d3026ac8b949fdc64444d4daecbde19f8bfb3fb4b3e199fdb5aff8339$16$b5ba03e404f1d79d$125631$2$00$2$00 |
| 44 | $bitcoin$64$9de529051d808b5d34c679c43020a233e6b5161de2e85070127009d61e4c24c8$16$09792b4786f368cb$49019$2$00$2$00 |
| 45 | $bitcoin$64$9269f788d7bcecd411d95cc222c9f0cdf7ebfc6fa33847607f7b8c1338a2c3f8$16$10cb87989a39ef71$60692$2$00$2$00 |
| 46 | $bitcoin$64$3420a7252f5ee93d31ef7734a56f93fd08e0e6ea7a4686e40f0e5e3e972fd6d5$16$885a0196aab916d0$193105$2$00$2$00 |
| 47 | $bitcoin$64$02fac009c7298c142c27aaf52a10b984bb578f124cb1ed0854fe460f16aa9cf4$16$1dabf1816b34e175$62719$2$00$2$00 |
| 48 | $bitcoin$64$1f72bf18ffa4fdc760635d8c13109da196d3dc802d5aabb23fa6c6aaba9a1dbb$16$04436c19f8b3699f$41162$2$00$2$00 |
| 49 | $bitcoin$64$21c25dd14dd7bc7bad4c3fcd9629ee862e0b27307092f25d3e963d76ea5d472b$16$d7cd7e3809ef7edb$81717$2$00$2$00 |
| 50 | $bitcoin$64$c186d4f68030949390af608519d5762a993158d655eb500cc23356324d46f9bb$16$8e75f5e20d006f95$74899$2$00$2$00 |
| 51 | $bitcoin$64$da5d83d08330d95c09b39e7b938a79b2170f39b8abade5a08438bf3efc59578e$16$d98f9e1b60b753b5$50122$2$00$2$00 |
| 52 | $bitcoin$64$b79d2b59e3ea4e90a039aa29e7a13981ce0e452158a77fd8d92fe4b32dbf0b06$16$f8f9e047cbbc102a$54976$2$00$2$00 |
| 53 | $bitcoin$64$825aae165a699d1d4de7fe313ff3afbd7deb58802e0d6cc96da1b158ca6010a4$16$f3a81a82d737a22d$63054$2$00$2$00 |
| 54 | $bitcoin$64$28a5eff3231423506ac1e0775e941ffc261e60dd43978572ca9a515cb39072aa$16$d7a612453f69d549$56140$2$00$2$00 |
| 55 | $bitcoin$64$9810cb6ab1782a996319de81ef4cba2f7b9c97fbb252fc49be3962377405799a$16$7f6fe559a2c604ba$36289$2$00$2$00 |
| 56 | $bitcoin$64$02fac009c7298c142c27aaf52a10b984bb578f124cb1ed0854fe460f16aa9cf4$16$1dabf1816b34e175$62719$2$00$2$00 |
| 57 | $bitcoin$64$01f782c4a3a71e9da3af5f7fe3977f10e9216f239814a45148c0d58ea0b486bb$16$e0eb85213cc20ccc$65828$2$00$2$00 |
| 58 | $bitcoin$64$51307c1824f9756c0542218c6c3054974e07dc5c58f8411173c12f7e938b5f10$16$0f088e5c4d1a0515$62055$2$00$2$00 |
| 59 | $bitcoin$64$65f0d344dcd7181ec223746a84f42b620e550a1019742f495fd76b2578523330$16$d699839d9729686b$60211$2$00$2$00 |
| 60 | $bitcoin$64$44ed889592a8d7b9bf6c8b1ed8bd676ca69a63c866e04f0119c34c1a7a185446$16$9e9ebf3cbd7605d8$64337$2$00$2$00 |
| 61 | $bitcoin$64$cfd9ff763c32192562a8e2a80b2dc2454fd91c22a4896e5a4e4503df011eb299$16$0d0477aa5f576baf$60455$2$00$2$00 |
| 62 | $bitcoin$64$c6c01dbdb35f65adfdf9ab423bb5cc1ac3b4b7969e65d37961272973e0c5e375$16$6bccd28adff9fc07$67908$2$00$2$00 |
| 63 | $bitcoin$64$6bef8568c8f81f067586cb5579b9edbef942c1d87f441b82adc14fd399305880$16$e6753cf77fbccd3a$104326$2$00$2$00 |
| 64 | $bitcoin$64$bb99f6bca2f215c658848ff7ea1c9459e29bbfb17e2cde0ae0a4769edcee0107$16$68d7955607946058$41608$2$00$2$00 |
| 65 | $bitcoin$64$6b180d8285ae3d5ab952950314df765615c5118393edfff5511f5419330a1d8e$16$1bd4e867b0f742b6$36208$2$00$2$00 |
| 66 | $bitcoin$64$7331cec5bbf44062c5488c40815cd2117da80b6e46bf56ad5142f126eb51b412$16$2fd37542ebc0cf7d$65866$2$00$2$00 |
| 67 | $bitcoin$64$c71e083361cd16dfbf5acaa2d0af0532554e1fd6982f6e5341bc5a7d4886080f$16$d6283ab0e04e9b78$63852$2$00$2$00 |
| 68 | $bitcoin$64$500cd102da82a708c81b68711faeb598210f30a0d601bb0e75c7464a4d3c20c2$16$f1fd68a3f791484b$61442$2$00$2$00 |
| 69 | $bitcoin$64$ec3edca5b3aff92ab10ac7681b05ee077681734dfad8b090dfefb969ec26eb4b$16$67201c141a44d1cd$36289$2$00$2$00 |
| 70 | $bitcoin$64$534982bd75fd55de814558f847d48a8805300c9144b557b3f82cbac0ffc66398$16$f1f0b2aa64c3d426$37698$2$00$2$00 |
| 71 | $bitcoin$64$fa7064fb38bd3ae262b2d88d4ba62b4870b23ff326ba14ba60de551fab7a9327$16$460f24cf3825a045$34090$2$00$2$00 |
| 72 | $bitcoin$64$2f77476dd3fd9db01c9d645ea24ec05c5c8125166fc07bac4d8c147c2c84167d$16$35af01fbce5b5e5f$62313$2$00$2$00 |
| 73 | $bitcoin$64$a64fe88a288fb7512b54d7dd64f9641fe2e70919f3c15c8dcc70a512aac166e6$16$dd272ec0ee200a78$77315$2$00$2$00 |
| 74 | $bitcoin$64$2ce3118fd2a87834b49b63916edd4935d89e905c2bedf6c97f19ff466b299b65$16$9480b99863bc4940$38489$2$00$2$00 |
| 75 | $bitcoin$64$b9d677fa8a11b6619cfedca40c837b0d3343ff20df48cf37700394b5b64cf192$16$a80e5f4352c4f324$71314$2$00$2$00 |
| 76 | $bitcoin$64$4d93553d15560f2e50533c3fd271fe41e1cf1baf9dbec1711746a21a42db05dd$16$f16dd4acd044b5c1$101546$2$00$2$00 |
| 77 | $bitcoin$64$0570ebd633691b97f566a8b73147d69723c94ad10b141f1c4d7e3c96bd408096$16$0f5ec00d429b9704$63835$2$00$2$00 |
| 78 | $bitcoin$64$3c7561c0d8ed6700b7e1a48a94077f9595858f07e05fa51c4575e5a9785b9723$16$f93dd4c873efcf97$38657$2$00$2$00 |
| 79 | $bitcoin$64$6d09cc1ed352f52f93ca0ee33a6b0350ce9f9ebfb0ebfcb88f5e41e708fd40c0$16$da73658aa029b6dd$47871$2$00$2$00 |
| 80 | $bitcoin$64$63e3a2b4a51ab13427e0a1e728c903933e87e8621b7d681ad45c4bd025831975$16$cf56402c27786c22$69042$2$00$2$00 |
| 81 | $bitcoin$64$0a5930326e7079600c75fd3bb4608727ee98888100322a4dbfdbe1f88e2e0b21$16$b4198b2d3fceaae7$61763$2$00$2$00 |
| 82 | $bitcoin$64$89cb146e3db70ae648d03266ab4f506e027b57137066c4d888ec66fbfde5236e$16$74752ca5389ef081$70054$2$00$2$00 |
| 83 | $bitcoin$64$70e4c5802b753c0a54bfaed48c660091ee646e86b313a37c7c4fa4b9552369dc$16$6cfd640bb735f660$31609$2$00$2$00 |
| 84 | $bitcoin$64$fbb855a7512b44a6c34c0e762c2844b1c5078a9bf175ccf894f6660660031ecd$16$b2703da18a5ac317$76979$2$00$2$00 |
| 85 | $bitcoin$64$23ca949be014591b7d6084702e54aebdebe5ee3658d7cb45cb2cc502c17ccce2$16$e167a26aaf9a728e$67219$2$00$2$00 |
| 86 | $bitcoin$64$a1a3ef63fba5710a98208a9dffa57d64b2a2d69e475514a1ddd4d178bf04a171$16$4eb9d7607de381ac$71074$2$00$2$00 |
| 87 | $bitcoin$64$7c777ff6ca1be06757120c36eba39c7573a1154cf35277e4740f13b1b44504e4$16$24089973d01d5f0d$82925$2$00$2$00 |
| 88 | $bitcoin$64$895b386376c1ca9c1f8b440ea269eb4a772bcb4b47757c7708a03fd47a8ca3f2$16$d1d93a887220a49f$31249$2$00$2$00 |
| 89 | $bitcoin$64$bcbea16e815204542d0c5c933a9b4082e34ac2143b586c8084bc6519e340375e$16$df41a91be092cb86$64053$2$00$2$00 |
| 90 | $bitcoin$64$b1aefb2665d35512c81f3765cd99d0a7cc1e15fcb741d0f21a46babaf9576cc1$16$6390ddc3df7fbd48$72463$2$00$2$00 |
| 91 | $bitcoin$64$fd1efeee395b9f5167ef5b2d40e6701164bd8fda6f055b21161f0f6b214cfdc5$16$32ddd688dd623687$35714$2$00$2$00 |
| 92 | $bitcoin$64$41f22b8d40dc773fae1acacc0c10c5746e0bf8cac6cee1129ade3b3d49b99a9f$16$fef57fc288239116$130926$2$00$2$00 |
| 93 | $bitcoin$64$aef813b23f8577f617d5d4890c1d769c46cb492e519214eb8d85c6f1606b6b3b$16$de2b3bd38f902753$64425$2$00$2$00 |
| 94 | $bitcoin$64$1d94364372d1cae4bfacbc1ac7722c2bf92a98de47ec2f8ac476119d45d40a60$16$ca471cd3a19b04ff$67917$2$00$2$00 |
| 95 | $bitcoin$64$04ac3ea427bfa8ddb2c6e10199267cd338cc9b19e4e5ce0806f6078b312604bf$16$b09bc7e9b1c6087e$59659$2$00$2$00 |
| 96 | $bitcoin$64$df4579769ff97a92cb815f8484e16e796df133e84ff392d56eb65399b69be57a$16$5f3ced39d11972bc$77315$2$00$2$00 |
| 97 | $bitcoin$64$6631eda4a5fbaf95d5d4fe18f9b04401fae84adbaf2238f78c1871dcadfde1a8$16$dbd7bd2153d79ff9$47334$2$00$2$00 |
| 98 | $bitcoin$64$829c1c500a6b80ce0f6a622bf77d9ad75fc07abe2753695e8c256bdd5e5ad872$16$e88c5fd7136eb715$52082$2$00$2$00 |
| 99 | $bitcoin$64$f20759bb3249e7f1928373981c4efb014d45b632ed8a3c781f061b92d095888b$16$3ff48fe3e092513b$111555$2$00$2$00 |
| 100 | $bitcoin$64$ef08500b11fda51111e9106ab0bc60fb77870202a7a433abe1dda820be9134f6$16$a962fdb86e3161a4$60692$2$00$2$00 |
| 101 | $bitcoin$64$6b45588e745d8490f2432c68533407e0f2040ff12debd840270f47543ad47c16$16$0af493ab2796f208$99974$2$00$2$00 |
| 102 | $bitcoin$64$b111269df559c2c8929f4e7d82bd627317301d9fdd189b5360153ab28f7d04a0$16$cf488450374c34d5$35714$2$00$2$00 |
| 103 | $bitcoin$64$a056da8f6713a70d9f6b125931ac02a3b89f3aed658ab444b624c740d08460d2$16$ded7ea15fc0ad57c$53205$2$00$2$00 |
| 104 | $bitcoin$64$c4904a4e27e374a782aa9700bc953bea61dc0342f8df97491d229fc6bcd5c641$16$25b711ed92cdf3c3$74899$2$00$2$00 |
| 105 | $bitcoin$64$c00315444e82cc43ec23bea608c7889138a6d73bcdef3ae3526fb64ef79ab0e9$16$f8a9ac6e9be0c72e$74899$2$00$2$00 |
| 106 | $bitcoin$64$44edd3d9e1aca5d3e486e2a43c3c507b475fd6d2235f91394bf96105e78105c9$16$0db9b5dd9f71ba20$61714$2$00$2$00 |
| 107 | $bitcoin$64$5e8a31c248beb652f3403ebab417104a689e8c332c1b439dac8bb80fc92b762e$16$f6a2d85665fd5826$62954$2$00$2$00 |
| 108 | $bitcoin$64$0d620dd9913bb3d0993bc7626bd5b4f388b64440498c4da55b52d53ff2f2d161$16$73b40d780231b8ca$63056$2$00$2$00 |
| 109 | $bitcoin$64$e1fcb6f24724b47a52bb16b9ac6a150454977541f44decb080c63471880e4c1c$16$012f4675057fd231$69491$2$00$2$00 |
| 110 | $bitcoin$64$af049ff75a8d5c1214e252f3c926b7b63e20f78f07fd411ca04140f272e557ae$16$999bf4729b971c7e$67169$2$00$2$00 |
| 111 | $bitcoin$64$00b0d3980bab3d9b3694fbed9e9082bd2fdf9b5ff8a4fd05b6599b556c6b1c67$16$22589d3f997c387f$60435$2$00$2$00 |
| 112 | $bitcoin$64$beee3a4519bd860e383f3a114b3a08cb4e7199248ea06d392fd9af52c042b4db$16$b6a4588ae3ba3e36$60714$2$00$2$00 |
| 113 | $bitcoin$64$0b7b5199cf24c104c1b130906774f2843d1f01ae62c8fff935c7afc3411dc8e9$16$66934f0863dd4482$63268$2$00$2$00 |
| 114 | $bitcoin$64$7f126bc43475c2fa85d7831a854d87a0ede3d742f6da71f79ccb65c284c6b0ba$16$fa85aa2d5eacee31$67271$2$00$2$00 |
| 115 | $bitcoin$64$54c20b76a774c8a9064e42d63ce98ae531b7c011483d25c42ad02ef0456aa376$16$e759f4549f41b949$77315$2$00$2$00 |
| 116 | $bitcoin$64$8d167901e4f604a677eddb21460cddc4f5603f3b21ebe33ff726d9077ee07cdb$16$722cb04e0e8fa285$66170$2$00$2$00 |
| 117 | $bitcoin$64$64f7392c7fa156c85cc89d44edd6d27ddd0d68cb78a56a8ad60cd732fe569c01$16$2e7c23cc7fc0b14a$60692$2$00$2$00 |
| 118 | $bitcoin$64$947f45d86f69bea47315abe26a0fd2eca5900909cb3d9fa47db36fab5584cccb$16$f04384fc94d2ba53$62973$2$00$2$00 |
| 119 | $bitcoin$64$3662b157e4eecaf689bfc43252fba54d915592fd2332dd50128d61462f3dba64$16$a9cef4ffcfa6e71f$38193$2$00$2$00 |
| 120 | $bitcoin$64$f7ffc0d93ca4cef66464c5c5461889f5cbaa2bcfc09d2a01df216241d2e2be8e$16$1f1e4d7daa8cc4a1$67520$2$00$2$00 |
| 121 | $bitcoin$64$9a7accab21442dd5c169eb408dc406c6cd77ccf39e9b3a1cf533bf867686c893$16$c7ee4cb0135cfabb$68810$2$00$2$00 |
| 122 | $bitcoin$64$f5a420086263fe96bf02389428e2a9bb043f52ecd0d09a15e99791e68153d98b$16$332e0d9db3c0ee6a$30841$2$00$2$00 |
| 123 | $bitcoin$64$8109c279503278b8cdef8b67a817ab04c77c06dd7cc83b76fbe7f3d3f1d4f53d$16$5e4a6c017108845b$66056$2$00$2$00 |
| 124 | $bitcoin$64$a37dc249738892ddfee64fd9eef6a164c334b2828e24738f53bc22399f0f24a5$16$739dfbe436b4d196$38193$2$00$2$00 |
| 125 | $bitcoin$64$7120f443a02024283d9a4fef4c2c7167c2df239f4eeac4541a7327fab1ac05e0$16$88e39336106da6be$60692$2$00$2$00 |
| 126 | $bitcoin$64$3e65e817d605b9d5d0b54bc8418a27aa104847dc59d664c6928601a8098927ee$16$5bcbad051d845552$60692$2$00$2$00 |
| 127 | $bitcoin$64$4e5275fdaa62b805f8866082a87d953cca0c11e8e9d6511ab8a88690e107cd6d$16$802b35126a909e0f$81065$2$00$2$00 |
| 128 | $bitcoin$64$144cc82f35ee18d502a01b826f5c47d201fad3167d26fe252595cf9c892584fa$16$af7ee951c6e05e80$33610$2$00$2$00 |
| 129 | $bitcoin$64$f011045b52a39829f0e053f35b594c18c02bbcd936994279201cbd8e07f27197$16$b7445bc82d7e62fa$38043$2$00$2$00 |
| 130 | $bitcoin$64$45abd6ebb0035af6c4ca2045a2bce9f663b763dc8afb558326752011ee85aa68$16$21eb684dadd49089$70727$2$00$2$00 |
| 131 | $bitcoin$64$29ce72e5f11715f757021bc614fc29ec759cc614052d877ab050888f50245f82$16$2f756cb410d49abc$68432$2$00$2$00 |
| 132 | $bitcoin$64$f95b995bd952613281a7fbf16a37abfa342d579a651d2fcf32c21d7479fe587e$16$c61ebd84c4990e1f$70312$2$00$2$00 |
| 133 | $bitcoin$64$3335c9e0dfd882b72d86f2b0412463e185768576771c6489e6fad6e4caec94c7$16$3365bac0544c6cc0$37167$2$00$2$00 |
| 134 | $bitcoin$64$b4ec55497c544b4e6a7435fb6f30205c2baf86c9f533da2bbfa1e6f9fabdf330$16$3795a68bc27c5915$35537$2$00$2$00 |
| 135 | $bitcoin$64$b1ed5af135a124b3041d79bb43074ae1054d3476693194d55d59c70252df19d6$16$aea459993c7600fe$38193$2$00$2$00 |
| 136 | $bitcoin$64$a0af3fa5006030e0edce5bf0931bebe7e0b27a694d314a68790d21347d79a657$16$2142112a50c1e140$73529$2$00$2$00 |
| 137 | $bitcoin$64$eb22cf4ac8e7c5231096f7ce560803116345ba6cb0104f1488803e57f1d18e5c$16$8c0643774dcd2e5a$68452$2$00$2$00 |
| 138 | $bitcoin$64$f8e443e6d6491d625a2ea48ddacffe0d1312ee59d80849d7f8cdb94d09931e84$16$7036c30511f8672b$36571$2$00$2$00 |
| 139 | $bitcoin$64$528c67300053686ddcc5bde2ab6cd7dfa451a56e9c08aa27dcf1cc276cb3df48$16$8be30851d53f2928$40948$2$00$2$00 |
| 140 | $bitcoin$64$feb27bbab8b0a6f15b26f418c10a20bb73ba287d439ae5ab6ceb0287e731f55a$16$0af493ab2796f208$73689$2$00$2$00 |
| 141 | $bitcoin$64$0d79241a6ba712a0d55440104d01811ccdf4d4294bdd89748bbbb6ef46dc15d7$16$646ff236cc6fe1e9$83181$2$00$2$00 |
| 142 | $bitcoin$64$e5f72c841730fd7e6965cb5c415016aa48c69757bcdf8c922a809d50af4c6c06$16$eddeaee1261a64e0$47530$2$00$2$00 |
| 143 | $bitcoin$64$e028fcb19d419b301a45f9850b750ad1ceaa8db1967b9fb8bbc4456ed5de580a$16$cf373e94a48bdb1f$35714$2$00$2$00 |
| 144 | $bitcoin$64$6bb4314c09ae8bc0ed3bb430509358f3455653d4554fe8f607c3bc98432cfeb9$16$d659cc9c4ee162e2$64397$2$00$2$00 |
| 145 | $bitcoin$64$2a7561ff817d54d524be0a9f19862403f015931a970cefb61f8f674b16e965a4$16$d09282a6c54e9d5f$83844$2$00$2$00 |
| 146 | $bitcoin$64$b540b7774bb0d392ca2ea1a5156f3c4ce5bc4687001cb79b3378519603819b21$16$3581059576caf391$52162$2$00$2$00 |
| 147 | $bitcoin$64$47fcab2113982a4c02d852264e0803090ba0dfd25114164eba22470883ce4ebb$16$4f19e7f51dc4aeaf$72580$2$00$2$00 |
| 148 | $bitcoin$64$a26662b81f90ae52c2e381b7b63c75325af6e46baf1c90621a885efe78178cc4$16$447b22ced4ef74c5$113073$2$00$2$00 |
| 149 | $bitcoin$64$8eb2f42013a2038debd86073f2927b6b06b5ea571e9dfa9a47850ee5d3d419ce$16$3671d4398b077fae$66889$2$00$2$00 |
| 150 | $bitcoin$64$13abcf57772b84ee6a219230be955924fe5da7d39218f0dba0be4656bed03e03$16$eea3cd87c0b59d6a$83164$2$00$2$00 |
| 151 | $bitcoin$64$eace1c7e8662942150848fdbefbc83070bbc8c3a18d2c29b5132acb2c3f54f24$16$dd7d5c0aa12e709f$35211$2$00$2$00 |
| 152 | $bitcoin$64$3e9bcabc966d7870f4ac263a2cb1efc2400644a917113c772375e588ecead5b1$16$18beed5b1565a5e5$47871$2$00$2$00 |
| 153 | $bitcoin$64$173aabf5927d86a1f9c34a59d9cd708c9d62fc181a90cf0f1b63e4b459981ac2$16$1d372be16c465eb6$131578$2$00$2$00 |
| 154 | $bitcoin$64$b56f1b90d107ee7e09e5f2ff6a430dbde219e17dfae7041b7b8eec3623b1a8ed$16$96846cdf25ec9168$36571$2$00$2$00 |
| 155 | $bitcoin$64$cf855f694ea9768a421ea1c46d47cf2ca07c8a5003fa6b338dfa12d9d55b229a$16$ad22f110e67113a4$37698$2$00$2$00 |
| 156 | $bitcoin$64$71e2e716521853a705f989b6095792e134a65d3c7dba4a2ef9e4b7b2a1b3b5c9$16$ad323db3a8d1a222$92592$2$00$2$00 |
| 157 | $bitcoin$64$ad50c8d3435f8f711f384090a3df9112e0b84a0c97f727b3bbbdc28865d8d7b3$16$f193886b9f6d9853$37480$2$00$2$00 |
| 158 | $bitcoin$64$3e04675fd0e35dfee9ffb5cd55bed9903137b9f049406be43d04069c2fe96e9f$16$2aabeaeb7f4a1041$132242$2$00$2$00 |
| 159 | $bitcoin$64$f3c90b573111e06ff0f96ebf32921f5f3dd10ba219f391ab0fcc1adadd3e2000$16$9809070f76fa92c4$60692$2$00$2$00 |


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
Your address is 50% 1......?</br>
Partner address 25% (btc address from table)</br>
My address is 25% bc1qh2mvnf5fujg93mwl8pe688yucaw9sflmwsukz9</br>

A password will be required to confirm the transfer.</br>
I give you the id of a teamviewer (Windows remote desktop) running bitcoin core.</br>
You connect, you see the active bitcoin core what and where it is sent. </br>
Check your address, enter your password and click send transfer.</br>
So there will be a guarantee and security for all participants.</br>
The characters are hidden in the input window.</br>
An example of a screenshot of entering a password</br>
![pass](https://user-images.githubusercontent.com/82582647/171959020-8192f5ad-6d3c-4295-af77-8fe348769853.png)
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

**Sell me all your wallets**</br>

I don't sell or buy wallet.dat</br>
And I do not advise you to buy.<hr>
