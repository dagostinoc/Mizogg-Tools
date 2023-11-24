# Mizogg-Tools

Next UPDATE coming soon Mizogg Tool's in Telegream

![image](https://user-images.githubusercontent.com/88630056/169119186-1f287adb-a688-4c99-a941-03e6f0eae634.png)
![image](https://user-images.githubusercontent.com/88630056/169120062-582ea1d9-c479-4234-87de-4550344bfce9.png)


Tools for Bitcoin Dogecoin and ETH Information Balance, HASH160, DEC, Transactions and much more.

Install_libraries.bat to get started( Only needs to be done once)

then to run use any of the start.bat files

## Miz_Tools_ice.py Version 10 Total 31 Tools

Using iceland2k14 secp256k1 https://github.com/iceland2k14/secp256k1  fastest Python Libary

    ************************ Main Menu Mizogg's Tools ***************************
    *                       Single Check Tools                                  *
    *    Option 1.Bitcoin Address with Balance Check                   =  1     *
    *    Option 2.Bitcoin Address to HASH160 Addresses starting 1,3,bc1=  2     *
    *    Option 3.HASH160 to Bitcoin Address(Not Working)              =  3     *
    *    Option 4.Brain Wallet Bitcoin with Balance Check              =  4     *
    *    Option 5.Hexadecimal to Decimal (HEX 2 DEC)     [Offline]     =  5     *
    *    Option 6.Decimal to Hexadecimal (DEC 2 HEX)     [Offline]     =  6     *
    *    Option 7.Hexadecimal to Bitcoin\Dogecoin Address with Balance Check=7  *
    *    Option 8.Decimal to Bitcoin\Dogecoin Address with Balance Check= 8     *
    *    Option 9.Mnemonic Words to Bitcoin Address with Balance Check =  9     *
    *    Option 10.WIF to Bitcoin Address with Balance Check           =  10    *
    *    Option 11.Retrieve ECDSA signature R,S,Z rawtx or txid tool   =  11    *
    *    Option 12.Range Divsion IN HEX or DEC tool      [Offline]     =  12    *
    *                                                                           *
    *                    Generators & Multi Check Tools                         *
    *    Option 13.Bitcoin Addresses from file with Balance Check      = 13     *
    *    Option 14.Bitcoin Addresses from file to HASH160 file 1,3,bc1 = 14     *
    *    Option 15.Brain Wallet list from file with Balance Check      = 15     *
    *    Option 16.Mnemonic Words Generator Random Choice [Offline]    = 16     *
    *    Option 17.Bitcoin random scan randomly in Range  [Offline]    = 17     *
    *    Option 18.Bitcoin Sequence scan sequentially in Range division= 18     *
    *    Option 19.Bitcoin random Inverse K position      [Offline]    = 19     *
    *    Option 20.Bitcoin sequence Inverse K position    [Offline]    = 20     *
    *    Option 21.Bitcoin WIF Recovery or WIF Checker 5 K L [Offline] = 21     *
    *    Option 22.Bitcoin Addresses from file to Public Key [OnLine]  = 22     *
    *    Option 23.Public Key from file to Bitcoin Addresses           = 23     *
    *                                                                           *
    *                 ETH Generators & Multi Check Tools                        *
    *    Option 24.ETH Address with TXS Check         [Internet required]= 24   *
    *    Option 25.Hexadecimal to Decimal (HEX 2 DEC) [Internet required]= 25   *
    *    Option 26.Decimal to Hexadecimal (DEC 2 HEX) [Internet required]= 26   *
    *    Option 27.Mnemonic Words to dec and hex      [Internet required]= 27   *
    *    Option 28.Mnemonic Words Generator Random Choice [Offline]      = 28   *
    *    Option 29.Mnemonic Words Generator Random Choice [ONLINE]       = 29   *
    *                                                                           *
    *                   Extras Miscellaneous Tools                              *
    *    Option 30.Doge Coin sequential Scan Balance Check [ONLINE]      = 30   *
    *    Option 31.Doge Coin Random Scan Balance Check [ONLINE]          = 31   *
    *                                                                           *
    *************** Main Menu Mizogg's All Tools made in Python *****************

      Type You Choice Here Enter 1-31 : 
     
## Miz_Tools_bit.py Version 4  Check https://mizogg.co.uk for more tools and info

test it here https://replit.com/@Mizogg

    7
    Hexadecimal to Bitcoin Address Tool
    Hexadecimal HEX ->  1
    PrivateKey (hex) :  1
    PrivateKey (dec) :  1
    PrivateKey (wif) Compressed   :  KwDiBf89QgGbjEhKnhXJuH7LrciVrZi3qYjgd9M7rFU73sVHnoWn
    PrivateKey (wif) UnCompressed :  5HpHagT65TZzG1PH3CSu63k8DbpvD8s5ip4nEB3kEsreAnchuDf
    Bitcoin Address Compressed   =  1BgGZ9tcN4rm9KBzDn7KprQz87SZ26SAMH     Balance =  0.00000000  BTC
    Bitcoin Address UnCompressed =  1EHNa6Q4Jz2uvNExL497mE43ikXhwF6kZm     Balance =  0.00000000  BTC
    Bitcoin Address Segwit       =  3JvL6Ymt8MVWiCNHC7oWU6nLeHNJKLZGLN     Balance =  0.00000000  BTC
    {'address': '1EHNa6Q4Jz2uvNExL497mE43ikXhwF6kZm', 'final_balance': 0, 'n_tx': 1391, 'total_received': 781873722, 'total_sent': 781873722}
    {'address': '3JvL6Ymt8MVWiCNHC7oWU6nLeHNJKLZGLN', 'final_balance': 0, 'n_tx': 2, 'total_received': 1000, 'total_sent': 1000}
    {'address': '1BgGZ9tcN4rm9KBzDn7KprQz87SZ26SAMH', 'final_balance': 0, 'n_tx': 62, 'total_received': 15211855, 'total_sent': 15211855}
    
NEW RSZ ADDED

        1-txid  blockchain API R,S,Z calculation starts. [Internet required]
        2-rawtx R,S,Z,Pubkey for each of the inputs present in the rawtx data. [No Internet required]
        Type 1-2 to Start
        1
      Enter Your -txid = 82e5e1689ee396c8416b94c86aed9f4fe793a0fa2fa729df4a8312a287bc2d5e

      Starting Program...
      ======================================================================
      [Input Index #: 0]
     R: 009bf436ce1f12979ff47b4671f16b06a71e74269005c19178384e9d267e50bbe9
     S: 00c7eabd8cf796a78d8a7032f99105cdcb1ae75cd8b518ed4efe14247fb00c9622
     Z: 9f4503ab6cae01b9fc124e40de9f3ec3cb7a794129aa3a5c2dfec3809f04c354
      PubKey: 04e3896e6cabfa05a332368443877d826efc7ace23019bd5c2bc7497f3711f009e873b1fcc03222f118a6ff696efa9ec9bb3678447aae159491c75468dcc245a6c
      ======================================================================
      [Input Index #: 1]
     R: 0094b12a2dd0f59b3b4b84e6db0eb4ba4460696a4f3abf5cc6e241bbdb08163b45
     S: 07eaf632f320b5d9d58f1e8d186ccebabea93bad4a6a282a3c472393fe756bfb
     Z: 94bbf25ba5b93ba78ee017eff80c986ee4e87804bee5770fae5b486f05608d95
      PubKey: 04e3896e6cabfa05a332368443877d826efc7ace23019bd5c2bc7497f3711f009e873b1fcc03222f118a6ff696efa9ec9bb3678447aae159491c75468dcc245a6c

test it here https://replit.com/@Mizogg/Mizogg-Tools?v=1

New All Tools in one 31 Options for Bitcoin DogeCoinand ETH. Only On https://mizogg.co.uk

![image](https://user-images.githubusercontent.com/88630056/156468112-201daba9-dc05-4179-9286-8f5996e5f19b.png)

https://user-images.githubusercontent.com/88630056/156468157-0ab9a2ac-91f5-48f5-9214-d42c56d37a3e.mp4

### Donations 3GCypcW8LWzNfJEsTvcFwUny3ygPzpTfL4
