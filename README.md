# Valheim Modpack — Guia Completo
*https://h3r9.github.io/valheim-modpack-igor/*

**Valheim** `v0.221.4` • **BepInExPack** `5.4.x` • Layout retrô (pixel), com busca/filtros no site.
Este README acompanha o conteúdo do **site** (`index.html`) e descreve **todos os mods instalados**, inclusive bibliotecas.

> **Dica global de atalhos:** a maioria dos mods expõe teclas e opções no **Configuration Manager**.
> Abra com **`F1`** (padrão); ajuste teclas/raios/distâncias lá.

---

## Índice

* [Como instalar (manual)](#como-instalar-manual)
* [Como atualizar (manual)](#como-atualizar-manual)
* [Mods instalados](#mods-instalados)

  * [Núcleo / Bibliotecas](#núcleo--bibliotecas)
  * [UI/HUD e QoL](#uihud-e-qol)
  * [Inventário e Automação](#inventário-e-automação)
  * [Construção e Base](#construção-e-base)
  * [Farming e Coleta](#farming-e-coleta)
  * [Mapa e Viagem](#mapa-e-viagem)
  * [Itens / Montarias / Utilitários](#itens--montarias--utilitários)
  * [Combate / Magia / Conteúdo](#combate--magia--conteúdo)
  * [Extras](#extras)
* [Lista crua (copiar/colar)](#lista-crua-copiarcolar)
* [Mods recomendados (aderentes ao pack)](#mods-recomendados-aderentes-ao-pack)
* [Créditos](#créditos)

---

## Como instalar (manual)

1. Faça backup de `characters/` e `worlds/`.
2. Baixe **BepInExPack Valheim** e extraia na pasta do jogo (onde está `valheim.exe`).
3. Coloque os `.dll` de cada mod em `BepInEx/plugins/`.
4. Dependências (Jötunn/JVL, XUnity, libs) também vão em `plugins/`.
5. Inicie o jogo 1 vez para gerar configs em `BepInEx/config/`. Ajuste pelo **F1**.

## Como atualizar (manual)

* Substitua o `.dll` antigo pelo novo em `BepInEx/plugins/` (mantenha backups).
* Compare as `.cfg` novas com as antigas (o jogo recria padrões na primeira execução).
* Conflitos? Atualize **primeiro** bibliotecas (JVL, XUnity, EIDF, etc.), **depois** mods de conteúdo.

---

## Mods instalados

> **Observação sobre links:** quando não há página única óbvia, os botões levam a **pesquisas diretas** (site:thunderstore / site:nexusmods) com o nome do mod.

### Núcleo / Bibliotecas

<details>
<summary><strong>BepInExPack Valheim</strong> <code>5.4.x</code> • <em>Biblioteca</em></summary>
Carregador de plugins para Valheim (bundle pronto do Thunderstore).  
<strong>Como usar:</strong> apenas manter em <code>BepInEx/</code>.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+valheim+BepInExPack+Valheim" target="_blank">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+valheim+BepInEx" target="_blank">Nexus</a> • <a href="https://www.google.com/search?q=BepInEx+Valheim" target="_blank">Google</a>
</details>

<details>
<summary><strong>Jötunn (JVL)</strong> <code>2.27.0</code> • <em>Biblioteca</em></summary>
API de alto nível para itens/receitas/peças/rede. Muitas criações dependem dela.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+valheim+Jotunn" target="_blank">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+valheim+Jotunn" target="_blank">Nexus</a> • <a href="https://www.google.com/search?q=Jotunn+JVL+Valheim" target="_blank">Google</a>
</details>

<details>
<summary><strong>XUnity Resource Redirector</strong> <code>2.1.0</code> • <em>Biblioteca</em></summary>
Redirecionamento/override de assets (útil para traduções e ajustes).  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+XUnity+Resource+Redirector+Valheim" target="_blank">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+XUnity+Resource+Redirector+Valheim" target="_blank">Nexus</a> • <a href="https://www.google.com/search?q=XUnity+Resource+Redirector+Valheim" target="_blank">Google</a>
</details>

<details>
<summary><strong>Newtonsoft.Json Detector</strong> <code>1.0.0</code> • <em>Biblioteca</em></summary>
Disponibiliza a lib JSON (Newtonsoft) para mods que serializam dados.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+Newtonsoft.Json+Valheim" target="_blank">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Newtonsoft+Json+Valheim" target="_blank">Nexus</a> • <a href="https://www.google.com/search?q=Newtonsoft.Json+Valheim" target="_blank">Google</a>
</details>

<details>
<summary><strong>YamlDotNet Detector</strong> <code>1.0.0</code> • <em>Biblioteca</em></summary>
Biblioteca para ler/gravar YAML, usada por configs de alguns mods.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+YamlDotNet+Valheim" target="_blank">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+YamlDotNet+Valheim" target="_blank">Nexus</a> • <a href="https://www.google.com/search?q=YamlDotNet+Valheim" target="_blank">Google</a>
</details>

<details>
<summary><strong>Configuration Manager</strong> <code>18.4.1</code> • <em>Biblioteca / QoL</em></summary>
Abre painel de configurações <strong>in-game</strong>.  
<strong>Atalho padrão:</strong> <code>F1</code>.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+valheim+Configuration+Manager" target="_blank">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+valheim+Configuration+Manager" target="_blank">Nexus</a> • <a href="https://www.google.com/search?q=Configuration+Manager+Valheim" target="_blank">Google</a>
</details>

### UI/HUD e QoL

<details><summary><strong>BetterUI</strong> <code>2.5.9</code> • <em>UI/HUD, QoL</em></summary>
HUD mais informativa (vida, XP, nomes, mensagens).  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+BetterUI+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+BetterUI+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=BetterUI+Valheim">Google</a>
</details>

<details><summary><strong>Building Health Display</strong> <code>0.7.1</code> • <em>UI/HUD, QoL</em></summary>
Mostra a vida das peças de construção para manutenção/defesa.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+Building+Health+Display+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Building+Health+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=Building+Health+Display+Valheim">Google</a>
</details>

<details><summary><strong>Minimal Status Effects</strong> <code>1.0.7</code> • <em>UI/HUD, QoL</em></summary>
Ícones de status compactos/limpos, reduz poluição visual.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+Minimal+Status+Effects+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Minimal+Status+Effects+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=Minimal+Status+Effects+Valheim">Google</a>
</details>

<details><summary><strong>Display Day & Time Countdown</strong> <code>1.0.0</code> • <em>UI/HUD, QoL</em></summary>
Exibe o dia atual e um relógio/contador na HUD.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+Display+Day+Time+Countdown+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Display+Day+Time+Countdown+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=Display+Day+%26+Time+Countdown+Valheim">Google</a>
</details>

<details><summary><strong>CameraTweaks</strong> <code>1.3.1</code> • <em>UI/HUD, QoL</em></summary>
Ajuste fino de câmera (FOV, offset, suavização).  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+CameraTweaks+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+CameraTweaks+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=CameraTweaks+Valheim">Google</a>
</details>

<details><summary><strong>FirstPersonMode</strong> <code>1.3.10</code> • <em>UI/HUD, QoL</em></summary>
Habilita visão em 1ª pessoa com controles ajustáveis.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+FirstPersonMode+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+First+Person+Mode+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=FirstPersonMode+Valheim">Google</a>
</details>

<details><summary><strong>SaveCrossbowState</strong> <code>1.0.2</code> • <em>QoL</em></summary>
Mantém a besta armada entre trocas de item.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+SaveCrossbowState+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Save+Crossbow+State+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=SaveCrossbowState+Valheim">Google</a>
</details>

### Inventário e Automação

<details><summary><strong>AzuExtendedPlayerInventory</strong> <code>1.4.12</code> • <em>Inventário, QoL</em></summary>
Expande o inventário do jogador com slots extras.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+AzuExtendedPlayerInventory">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+AzuExtendedPlayerInventory+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=AzuExtendedPlayerInventory+Valheim">Google</a>
</details>

<details><summary><strong>AzuCraftyBoxes</strong> <code>1.8.5</code> • <em>Automação, Inventário</em></summary>
Crafta usando materiais em baús próximos (raio configurável).  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+AzuCraftyBoxes">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+AzuCraftyBoxes+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=AzuCraftyBoxes+Valheim">Google</a>
</details>

<details><summary><strong>AzuAutoStore</strong> <code>3.0.8</code> • <em>Automação, Inventário</em></summary>
Despejo automático em baús “certos”, com filtros/whitelist.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+AzuAutoStore">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+AzuAutoStore+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=AzuAutoStore+Valheim">Google</a>
</details>

<details><summary><strong>Smart Containers Mod</strong> <code>1.7.0</code> • <em>Automação, Inventário</em></summary>
Agrupa baús por tipo (minérios, vegetais, cogumelos etc.) e organiza automaticamente.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+Smart+Containers+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Smart+Containers+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=Smart+Containers+Mod+Valheim">Google</a>
</details>

<details><summary><strong>Quick Stack - Store - Sort - Restock</strong> <code>1.4.13</code> • <em>Inventário, QoL</em></summary>
Botões para organizar, guardar itens iguais e reabastecer consumíveis.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+Quick+Stack+Store+Sort+Restock+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Quick+Stack+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=Quick+Stack+Store+Sort+Restock+Valheim">Google</a>
</details>

<details><summary><strong>Blacksmithing (Skill)</strong> <code>1.3.2</code> • <em>Skills, Craft</em></summary>
Habilidade de ferreiro; evolui ao forjar e pode ajustar bônus por nível.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+Blacksmithing+skill+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Blacksmithing+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=Blacksmithing+skill+Valheim">Google</a>
</details>

<details><summary><strong>AutoRepair</strong> <code>5.4.1600</code> • <em>Automação, QoL</em></summary>
Repara automaticamente equipamentos ao abrir bancadas compatíveis.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+AutoRepair+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+AutoRepair+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=AutoRepair+Valheim">Google</a>
</details>

### Construção e Base

<details><summary><strong>OdinArchitect</strong> <code>1.5.7</code> • <em>Construção, Conteúdo</em></summary>
Coleção grande de peças nórdicas e decorações para bases/vilas.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+OdinArchitect+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+OdinArchitect+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=OdinArchitect+Valheim">Google</a>
</details>

<details><summary><strong>Auto Fuel</strong> <code>1.3.1</code> • <em>Automação, Base</em></summary>
Abastece fornos/forjas/lareiras a partir de baús próximos; pode coletar produtos.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+Auto+Fuel+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Auto+Fuel+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=Valheim+Auto+Fuel">Google</a>
</details>

<details><summary><strong>AutomaticFermenters</strong> <code>1.0.8</code> • <em>Automação, Base</em></summary>
Fermentadores com entrada/saída automática: puxa ingredientes e deposita hidroméis prontos.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+Automatic+Fermenters+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Automatic+Fermenters+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=Automatic+Fermenters+Valheim">Google</a>
</details>

<details><summary><strong>CookingStationTweaks</strong> <code>0.7.1</code> • <em>Base, Cozinha, QoL</em></summary>
Mais slots por grelha, tempos/avisos e prevenção de queimar alimentos.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+Cooking+Station+Tweaks+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Cooking+Station+Tweaks+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=CookingStationTweaks+Valheim">Google</a>
</details>

<details><summary><strong>TorchesEternal</strong> <code>0.2</code> • <em>Base, QoL</em></summary>
Tochas/brasas com duração estendida (ou ilimitada, via config).  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+TorchesEternal+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Torches+Eternal+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=TorchesEternal+Valheim">Google</a>
</details>

<details><summary><strong>StumpsRegrow</strong> <code>1.0.4</code> • <em>Mundo, Base</em></summary>
Tocos voltam a brotar, facilitando silvicultura sustentável.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+StumpsRegrow+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Stumps+Regrow+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=StumpsRegrow+Valheim">Google</a>
</details>

### Farming e Coleta

<details><summary><strong>PlantEverything</strong> <code>1.20.0</code> • <em>Farming, Conteúdo</em></summary>
Permite plantar itens do mundo (cogumelos, cardo, berries, etc.) com o cultivador.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+PlantEverything+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Plant+Everything+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=PlantEverything+Valheim">Google</a>
</details>

<details><summary><strong>PlantEasily</strong> <code>2.0.3</code> • <em>Farming, Automação</em></summary>
Grade/alinhamento de plantio, com espaçamento ajustável para fileiras perfeitas.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+PlantEasily+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Plant+Easily+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=PlantEasily+Valheim">Google</a>
</details>

<details><summary><strong>MassFarming</strong> <code>1.11</code> • <em>Farming, Automação</em></summary>
Ações em área (plantar/colher) para grandes plantações.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+MassFarming+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Mass+Farming+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=MassFarming+Valheim">Google</a>
</details>

<details><summary><strong>Farming (Skill)</strong> <code>2.2.1</code> • <em>Skills, Farming</em></summary>
Habilidade de agricultura; pode dar bônus de rendimento/eficiência.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+Farming+Skill+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Farming+Skill+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=Farming+skill+Valheim">Google</a>
</details>

<details><summary><strong>Mining (Skill)</strong> <code>1.1.5</code> • <em>Skills</em></summary>
Habilidade de mineração (ajustes de dano/stamina por nível).  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+Mining+Skill+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Mining+Skill+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=Mining+skill+Valheim">Google</a>
</details>

### Mapa e Viagem

<details><summary><strong>CartographySkill</strong> <code>3.1.1</code> • <em>Skills, Mapa</em></summary>
Habilidade ligada à exploração/compartilhamento de mapa (sinergia com mesa de cartografia).  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+Cartography+Skill+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Cartography+Skill+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=Cartography+Skill+Valheim">Google</a>
</details>

<details><summary><strong>TargetPortal</strong> <code>1.2.1</code> • <em>Viagem, QoL</em></summary>
Portais com seleção de destino por lista (nomeie e escolha).  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+TargetPortal+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Target+Portal+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=TargetPortal+Valheim">Google</a>
</details>

<details><summary><strong>Sailing (Skill)</strong> <code>1.1.7</code> • <em>Skills, Viagem</em></summary>
Habilidade que melhora controle/desempenho de barcos conforme evolui.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+Sailing+skill+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Sailing+Skill+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=Sailing+skill+Valheim">Google</a>
</details>

<details><summary><strong>DiscoveryPins</strong> <code>0.3.10</code> • <em>Mapa, QoL</em></summary>
Cria pinos automaticamente ao descobrir recursos/locais (configurável).  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+Discovery+Pins+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Discovery+Pins+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=Discovery+Pins+Valheim">Google</a>
</details>

<details><summary><strong>UnderTheRadar</strong> <code>3.1.7</code> • <em>Mapa, QoL</em></summary>
Mostra colecionáveis, veios e POIs no minimapa; raio/categorias ajustáveis.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+UnderTheRadar+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Under+The+Radar+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=UnderTheRadar+Valheim">Google</a>
</details>

### Itens / Montarias / Utilitários

<details><summary><strong>Adventure Backpacks</strong> <code>1.9.7</code> • <em>Itens, QoL</em></summary>
Mochilas com slots/efeitos; utilidade e visual aventureiro.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+Adventure+Backpacks+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Adventure+Backpacks+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=Adventure+Backpacks+Valheim">Google</a>
</details>

<details><summary><strong>Spyglass</strong> <code>3.1.1</code> • <em>Itens, UI/HUD</em></summary>
Luneta para inspecionar à distância e marcar pontos com precisão.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+Spyglass+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Spyglass+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=Spyglass+Valheim">Google</a>
</details>

<details><summary><strong>OdinHorse</strong> <code>1.5.0</code> • <em>Montaria, Conteúdo</em></summary>
Adiciona cavalos com sela/armadura; locomoção rápida na exploração.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+OdinHorse+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+OdinHorse+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=OdinHorse+Valheim">Google</a>
</details>

### Combate / Magia / Conteúdo

<details><summary><strong>Better Archery</strong> <code>1.9.81</code> • <em>Gameplay, QoL</em></summary>
Física de flechas melhorada, recuperação de setas, aljavas e mira agradável.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+Better+Archery+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Better+Archery+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=Better+Archery+Valheim">Google</a>
</details>

<details><summary><strong>Epic Loot</strong> <code>0.11.6</code> • <em>Loot, Conteúdo</em></summary>
Sistema ARPG de raridades/afixos, com encantamento e identificação.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+Epic+Loot+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Epic+Loot+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=Epic+Loot+Valheim">Google</a>
</details>

<details><summary><strong>Creature Level & Loot Control (CLLC)</strong> <code>4.6.4</code> • <em>Balance, Loot</em></summary>
Controla níveis/estrelas, afixos de inimigos e tabelas de drop (balance).  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+Creature+Level+%26+Loot+Control+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Creature+Level+and+Loot+Control+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=CLLC+Valheim">Google</a>
</details>

<details><summary><strong>Warfare</strong> <code>1.8.9</code> • <em>Conteúdo, Combate</em></summary>
Pacote grande de armas, armaduras e progressão de combate.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+Therzie+Warfare+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Therzie+Warfare+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=Therzie+Warfare+Valheim">Google</a>
</details>

<details><summary><strong>Armory</strong> <code>1.3.1</code> • <em>Conteúdo, Craft</em></summary>
Estação/árvore de craft que integra o conteúdo do Warfare.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+Therzie+Armory+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Therzie+Armory+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=Therzie+Armory+Valheim">Google</a>
</details>

<details><summary><strong>Warfare Fire & Ice</strong> <code>2.0.8</code> • <em>Conteúdo, Combate</em></summary>
Expansão elemental (fogo/gelo) para o arsenal do Warfare.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+Warfare+Fire+and+Ice+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Warfare+Fire+and+Ice+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=Therzie+Warfare+Fire+%26+Ice+Valheim">Google</a>
</details>

<details><summary><strong>Wizardry</strong> <code>1.1.8</code> • <em>Magia, Conteúdo</em></summary>
Cajados/varinhas, armaduras de Eitr e progressão mágica.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+Therzie+Wizardry+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Therzie+Wizardry+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=Therzie+Wizardry+Valheim">Google</a>
</details>

<details><summary><strong>MagicPlugin (blacks7ar)</strong> <code>2.1.8</code> • <em>Magia, Conteúdo</em></summary>
Itens e feitiços focados em magia; complementa sistemas místicos.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+MagicPlugin+blacks7ar+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+MagicPlugin+blacks7ar+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=MagicPlugin+blacks7ar+Valheim">Google</a>
</details>

<details><summary><strong>RenegadeVikings (blacks7ar)</strong> <code>1.3.9</code> • <em>Conteúdo, Eventos</em></summary>
Novos inimigos humanóides, encontros e equipamentos temáticos.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+RenegadeVikings+blacks7ar+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Renegade+Vikings+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=RenegadeVikings+blacks7ar+Valheim">Google</a>
</details>

<details><summary><strong>Shield Me Bruh!</strong> <code>1.1.1</code> • <em>Combate, QoL</em></summary>
Ajustes de escudos (parry/timing) para defesa mais responsiva.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+Shield+Me+Bruh+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Shield+Me+Bruh+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=Shield+Me+Bruh+Valheim">Google</a>
</details>

<details><summary><strong>Monstrum</strong> <code>1.5.1</code> • <em>Conteúdo, Mobs</em></summary>
Novas criaturas e eventuais chefes/variantes desafiadoras (pools configuráveis).  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+Therzie+Monstrum+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Therzie+Monstrum+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=Therzie+Monstrum+Valheim">Google</a>
</details>

<details><summary><strong>Seasonality</strong> <code>3.5.0</code> • <em>Mundo, Imersão</em></summary>
Estações do ano com clima e visuais customizáveis; altera a atmosfera do mundo.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+Seasonality+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Seasonality+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=Seasonality+Valheim">Google</a>
</details>

### Extras

<details><summary><strong>TranslationsHelper</strong> <code>1.2.8</code> • <em>Biblioteca</em></summary>
Infraestrutura de localização para textos/strings personalizados.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+TranslationsHelper+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Translations+Helper+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=TranslationsHelper+Valheim">Google</a>
</details>

<details><summary><strong>Passive Powers</strong> <code>1.1.3</code> • <em>Gameplay, QoL</em></summary>
Permite configurar certos poderes guardiões como efeitos passivos/alternativos.  
<strong>Links:</strong> <a href="https://www.google.com/search?q=site%3Athunderstore.io+Passive+Powers+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Passive+Powers+Valheim">Nexus</a> • <a href="https://www.google.com/search?q=Passive+Powers+Valheim">Google</a>
</details>

---

## Lista crua (copiar/colar)

```
Adventure Backpacks v1.9.7
Armory v1.3.1
Auto Fuel v1.3.1
AutomaticFermenters v1.0.8
AzuAutoStore v3.0.8
AzuCraftyBoxes v1.8.5
AzuExtendedPlayerInventory v1.4.12
Better Archery v1.9.81
BetterUI v2.5.9
BepInExPack Valheim 5.4.x
Blacksmithing (Skill) v1.3.2
Building Health Display v0.7.1
CameraTweaks v1.3.1
CartographySkill v3.1.1
CLLC (Creature Level & Loot Control) v4.6.4
Configuration Manager v18.4.1
CookingStationTweaks v0.7.1
DiscoveryPins v0.3.10
Display Day & Time Countdown v1.0.0
Epic Loot v0.11.6
Farming (Skill) v2.2.1
FirstPersonMode v1.3.10
MagicPlugin (blacks7ar) v2.1.8
MassFarming v1.11
Minimal Status Effects v1.0.7
Mining (Skill) v1.1.5
Monstrum v1.5.1
OdinArchitect v1.5.7
OdinHorse v1.5.0
Passive Powers v1.1.3
PlantEasily v2.0.3
PlantEverything v1.20.0
Quick Stack - Store - Sort - Restock v1.4.13
RenegadeVikings (blacks7ar) v1.3.9
Sailing (Skill) v1.1.7
SaveCrossbowState v1.0.2
Seasonality v3.5.0
Shield Me Bruh! v1.1.1
Smart Containers Mod v1.7.0
Spyglass v3.1.1
StumpsRegrow v1.0.4
TargetPortal v1.2.1
TorchesEternal v0.2
TranslationsHelper v1.2.8
UnderTheRadar v3.1.7
Warfare v1.8.9
Warfare Fire & Ice v2.0.8
Wizardry v1.1.8
XUnity Resource Redirector v2.1.0
Jötunn (JVL) v2.27.0
Newtonsoft.Json Detector v1.0.0
YamlDotNet Detector v1.0.0
AutoRepair v5.4.1600
```

---

## Mods recomendados (aderentes ao pack)

> Seleção para expandir qualidade de vida, construção e progressão **sem quebrar** o estilo do seu modpack.

<details>
<summary><strong>Ward Is Love</strong> • <em>Base</em></summary>
Gestão avançada de wards (permissões por jogador, área ampliada, QoL).  
<a href="https://www.google.com/search?q=site%3Athunderstore.io+Ward+Is+Love+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Ward+Is+Love+Valheim">Nexus</a>
</details>

<details>
<summary><strong>Jewelcrafting (RandyKnapp)</strong> • <em>Loot</em></summary>
Gemas para engastar em equipamentos (sinergia com Epic Loot). Requer EIDF.  
<a href="https://www.google.com/search?q=site%3Athunderstore.io+Jewelcrafting+RandyKnapp+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Jewelcrafting+RandyKnapp+Valheim">Nexus</a>
</details>

<details>
<summary><strong>Extended Item Data Framework (EIDF)</strong> • <em>Biblioteca</em></summary>
Framework necessário para soquetes/gemas e outros mods orientados a dados.  
<a href="https://www.google.com/search?q=site%3Athunderstore.io+Extended+Item+Data+Framework+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Extended+Item+Data+Framework+Valheim">Nexus</a>
</details>

<details>
<summary><strong>Equipment & Quick Slots</strong> • <em>Inventário</em></summary>
Slots dedicados (anel/capa etc.) e atalhos rápidos; verificar compatibilidade com inventários estendidos.  
<a href="https://www.google.com/search?q=site%3Athunderstore.io+Equipment+and+Quick+Slots+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Equipment+and+Quick+Slots+Valheim">Nexus</a>
</details>

<details>
<summary><strong>Item Drawers</strong> • <em>Inventário</em></summary>
Gavetas visuais de armazenamento; combina com AzuAutoStore/Smart Containers.  
<a href="https://www.google.com/search?q=site%3Athunderstore.io+Item+Drawers+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Item+Drawers+Valheim">Nexus</a>
</details>

<details>
<summary><strong>PlanBuild</strong> • <em>Construção</em></summary>
Planejamento de construção (blueprints/planos) para erguer bases gigantes com custo controlado.  
<a href="https://www.google.com/search?q=site%3Athunderstore.io+PlanBuild+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+PlanBuild+Valheim">Nexus</a>
</details>

<details>
<summary><strong>Snap Points Made Easy</strong> • <em>Construção</em></summary>
Snapping e pontos de encaixe facilitados para alinhamento preciso.  
<a href="https://www.google.com/search?q=site%3Athunderstore.io+Snap+Points+Made+Easy+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Snap+Points+Made+Easy+Valheim">Nexus</a>
</details>

<details>
<summary><strong>Item Stand All Items</strong> • <em>Construção</em></summary>
Permite exibir praticamente qualquer item em pedestais/stands (decoração temática).  
<a href="https://www.google.com/search?q=site%3Athunderstore.io+Item+Stand+All+Items+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Item+Stand+All+Items+Valheim">Nexus</a>
</details>

<details>
<summary><strong>Simple Recycling</strong> • <em>Craft</em></summary>
Recicla equipamentos para recuperar parte dos materiais.  
<a href="https://www.google.com/search?q=site%3Athunderstore.io+Simple+Recycling+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Simple+Recycling+Valheim">Nexus</a>
</details>

<details>
<summary><strong>Better Trader (Remake)</strong> • <em>Economia</em></summary>
Mercador expandido: mais itens/categorias e preços equilibráveis.  
<a href="https://www.google.com/search?q=site%3Athunderstore.io+Better+Trader+Remake+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Better+Trader+Valheim">Nexus</a>
</details>

<details>
<summary><strong>AllTameable (Buzz)</strong> • <em>Mobs</em></summary>
Permite domar mais criaturas (com equilíbrio configurável).  
<a href="https://www.google.com/search?q=site%3Athunderstore.io+AllTameable+Buzz+Valheim">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+AllTameable+Valheim">Nexus</a>
</details>

<details>
<summary><strong>BoneAppetit / Cooking Skill</strong> • <em>Culinária</em></summary>
Habilidade/cozinha estendida para progressão culinária mais profunda (escolha a variante compatível mais recente).  
<a href="https://www.google.com/search?q=site%3Athunderstore.io+Valheim+Cooking+Skill">Thunderstore</a> • <a href="https://www.google.com/search?q=site%3Anexusmods.com+Valheim+Cooking+Skill">Nexus</a>
</details>

---

## Créditos

* Desenvolvedores dos mods listados (Thunderstore / Nexus).
* Comunidade Valheim por APIs e bibliotecas (JVL, XUnity, etc.).

> ⚠️ Todos os mods pertencem aos seus respectivos autores. Este repositório apenas documenta e organiza os links e o uso dentro do jogo.
