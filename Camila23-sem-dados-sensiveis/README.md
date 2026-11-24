# Camila 23 ✨ Confirmação de Presença (RSVP)

Landing page temática dos anos 2000 (Y2K cyber-fairy) para a festa de comemoração de aniversário da Camila.

## 🪩 Funcionalidades

- **Design Fiel ao Convite**: Tipografia Varsity "CAMILA 23", coração 3D jelly com "24 DE OUTUBRO ÀS 17H", balões com corações pixelados 8-bit, CDs holográficos, globo de espelhos rosa e celular flip retrô.
- **Confirmação de Presença (RSVP)**:
  - Nome completo e WhatsApp
  - Confirmação ou recusa
  - Quantidade e nomes dos acompanhantes
  - Preferência de bebida (Cerveja, Drinks, Refrigerante, etc.)
  - Restrição alimentar
  - Pedido de música para o churrasco
  - Recadinho carinhoso de parabéns
- **Envio Direto para o E-mail / Demonstração**:
  - Envio automático configurável via FormSubmit AJAX (com simulação interativa segura no modo portfólio).
  - Opção para enviar comprovante instantâneo no WhatsApp.
  - Botão de adicionar à Google Agenda e download de arquivo `.ics` (Apple/Outlook).
- **Painel da Organizadora**:
  - Acesso à lista completa de confirmados com busca e filtros (adicione `?admin=1` na URL).
  - Contagem total de pessoas (convidados + acompanhantes).
  - Resumo de bebidas preferidas.
  - Exportação da lista completa para Excel / CSV em 1 clique.
- **Efeitos Sonoros Retrô 2000s**: Efeitos sintetizados via Web Audio API (sem dependências de áudios externos).

---

## 🚀 Como Hospedar no GitHub Pages Grátis

O projeto já está 100% configurado com caminhos relativos (`base: './'` no Vite) e com o fluxo do GitHub Actions pronto em `.github/workflows/deploy.yml`.

### Passo a passo rápido:

1. Crie um novo repositório no seu GitHub (exemplo: `camila-23`).
2. No seu computador, suba os arquivos com os comandos:
   ```bash
   git init
   git add .
   git commit -m "Landing page Camila 23"
   git branch -M main
   git remote add origin https://github.com/SEU_USUARIO/camila-23.git
   git push -u origin main
   ```
3. No GitHub:
   - Abra **Settings** > **Pages**.
   - Em **Build and deployment > Source**, selecione **GitHub Actions**.
4. Pronto! O GitHub Pages fará o deploy automático e disponibilizará o link público para você adicionar no seu portfólio!

### Configuração de e-mail real (opcional):
Para receber os dados em um e-mail real em vez do modo de demonstração, basta alterar o valor de `recipientEmail` em `src/utils/rsvp.ts` para o seu endereço de e-mail.
