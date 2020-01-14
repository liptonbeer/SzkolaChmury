# #Tydzien10.1

## Jakie usługi wykorzystasz i dlaczego? Jakich nie wykorzystasz i gdzie? Bądź pragmatyczny

### Co bym użył

Azure AD Pass-Through with seamless SSO

- Użytkownicy za pomocą tych samych poświadczeń logują się w środowisku Azure jak i On-Premises;
- muszę zostawić kontroler domeny po stronie On-Premises, na potrzeby nieprzeniesionych maszyn;
- chcę, aby użytkownicy sami radzili sobie ze zmianą hasła;
- nie będę wykorzystywał polityk niewspieranch przez AD;
- chcę aby było wymuszone wykorzystanie polityk na poziomie użytkownika;
- chcę zmigroważ wszystkich użytkowników na Office 365;

B2C

- dla aplikacji hostowanych w chmurze, które będą dostępne przez zewnętrznych użytkowników;
- nie chcę tych użytkowników przechowywać w AD razem z pracownikami wewnętrznymi firmy;

### Czego bym nie używał

Azure AD

- zostawiam kontroler domeny po stronie On-Premises;

B2B

- w moim przypadku nie potrzebuję nadawać dostępu do wewnętrznego środowiska parterom z innego AD;

Azure AD FS

- Wewnątrz On-Premises nie ma federation providera;
- nie będę wykorzystywał polityk niewspieranch przez AD;
- docelowo cały On-Premises ma być zmigorwany do chmury;