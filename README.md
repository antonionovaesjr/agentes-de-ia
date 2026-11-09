# Agentes de IA — Grandes Debates Nacionais

Plataforma experimental de deliberação autônoma multiagente onde modelos de Inteligência Artificial de ponta (**Maritaca AI**, **Google Gemini** e **Anthropic Claude**) representam visões econômicas e educacionais contrapostas e negociam termos de consenso viáveis para o Brasil até 2030.

---

## 🏛️ Debates e Consensos Disponíveis

- **Economia Brasil 2030**:
  - [Proposta de Consenso Econômico](economia/proposta_consenso_DEBATE_20261108_214942_1C0F76.md)
  - [Transcrição Integral das 10 Rodadas](economia/resultado_debate_10_rodadas_DEBATE_20261108_214942_1C0F76.md)
- **Educação Brasil 2030**:
  - [Proposta de Consenso Educacional](educacao/proposta_consenso_educacao_DEBATE_EDUC_20261108_222513_445778.md)
  - [Transcrição Integral das 10 Rodadas](educacao/resultado_debate_educacao_10_rodadas_DEBATE_EDUC_20261108_222513_445778.md)

---

## 📖 Portal de Documentação (MkDocs + Material)

Este repositório inclui uma documentação completa e elegante construída com **MkDocs** e o tema **Material for MkDocs**, com modo escuro/claro, fórmulas matemáticas, gráficos e visualização interativa dos debates.

### Como Executar Localmente

1. **Crie e ative o ambiente virtual:**
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```

2. **Instale as dependências:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Inicie o servidor de desenvolvimento:**
   ```bash
   mkdocs serve
   ```
   Acesse no seu navegador: `http://127.0.0.1:8000/`

4. **Gerar os arquivos estáticos (HTML/CSS):**
   ```bash
   mkdocs build --strict
   ```
   Os arquivos finais serão gerados no diretório `site/`.

---

## 🤖 Os Agentes Debatedores

- **Prof. Socialdo** (`Maritaca AI: S5-br-sp`): Foco desenvolvimentista, social, chão da escola e combate às desigualdades.
- **Dr. Isentão** (`Google GenAI: gemini-3.8-flash`): Consultor legislativo e orçamentário, mediação federativa e governança.
- **Dr. Livre-Mercado / Dr. Rigoroso** (`Anthropic: claude-sonnet-5-5`): Ortodoxia fiscal, monetarismo, evidências empíricas e avaliação de impacto.
