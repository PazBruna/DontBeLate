# 5. Mecânica

## 5.1 Esboço do loop principal
a)  Movimentação do jogador.
b)  Disparo do jogador.
c)  Detecção de colisão dos disparos com os inimigos.
d)  Reação dos inimigos à presença do jogador.
e)  Ataque dos inimigos.
f)  Detecção de colisão dos ataques dos inimigos com o jogador.
g)  Verificação de vida do jogador (se perdeu toda a vida, fim de jogo).
h)  Verificação de spawn do padre
i)  Verificação se o jogador chegou ao destino.

## 5.2 Atores, componentes e mecânicas

- Jogador: Possui como componentes a vida e a quantidade de munição, além de
portar uma arma. Pode se movimentar livremente pelo cenário e atirar para se
defender.
- Quero-queros: Possuem vida. Permanecem em patrulha no
ambiente e reagem agressivamente à presença do jogador, atacando-o assim que o
detectam.
- Estátua do Padre: Possui vida. Surge aleatoriamente pelo mapa. Ataca o jogador assim que o ver.
- Arma: Conta com atributos de dano e nível, sendo aprimorada a cada progresso do
jogador.

## 5.3 Regras
- **Explícitas:**
  - Percurso e Tempo: O jogador deve completar a rota até a sala de aula dentro
do tempo estipulado para cada fase.
  - Coleta de Munição: Para se defender, o jogador precisa coletar pedras
espalhadas pelo campus, que servem para recarregar sua arma.
  - Pontuação Extra: Abater um número pré-determinado de quero-queros
garante pontos extras.
  - Aparição do Padre: Caso o jogador ultrapasse o tempo mínimo para concluir
a fase, a estátua do padre ganha vida e começa a persegui-lo de forma aleatória.
  - Enfrentando o Padre: Para escapar, o jogador deve acertar a estátua com
cinco pedras
- **Implícitas:**
   - Munição Limitada: O jogador possui um número restrito de pedras por
rodada, tornando essencial a coleta e o uso estratégico.
   - Intervalo de Disparo: Existe um tempo de recarga entre um arremesso e
outro, exigindo precisão nos ataques.
   - Vida do Jogador: O personagem tem um número limitado de pontos de vida,
sendo derrotado caso perca todos eles.

## 5.4 Procedimentos
- **Desviar dos inimigos:** O jogador pode evitar o confronto direto, utilizando
movimentação estratégica para escapar dos quero-queros e do padre.
- **Distração dos quero-queros:** O jogador pode usar elementos do ambiente ou
lançar pedras para desviar a atenção das aves e abrir caminho.
- **Coleta de pedras:** Para se defender, o jogador precisa buscar e coletar pedras
espalhadas pelo cenário.
- **Gerenciamento do tempo:** O jogador deve equilibrar velocidade e cautela para
alcançar a sala antes que o tempo acabe e o padre comece a persegui-lo.

## 5.5 Recursos
- **Pedras:** O jogador usa pedras para causar dano nos inimigos, podendo ter um
upgrade a cada fase.
- **Pontuação:** O jogador ganha pontos a cada quero quero atingido.
- **Vidas:** O jogador inicia o jogo com 3 vidas.
- **Quero queros:** O jogador deve eliminar os quero quero para ganhar pontos.
  
## 5.6 Limites
- **Início:** O jogo se inicia na portaria principal da FEI.
- **Término:** O jogo termina na sala de prova.
- **Limite:** O jogo tem como limite o campus da faculdade.
  
## 3.7 Resultado
O jogo tem como resultado o aluno conseguindo chegar na sala de prova e
realizando-a.

