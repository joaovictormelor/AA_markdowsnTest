### RQ01 - Cadastro de Usuários


#### **Atores:**
&nbsp;&nbsp;&nbsp;&nbsp; Usuário - Insere, edita e exclui sua conta.


#### **Descrição suncita:**
&nbsp;&nbsp;&nbsp;&nbsp; Permitir que os novos clientes se registrem no sitema para que possam relaizar compras.


#### **Pré condição**
O usuário deve fornecer dados válidos


### **Fluxo Principal:**
1 - O ator acessa a tela inicial do sistema e seleciona a opção "Criar Cadastro"; \
2 - O sistema exibi na tela o sistema de cadastro de novo usuário contendo: \
Nome: &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  Data de nascimento: \
E-mail:&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp; &nbsp; Telefone: \
CPF: &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; Sexo:\
Endereço: &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; Senha:

3 - O usuário após preencher odos os dados corretamente confirma o cadastro de novo usuário.

4 - o sistema aloca todos os dados do novo usuário para o banco de dados e emite uma menssagem para o usuário "Cadastro Concluído" e o direciona para a tela inicial do sistema;

### **Campos do formulário:**

**Campo** | **Obrigatório?** | **Editável** | **Formato**
--|--|--|--
Nome|Sim|Sim|Texto
Data de Nascimento|Sim|Sim|Numérico
CPF| Não| Sim| Numérico|
Sexo|Não| Sim| Texto|
Endereço | Não| Sim| Alfanumérico
Senha| Sim| Sim| Alfa-Numérico

#### **Opções do Usuário:**

**Opção** | **Descrição**
--|--
Confirmar | Confirmar criação de conta
Cancelar | Cancelar criação de conta

#### **Fluxo Alternativos:**

**FA01 -** Login \
1- Se exitir um email com a conta que ta tentando ser adicionada sera redirecionado para login
