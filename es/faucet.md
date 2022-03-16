---
label: Faucet
order: -2
icon: verified
description: El DRIP Faucet es un contracto de bajo riesgo y alto beneficio que trabaja similar a un certificado de depósito. Aprende cómo funciona, incluyendo su sistema de referidos y el impuesto a ballenas.
---

# Faucet (El Grifo)
Un contrato de bajo riesgo y alto beneficio que opera similar a un certificado de deposito.

---
### ¿Cómo funciona?

Los jugadores pueden participar en el Faucet al depositar tokens DRIP en él. Los DRIPs depositados se van permanentemente al fondo de impuestos y no pueden ser reclamados de vuelta por el jugador. El Faucet genera 1% diario de retorno de inversión (en DRIP) de los depósitos totales, con una paga máxima de 365% del total del monto depositado o hasta 100,000 DRIPS (cualquier que sea el más pequeño).

Las ganancias del 1% Diario vienen del fondo de impuestos del Faucet, los cuales son fundados por los depósitos de DRIP y por las transacciones del token. Si se llega a una situación donde no haya suficientes tokens DRIP en el fondo de impuestos para pagar por el rendimiento diario, se acuñará nuevos DRIPS para asegurarse que el rendimiento sea pagado. Dada la teoría de juegos tras el proyecto, la probabilidad de que sea necesario acuñar nuevos DRIPs es extremadamente baja.

---
### Acciones

**Deposit (Depósito):**
Deposita tokens DRIP desde tu billetera al contrato del Faucet. Hay una cantidad mínima de depósito de 1 DRIP. También hay un impuesto del 10% por depositar DRIP en el Faucet.

**Hydrate (Hidratar):**
Re-Deposita tus ganancias disponibles nuevamente al Faucet. Hay un impuesto del 5% por hidratar las ganancias. Hidratar le permite a los jugadores incrementar sus ganancias diarias al incrementar su cantidad total de depósitos en el Faucet. Hidratar frecuentemente genera ganancias exponenciales.

**Claim (Retirar)**
Withdraws your available DRIP Faucet rewards into your wallet. There is a 10% tax for claiming DRIP Faucet rewards.

**Airdrops:**
Puedes transferir DRIPs directamente a los depósitos del Faucet de otro jugador. Hay un impuesto del 10% por enviar airdrops. Enviar airdrops puede ayudar a asegurarse que tu cuenta tenga un estado de balance positivo, al mismo tiempo que es una gran herramienta para darle valor de vuelta a tu equipo y atraer nuevos miembros.


| Transacción | Impuesto |
|:---:|:---:|
| Depositos en Faucet | 10% |
| Retiros del Faucet | 10% |
| Hidratación (recompound) | 5% |
| Enviar Airdrops | 10% |

---

### Equipos y Referidos

Antes de que un jugador pueda hacer su depósito en el Faucet, necesitarán unirse al equipo de otra persona al ingresar la dirección billetera de dicha persona en el Buddy Referral System (sistema de referidos de compañeros). Este compañero (líder de equipo) tiene que estar activo en el Faucet (tener un depósito en el Faucet) y tener un máximo de 14 o menos personas arriba de ello en el sistema (hay un límite de 15 niveles). No es posible cambiar de  equipo.

No se requiere que los jugadores construyan equipos bajo ellos, y recibirán sus ganancias del Faucet con o sin referidos y sin importar el tamaño de su equipo.

Con la meta de promover el crecimiento de la plataforma, DRIP Network ha implementado un sistema de referidos. El sistema busca recompensar justamente a sus jugadores por su trabajo al expandir el alcance de DRIP Network.

La cantidad de recompensas por referidos se distribuye en 10% de los depósitos (depósito después de impuestos) o el 5% del monto hidratado (después de impuestos por hidratar). Las recompensas de líder de equipo son enviadas a su depósito del Faucet.

Requerimientos para recibir recompensas por referidos:
-   Tener la cantidad de tokens BR34P necesarios en tu billetera (ver tabla más abajo)
-   Tener un estatus positivo neto: (Depósitos de Faucet + Hidrataciones de Faucet + Airdrops enviados) > (Retiros del Faucet)


| Numero de niveles alcanzables | Cantidad de BR34P necesario |
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


Si estas condiciones no se cumplen, el siguiente jugador arriba en el sistema será verificado, y se entregarán las recompensas hasta que se encuentre a un jugador que cumpla con los requisitos.

Si el jugador seleccionado tiene menos de 5 referidos directos, el jugador recibirá el 100% de las recompensas. Si el jugador seleccionado tiene más de 5 referidos directos, el jugador recibirá el 75% de la recompensa, y la persona que está depositando/hidratando va a recibir el 25% de las recompensas.

| Tamaño de equipo del seleccionado  | Recompensa del seleccionado | Recompensa de quien deposita |
|:---:|:---:|:---:|
| < 5 | 100% | 0% |
| ≥ 5 | 75% | 25% |

!!!primary
Los tokens de recompensas de referidos recibidos por la [dev wallet](https://bscscan.com/address/0xe8e9720e39e13854657c165cf4eb10b2dfe33570) serán usados como una herramienta promocional para ayudar al crecimiento de la plataforma. Por ejemplo: recompensas por competición de equipos, ser quemadas, etc. Estos tokens no serán entregados al mercado.
!!!

Para explicar mejor cómo funciona el sistema de referidos, veamos un ejemplo ilustrado en la imagen de abajo:

![Ilustración de el siguiente árbol de referidos: Dev wallet (5 referidos directos, 1600 BR34P) → Alicia (2 referidos directos, 10 BR34P) → Bruno (1 referido directo, 0 BR34P) → Chang (3 referidos directos, 2 BR34P) → Diana (0 Referidos directos, 0 BR34P)](/static/banner_faucet_referral.jpg)

Cuando Diana (persona más a la derecha de la imagen) deposita o hidrata, una billetera en su línea ascendente va a recibir la recompensa (un porcentaje del monto hidratado o depositado).

La primera vez que Diana haga un depósito, la recompensa irá a la persona que esté **1 nivel** arriba de ella (si la billetera es elegible), en este caso, Chang. Chang va a recibir las recompensas porque tiene suficientes tokens BR34P en su billetera para llegar a 1 nivel hacia abajo y tiene un estatus neto positivo.

La 2da vez que Diana deposite o hidrate, la recompensa irá la persona **2 niveles** arriba de ella, en este caso Bruno. Bruno no es elegible para recibir esta recompensa porque no tiene suficientes tokens BR34P en su billetera para llegar a 2 niveles hacia abajo. Ya que Bruno no es elegible para recibir la recompensa, esta irá a la siguiente persona hacia arriba, Alicia, quien está **3 niveles** arriba de Diana. Alicia va a recibir la recompensa porque tiene suficientes tokens BR34P en su billetera para alcanzar **3 niveles** hacia abajo y tiene un estatus positivo neto.

La 3ra vez que Diana deposite o hidrate, la recompensa irá a la persona **4 niveles** arriba de ella, la dev wallet. La Dev wallet es elegible y recibirá las recompensas.

Ya que no hay cuentas arriba de la dev wallet, el nivel de recompensa se reiniciará al **nivel 1**. Así que la siguiente vez que Diana deposite o hidrate, el ciclo empieza de nuevo con Chang recibiendo la recompensa si es elegible.

---

### Whale Tax (El Impuesto de Ballenas)

Para poder mantener la sostenibilidad del proyecto, un impuesto adicional al retirar del Faucet es aplicado a jugadores acorde a la suma **total de retiros + recompensas disponibles del Faucet** en relación al suministro total de tokens DRIP.

| % total del suministro de DRIP | Impuesto |
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
