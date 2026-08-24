# FCSC 2025 eraise

À vous de décrocher une augmentation !

Cette épreuve est un service d’un CTF fictif en mode Attack/Defense ! Votre équipe a mis en place l’outil [Shovel](https://github.com/FCSC-FR/shovel) qui vous donne une vision au niveau réeau du traffic entrant et sortant de votre VM de jeu.

Pour ce service, vous équipe s’est faite RCE au tick 0… C’est un peu la loose ! À vous de comprendre l’exploit avec les trames réseaux et de le rejouer sur une équipe adverse.

Pour s’adapter au FCSC, on ne donne qu’un unique flagID : `KUHddCSYqwYFWowMzSxzdcHjCm3ayDFs`.

Le flag à trouver est au format `FCSC_<hex_string>`.

Bon courage !

- Shovel : [http://localhost:8000](http://localhost:8000)
- Service à attaquer : `nc localhost 4000`

Auteur : Cryptanalyse

Origine : [eraise](https://hackropole.fr/fr/challenges/pwn/fcsc2025-pwn-eraise/)


## Challenge
[files/eraise](files/eraise)
[files/ld-2.40.so](files/ld-2.40.so)
[files/libc-2.40.so](files/libc-2.40.so)

-----------

## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2025-pwn-eraise.git

> cd fcsc2025-pwn-eraise

> docker compose up

-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/pwn/fcsc2025-pwn-eraise/
