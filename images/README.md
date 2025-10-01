# 📸 Evidências dos Testes de Força Bruta

Esta pasta contém as evidências visuais (**capturas de tela**) que validam a execução dos comandos e os resultados obtidos durante a simulação dos ataques de força bruta, conforme detalhado no `README.md` principal.

---

### 1. `1-ftp-nmap.png`

**Descrição:** Saída do comando `nmap -sV -p 21 <IP>`. Confirmação de que o serviço **FTP** (`vsftpd 2.3.4`) está ativo e acessível na porta 21 da máquina alvo (Metasploitable 2). Esta é a etapa inicial de **enumeração**.

### 2. `2-ftp-medusa.png`

**Descrição:** Tela do **Medusa** em execução, realizando o ataque de força bruta contra o serviço FTP. A imagem destaca a linha de **"ACCOUNT FOUND"** (Conta Encontrada), revelando as credenciais válidas obtidas (`msfadmin:msfadmin`).

### 3. `3-ftp-login-success.png`

**Descrição:** Validação do ataque. Demonstra o login bem-sucedido no servidor FTP (`ftp <IP>`) utilizando as credenciais descobertas pelo Medusa. O login com sucesso confirma a vulnerabilidade explorada.
