# Introdução

 
 O estilo do jogo é caracterizado como ação, aventura e shooter. Nele você é um estudante
do Centro Universitário FEI em sua semana de provas finais. No entanto, há um grande problema:
todas as provas acontecem à noite, justamente quando os quero-queros do campus se transformam
em aves assassinas para proteger seu território. Seu objetivo é atravessar a FEI todas as noites e
chegar ao prédio onde realizará cada prova, enfrentando bandos cada vez mais agressivos de
quero-queros. Para se defender, você conta com uma arma que dispara pequenas pedras. A cada
prova concluída, sua arma é aprimorada, aumentando sua eficácia e fornecendo mais munição. A
cada noite, os quero-queros se tornam mais hostis e numerosos, tornando a jornada cada vez
mais desafiadora.


    
### 1. Esboço do loop principal
-  Movimentação do jogador.
-   Disparo do jogador.
-   Detecção de colisão dos disparos com os quero-queros.
-   Reação dos quero-queros à presença do jogador.
-   Ataque dos quero-queros.
-   Detecção de colisão dos ataques dos quero-queros com o jogador.
-   Verificação de vida do jogador (se perdeu toda a vida, fim de jogo).
-   Verificação se o jogador chegou ao destino.

### 2. Atores, componentes e mecânicas

- Jogador: Possui como componentes a vida e a quantidade de munição, além de
portar uma arma. Pode se movimentar livremente pelo cenário e atirar para se
defender.
- Quero-queros: Possuem vida e poder de ataque. Permanecem em patrulha no
ambiente e reagem agressivamente à presença do jogador, atacando-o assim que o
detectam.
- Arma: Conta com atributos de dano e nível, sendo aprimorada a cada progresso do
jogador.
