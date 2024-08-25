# Configuração de Ambiente Virtual Python no Linux

Este guia descreve como configurar um ambiente virtual Python no Linux, utilizando o terminal.

## Criando a Pasta de Trabalho

1. **Abra o Terminal:**  
   Inicie o terminal no seu ambiente Linux.

2. **Navegue até a pasta onde deseja criar o ambiente virtual:**  
   Use o comando `cd` para acessar o diretório desejado. Por exemplo, para acessar a pasta `Documentos` no seu diretório home:
   ```bash
   cd ~/Documentos
   ```

# Crie um diretório para o ambiente virtual:
Execute o comando mkdir para criar uma nova pasta onde o ambiente virtual será configurado:

```mkdir venv```

Agora temos a pasta preparada para configurar o ambiente virtual.
# Criando o Ambiente Virtual.
**Crie o ambiente virtual:**
Navegue até o diretório criado e utilize o comando ```python3 -m venv``` 
para configurar o ambiente virtual:
```cd venv ```
```python3 -m venv ```

**Após a execução do comando, a estrutura do diretório será similar à seguinte:**
```. ├── bin ├── include ├── lib └── pyvenv.cfg```
# Ativando o Ambiente Virtual.
** Ative o ambiente virtual:** 
Para começar a trabalhar no ambiente virtual de forma isolada, execute o seguinte comando:
 ```source bin/activate ```
Se tudo ocorrer corretamente, o nome do ambiente virtual aparecerá no início da linha de comando, indicando que o ambiente está ativo:(venv) ```user@machine:~/Documentos/venv$```
**Desativar o ambiente virtual:** 
Quando terminar de trabalhar no ambiente, você pode desativá-lo com o comando:
```deactivate```
# Considerações Finais
**Subir arquivos para o GitHub:**
Certifique-se de que apenas os arquivos necessários sejam enviados ao repositório. Por exemplo, adicione o diretório `venv` ao `.gitignore` para evitar enviar arquivos do ambiente virtual.
**Exemplo de `.gitignore`:**
```venv/```
```.gitignore```
**Documentação:**
Documente os passos e as funcionalidades do seu projeto criando um arquivo `README.md` claro e objetivo.

Este texto formatado em Markdown pode ser utilizado como um arquivo `README.md` em seu repositório Git.
