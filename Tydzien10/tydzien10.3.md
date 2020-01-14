# #Tydzien10.3

## Jakich usług bezpieczeństwa chciałbyś włączyć i w jakim zakresie by to wszystko działało w dobrze znany sposób

- MFA
- SAS dla dostępu do danych
- KeyVault do przechowywania kluczy szyfrujących dla dysków oraz innych kluczy/haseł wykorzystywanych w apliakcji
- NSG i ASG do zabezpieczenia komunikacji wewnątrz VNET-ów
- WAF/Azure FrontDoor przed każdą aplikacją wystawioną na Internet
- Oddzielne spoke-i serwisowe dla administratorów dostępne przez VPN z On-Premises przez ExpressRoute

To tak ogólnie w ramach dobrych praktyk, bo wiadomo, że wszysko zależy od danego case-u oraz architektury.
