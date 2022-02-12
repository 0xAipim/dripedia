---
label: Faucet (Torneira)
order: -2
icon: verified
---

# Faucet (Torneira)
Um contrato de baixo risco e alto rendimento que funciona de forma similar a um certificado de depósito.

---
## Como funciona?

Para fazer parte da Faucet, participantes depositam tokens DRIP. Tokens DRIP depositados são enviados permanentemente para a reserva de fundos da Faucet e não podem ser sacados pelos participantes. A Faucet oferece rendimentos diários de 1% (em DRIP) do total de depósitos, com um limite para o total de saques igual a 365% do total depositado ou 100K tokens DRIP (o que for menor).

Os rendimentos diários de 1% tem como fonte a reserva de fundos da Faucet, que é financiada pelos depósitos na Faucet e pelas taxas de transação do token DRIP. Se houver uma situação em que não haja tokens DRIP suficientes na reserva de fundos da Faucet para pagar os rendimentos da Faucet, novos tokens DRIP serão cunhados para garantir que os rendimentos sejam pagos. Dada a teoria de jogo por trás do projeto, a probabilidade de que novos tokens DRIP sejam cunhados é extremamente baixa.

---
##  Ações

**Depositar:**
Deposita tokens DRIP da sua carteira no contrato da Faucet. Há um valor mínimo de depósito de 1 DRIP. Adicionalmente, há um imposto de 10% para depositar DRIP na Faucet.

**Hidratar:**
Redeposita suas recompensas disponíveis na Faucet de volta na Faucet. Há um imposto de 5% para hidratar recompensas da Faucet. A hidratação permite que os participantes aumentem seus ganhos diários, por aumentar o total de seus depósitos na Faucet. Hidratação frequente gera recompensas diárias exponenciais.

**Sacar:**
Realiza o saque das suas recompensas disponíveis na DRIP Faucet para a sua carteira. Há um imposto de 10% para sacar recompensas da DRIP Faucet.

**Airdrops:**
Realiza o envio de tokens DRIP da sua carteira diretamente ao saldo de depósitos na Faucet de um outro participante. Há um imposto de 10% para realizar airdrops.
Enviar airdrops pode te ajudar a garantir que sua conta tenha um status positivo de depósito líquido (mais depósitos do que saques no projeto), além de ser uma ótima ferramenta para retribuir aos membros da sua equipe e atrair novos membros.


| Transação | Taxa |
|:---:|:---:|
| Depósito na Faucet | 10% |
| Saque da Faucet | 10% |
| Hidratar a Faucet (redepositar) | 5% |
| Enviar airdrop | 10% |

---

## Equipes e Indicações

Antes que um participante possa depositar na Faucet, o participante terá que se juntar à equipe de outra pessoa, inserindo o endereço da carteira da pessoa no sistema de indicação. Essa pessoa escolhida (líder da equipe) já deve estar ativa na Faucet (ter um depósito na Faucet) e ter 14 ou menos pessoas acima dela (há um limite de 15 níveis). Não é possível trocar de equipe.

Os participantes não são obrigados a desenvolver equipes e ainda ganharão as recompensas da Faucet, independentemente do tamanho de suas equipes.

Com o objetivo de promover o crescimento da plataforma, a DRIP Network implementou um sistema de indicações. Este sistema busca recompensar os participantes de forma justa por seu trabalho em ajudar a expandir o alcance da DRIP Network.

O valor da recompensa por indicação é de 10% do valor depositado (após os impostos de depósito) ou 5% do valor hidratado (após os impostos de hidratação). Recompensas por indicação recebidas vão para os depósitos da Faucet.

Requisitos para receber recompensas por indicação de pessoas em níveis abaixo ao seu:
- Ter a quantia do token BR34P necessária em sua carteira (veja a tabela abaixo)
- Ter um status de depósito líquido positivo: (Depósitos na Faucet + Hidratações na Faucet + Airdrops enviados) > (Saques da Faucet)


| Número de níveis alcançáveis | Quantia de BR34P necessária |
|:---:|:---:|
| 1 | 2 |
| 2 | 3 |
| 3 | 5 |
| 4 | 8 |
| 5 | 13 |
| 6 | 21 |
| 7 | 34 |
| 8 | 55 |
| 9 | 89 |
| 10 | 144 |
| 11 | 233 |
| 12 | 377 |
| 13 | 610 |
| 14 | 987 |
| 15 | 1597 |


Se essas condições não forem atendidas, a pessoa 1 nível acima terá sua elegibilidade verificada, sucessivamente até que um participante elegível seja encontrado para receber as recompensas.

Se a equipe do participante selecionado para receber as recompensas tiver menos de 5 membros diretos, este participante selecionado receberá 100% da recompensa.
Se a equipe do participante selecionado para receber as recompensas tiver mais de 5 membros diretos, este participante selecionado receberá 75% da recompensa, e a pessoa que estiver depositando/hidratando receberá 25% da recompensa.

| Tamanho da equipe do selecionado | Recompensa do selecionado | Recompensa de quem deposita |
|:---:|:---:|:---:|
| < 5 | 100% | 0% |
| ≥ 5 | 75% | 25% |

Os tokens que vão para a [carteira do desenvolvedor](https://bscscan.com/address/0xe8e9720e39e13854657c165cf4eb10b2dfe33570) serão usados como ferramenta promocional para ajudar no crescimento da plataforma. Por exemplo: patrocinar competições entre equipes, ser queimado, etc. Esses tokens não serão despejados no mercado.

Para explicar melhor como funciona o sistema de indicação, vejamos um exemplo ilustrado pela imagem abaixo:

![Ilustração da seguinte árvore de indicações: Dev wallet (5 membros diretos, 1600 BR34P) -> Alicia (3 membros diretos, 10 BR34P) -> Bruno (1 membro direto, 0 BR34P) -> Chang (3 membro direto, 2 BR34P) -> Diana ( 0 membros diretos, 0 BR34P).](/static/banner_faucet_referral.jpg)

Sempre que Diana (mais à direita da imagem) depositar ou hidratar, uma carteira em um nível acima dela receberá uma recompensa (uma porcentagem do valor depositado ou hidratado).

Na 1ª vez que Diana fizer um depósito, a recompensa irá para a pessoa **1 nível** acima dela (se a conta for elegível), neste caso o Chang. Chang receberá as recompensas porque ele possui tokens BR34P suficientes em sua carteira para alcançar 1 nível abaixo dele e tem um status positivo de depósito líquido .

A 2ª vez que Diana depositar ou hidratar, a recompensa irá para a pessoa **2 níveis** acima dela, neste caso o Bruno. Bruno não é elegível para receber esta recompensa porque ele não tem tokens BR34P suficientes em sua carteira para alcançar 2 níveis abaixo dele. Como Bruno não é elegível para receber a recompensa, ela irá para a pessoa acima dele, a Alicia, que está **3 níveis** acima de Diana. Alicia receberá a recompensa porque ela possui tokens BR34P suficientes em sua carteira para alcançar 3 níveis abaixo dela e tem um status positivo de depósito líquido.

Na 3ª vez que Diana depositar ou hidratar, a recompensa irá para a pessoa **4 níveis** acima dela, a carteira do desenvolvedor. A carteira do desenvolvedor é elegível e receberá as recompensas.

Como não há nenhuma conta acima da carteira do desenvolvedor, o nível de recompensas será redefinido para o nível 1. Então, da próxima vez que Diana depositar ou hidratar, o ciclo recomeça com Chang recebendo a recompensa, se ele for elegível.

---

## Imposto para baleias

Para garantir a sustentabilidade do projeto, um imposto adicional sobre saques da Faucet é aplicado aos participantes de acordo com a soma de seus **saques totais + recompensas de Faucet disponíveis** em relação à quantidade total de tokens DRIP.

| % da oferta total de tokens DRIP | Taxa |
|:---:|:---:|
| < 0.99% | 0% |
| ≥ 1% | 5% |
| ≥ 2% | 10% |
| ≥ 3% | 15% |
| ≥ 4% | 20% |
| ≥ 5% | 25% |
| ≥ 6% | 30% |
| ≥ 7% | 35% |
| ≥ 8% | 40% |
| ≥ 9% | 45% |
| ≥ 10% | 50% |
