# 🚀 DIO - Azure AI Language Studio Challenge  

## 🎯 Objetivo  
Praticar o uso das ferramentas **Azure Speech Studio** e **Language Studio**, explorando recursos de **análise de sentimentos e opiniões**, para desenvolver habilidades práticas em **IA aplicada à linguagem natural**.  

---

## 🔹 Passo a Passo  

### 1. Criação do Recurso de Linguagem no Azure  
- Acesse o **portal do Azure** e crie um recurso do tipo **Language**.  
- Configure:  
  - **Subscription**: Azure subscription 1  
  - **Resource group**: Teste  
  - **Region**: East US  
  - **Name**: idiomalanguagePedro  
  - **Pricing tier**: Free F0 (5K transações/mês).  
- Clique em **Review + create** e finalize a implantação ✅  

📸 *Screenshot: Tela de criação do recurso (`idiomalanguagePedro`).*  

---

### 2. Confirmação da Implantação  
- Após alguns segundos, a mensagem **“Your deployment is complete”** confirma que o recurso foi criado com sucesso.  
- O recurso aparece listado no grupo de recursos **Teste**.  

📸 *Screenshot: Tela de “Deployment complete” e listagem no resource group.*  

---

### 3. Conexão com o Language Studio  
- Acesse o **Language Studio**: [language.cognitive.azure.com](https://language.cognitive.azure.com).  
- Selecione o recurso criado:  
  - **Azure subscription**: Azure subscription 1  
  - **Resource type**: Language  
  - **Resource name**: idiomalanguagePedro  
- Clique em **Done** para vincular o recurso.  

📸 *Screenshot: Tela de seleção do recurso `idiomalanguagePedro`.*  

---

### 4. Escolha da Tarefa: Analyze Sentiment and Opinions  
- No **Language Studio**, selecione a aba **Classify text**.  
- Clique em **Analyze sentiment and mine opinions**.  
- Essa funcionalidade identifica se o texto é **positivo, negativo ou neutro**, além de extrair opiniões sobre diferentes aspectos.  

📸 *Screenshot: Tela inicial do Language Studio mostrando as opções.*  

---

### 5. Inserção do Texto de Teste  
- Exemplo utilizado:  

```text
I really enjoy using this new laptop because the battery lasts a long time and the screen is very clear. 
However, the keyboard feels uncomfortable and the fan is a bit noisy, which makes working for long hours frustrating.
