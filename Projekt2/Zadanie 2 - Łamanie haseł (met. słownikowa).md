Określenie typu wykorzystanego algorytmu hashującego za pomocą strony:
www.tunnelsup.com/hash-analyzer/ lub innego narzędzia.

Następnie rozszyfrowanie hasła za pomoca hashcat lub innych dostępnych opcji.

1. 9fd8301ac24fb88e65d9d7cd1dd1b1ec
![](20230514123835.png)

hashcat -a 3 -m 0  9fd8301ac24fb88e65d9d7cd1dd1b1ec /home/kali/Desktop/Projekt2/rockyou.txt

![](20230514125749.png)

Wynik: butterfly

2. 7f9a6871b86f40c330132c4fc42cda59
![](20230514125833.png)

hashcat -a 3 -m 0 7f9a6871b86f40c330132c4fc42cda59 /home/kali/Desktop/Projekt2/rockyou.txt

![](20230514130043.png)

Wynik: tinkerbell

3. 6104df369888589d6dbea304b59a32d4
![](20230514125845.png)

hashcat -a 3 -m 0 6104df369888589d6dbea304b59a32d4 /home/kali/Desktop/Projekt2/rockyou.txt

![](20230514130214.png)

Wynik: blink182

4. 276f8db0b86edaa7fc805516c852c889
![](20230514125855.png)

hashcat -a 3 -m 0 276f8db0b86edaa7fc805516c852c889 /home/kali/Desktop/Projekt2/rockyou.txt

![](20230514130338.png)

Wynik: baseball

5. 04dac8afe0ca501587bad66f6b5ce5ad
![](20230514125916.png)

hashcat -a 3 -m 0 04dac8afe0ca501587bad66f6b5ce5ad /home/kali/Desktop/Projekt2/rockyou.txt

![](20230514130457.png)

Wynik: hellokitty

6. 7ab6888935567386376037e042524d27fc8a24ef87b1944449f6a0179991dbdbc481e98db4e70f6df0e04d1a69d8e7101d881379cf1966c992100389da7f3e9a

![](20230514130620.png)

hashcat -a 3 -m 1700 7ab6888935567386376037e042524d27fc8a24ef87b1944449f6a0179991dbdbc481e98db4e70f6df0e04d1a69d8e7101d881379cf1966c992100389da7f3e9a /home/kali/Desktop/Projekt2/rockyou.txt

![](20230514130932.png)

Wynik: spiderman

7. 470c62e301c771f12d91a242efbd41c5e467cba7419c664f784dbc8a20820abaf6ed43e09b0cda994824f14425db3e6d525a7aafa5d093a6a5f6bf7e3ec25dfa
![](20230514130640.png)

 hashcat -a 3 -m 1700 470c62e301c771f12d91a242efbd41c5e467cba7419c664f784dbc8a20820abaf6ed43e09b0cda994824f14425db3e6d525a7aafa5d093a6a5f6bf7e3ec25dfa /home/kali/Desktop/Projekt2/rockyou.txt


![](20230514131106.png)

Wynik: rockstar