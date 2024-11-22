# Energyzo

## Equipe
- Enzo Oliveira - RM 551356
- João Vitor - RM 550381
- Pedro - RM 551446
- Matheus Colossal - RM 99572
- Igor - RM 550415

## Como Rodar a Aplicação

### Passo 1: Clone o repositório

```bash
git clone https://github.com/colossalmatheus/Energyzo.git
cd Energyzo
```

### Passo 2: Configurar a Aplicação

Antes de rodar a aplicação, você precisará configurar as credenciais do banco de dados e a chave da API. Abra o arquivo `application.properties` (ou o equivalente de configuração que esteja usando) e substitua as seguintes variáveis:

- `${user}`: Substitua pelo usuário do banco de dados.
- `${password}`: Substitua pela senha do banco de dados.
- `${API}`: Substitua pela chave da API que será utilizada.

### Passo 3: Rodar a Aplicação

Para rodar a aplicação, utilize o comando abaixo:

```bash
./mvnw spring-boot:run
```

Isso iniciará o servidor Spring Boot localmente.

### Observação
Certifique-se de que a porta 8080 esteja disponível. Caso encontre erros indicando que a porta está em uso, finalize o processo que está utilizando a porta 8080 antes de iniciar a aplicação.

