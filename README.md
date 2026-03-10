# 👁️‍🗨️ AR Nexus Purge

🇧🇷 **[Português]** | 🇺🇸 **[English below]**

Um jogo de tiro em Realidade Aumentada (AR) onde o ambiente físico do jogador se torna a última linha de defesa. 

No Nexus Purge, o jogador descobre que códigos QR no mundo real são falhas na realidade. Utilizando a câmera do dispositivo mobile, o sistema rastreia e converte esses códigos em portais interdimensionais, de onde emergem hordas de criaturas hostis. O objetivo é neutralizar a ameaça antes que o tempo limite se esgote.

📱 **[Baixe e jogue a versão final no Itch.io / Play it on Itch.io](https://lucassodev.itch.io/nexus-purge)**

## ⚙️ Engenharia e Mecânicas Principais (Mechanics & System Design)

O desenvolvimento deste projeto exigiu a integração de tecnologias de rastreamento do mundo real com mecânicas clássicas de *Wave Shooter*:

* **Rastreamento de Imagem (Image Tracking):** Utilização de códigos QR físicos como *Image Targets*. O sistema lê o código pela câmera e ancora o portal 3D e as malhas de colisão no espaço físico em tempo real.
* **Sistema de Hordas Dinâmico (Wave Spawning):** Os inimigos são instanciados (spawn) a partir do ponto de ancoragem do portal, exigindo que o jogador se mova fisicamente pelo cenário para mirar e desviar.
* **Controle de Tempo Restrito (Time Attack):** Um sistema rigoroso de contagem regressiva. Se a horda não for purgada a tempo, a invasão se torna permanente e a sessão é encerrada, punindo a lentidão do jogador.

---

🇺🇸 **[English]**

An Augmented Reality (AR) shooter where the player's physical environment becomes the last line of defense.

In Nexus Purge, the player discovers that real-world QR codes are rifts in reality. Using the mobile device's camera, the system tracks and converts these codes into interdimensional portals, from which hordes of hostile creatures emerge. The objective is to neutralize the threat before the time limit expires.

## ⚙️ Core Mechanics & System Design

The development of this project required integrating real-world tracking technologies with classic Wave Shooter mechanics:

* **Image Tracking:** Utilizing physical QR codes as Image Targets. The system reads the code via the camera and anchors the 3D portal and collision meshes in the physical space in real-time.
* **Dynamic Wave Spawning:** Enemies are spawned from the portal's anchor point, requiring the player to physically move around their environment to aim and dodge.
* **Strict Time Control (Time Attack):** A rigorous countdown system. If the horde is not purged in time, the invasion becomes permanent and the session ends, punishing player sluggishness.

---

## 🛠️ Tecnologias Utilizadas (Tech Stack)

* **Engine:** Unity 3D
* **AR Framework:** Unity AR Foundation / Vuforia *(Atualize com o framework exato que você usou)*
* **Linguagem / Language:** C#
* **Plataforma:** Mobile (Android)
* **Versionamento / Version Control:** Git & GitHub

## 👨‍💻 Desenvolvedor (Developer)
**Lucas**
- [Portfólio no Itch.io](https://lucassodev.itch.io/)
