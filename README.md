# 📦 Consumindo API do GitHub com Python

Este projeto faz uma requisição à [API pública do GitHub](https://docs.github.com/pt/rest/repos/repos?apiVersion=2022-11-28) para listar todos os repositórios públicos de um usuário.

## 💡 Como funciona?

O código utiliza a biblioteca `requests` para fazer a requisição HTTP, e exibe no terminal os nomes dos repositórios de um determinado usuário do GitHub.

---

## 🧑‍💻 Como usar

1. **Clone o repositório:**

```bash
git clone https://github.com/SeuUsuario/NomeDoRepo.git
```

2. **Acesse a pasta do projeto:**

```bash
cd NomeDoRepo
```

3. **Instale a biblioteca necessária:**

```bash
pip install requests
```

4. **Edite a linha 25 do código para usar o nome de usuário que desejar:**

```bash
repositorios = ListaDeRepositorios('LizaGomes97')  # substitua aqui
```

5. **Execute o código:**

```bash
python nome_do_arquivo.py
```

## ✨ Exemplo de saída

```bash
repo1
repo2
repo3
...
```
