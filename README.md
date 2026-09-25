# 🌸 Spring Sound Festival 2026

**Integrantes:** Gustavo Mesquita, Gabriel Nazarre, Raul Nogueira. 
**Link do site na Vercel:** 

---

## 🎯 Briefing do Projeto

### Público-Alvo
Jovens e adultos entre 18 e 35 anos, amantes de música alternativa, indie, pop e brasilidades. Pessoas que valorizam experiências ao ar livre, sustentabilidade, arte urbana e momentos instagramáveis no pôr do sol.

### Clima do Festival (3 palavras)
`Vibrante`, `Solar`, `Acolhedor`

### Paleta de Cores
* **Fundo (`#f7f2ec`):** Bege suave, remetendo ao papel reciclado e leveza do dia.
* **Fundo Secundário (`#e5ceae`):** Tom areia para destacar cards e o cabeçalho.
* **Cor de Destaque (`#e58d05`):** Laranja pôr do sol para bordas e elementos informativos.
* **Cor de Ação (`#fc3f00`):** Vermelho vibrante para botões, badges e links importantes.

### Tipografia (Google Fonts)
* **Título (`Monoton`):** Escolhida por seu estilo geométrico e marcante, trazendo a identidade de grandes festivais e modernidade retrô.
* **Texto (`Montserrat` / `Roboto`):** Escolhidas pela alta legibilidade em dispositivos móveis e suporte a leituras longas.

---

## 💡 Inspirações Visuais

1. **Lollapalooza Brasil:** Gostamos da organização das áreas VIP e da disposição do card de ingressos.
2. **Primavera Sound:** Inspiração para a paleta de cores terrosas e layout fluido do line-up.
3. **Coachella:** Inspiração para os banners visuais e o contador regressivo na página inicial.

---

## 🖼️ Comparativo Visual (Evolução com IA)

* **Primeira Versão (Antes):** `img/antes.png`
* **Versão Final (Depois):** `img/depois.png`

---

## 🤖 Prompts Utilizados

1. *"Crie a estrutura do header e nav usando flexbox com uma paleta de cores acolhedora e estilo de festival de primavera."*
2. *"Ajuste o layout do line-up para usar cards alternados em linha (flex-direction row e row-reverse) com badge de palco."*
3. *"Crie uma tabela de preços de ingressos com destaque no card central (Passaporte) e suporte a parcelamento e badges de lote."*
4. *"Resuma e otimize o CSS global consolidando variáveis, tirando seletores duplicados e unificando as media queries no final."*

---

## 💻 Guia Técnico de CSS (Para Apresentação)

* **Flexbox (`display: flex`):** Utilizado no cabeçalho, rodapé e nos blocos de artistas para alinhar elementos lado a lado e organizar o espaçamento.
* **CSS Grid (`display: grid`):** Utilizado na grade de cards da Home, nos ingressos e na página de informações para criar colunas responsivas automáticas.
* **Variáveis CSS (`:root`):** Permitem centralizar as cores e fontes do site em um só lugar. Se alterarmos `--cor-acao`, todo o site muda instantaneamente.
* **Media Queries (`@media`):** Reorganizam o layout para telas pequenas (smartphones), transformando grades de 3 colunas em 1 única coluna legível.