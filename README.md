# Titulo 


# modelo que iremos guardar no banco

```
class Pessoa(Model):
    name= Column() 
    password= Column() 
    email
    data_criacao= null
    cpf = null
    fl_active = True 

```

schema --> Modelo para recebimento ou saída de dados

Dados que ele vai inserir para cadastrar no sistema

# Modelo de Cadastro
```
class PessoaCadastro(BaseModel):
    name:str 
    password:str
    email:str

```
- Modelo de entrada de dados, classe representa a entrada de dados via formulário da página html

# Modelo de Login
```
class PessoaLogin(BaseModel):
    email:str 
    password:str

```

# Modelo de Exibição

```
class PessoaOut(BaseModel):
    name:str 
    email:str
    telefone:str

```







