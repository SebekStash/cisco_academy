# Cheatsheet for console commands
- enable            | Switch#               - tryb uprzywilejowany
- disable           | Switch>               - zwykły tryb użytkownika
- configure terminal| Switch(config)#       - globalna konfiguracja (switcha, routera)
- interface vlan 1  | Switch(config-if)#    - konfiguracja interfejsu
- line console 0    | Switch(config-line)#  - konfiguracja "management interface for console port"
- exit              | Switch(config)#       - wróć do globalnej konfiguracji
- line vty 0 15     | Switch(config-line)#  - "virtual terminal management system"
- end / CTRL+Z      | Switch#               - wyjdź do trybu uprzywilejowanego

# 

- Switch(config)# hostname nowaNazwaSwitcha - zmień nazwę urządzenia

Sw-Floor-1(config-line)# password cisco
Sw-Floor-1(config-line)# login
Sw-Floor-1(config-line)# end