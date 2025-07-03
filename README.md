# Gerador de Senhas Seguras com GUI em Python

Este é um aplicativo desktop intuitivo e robusto desenvolvido em **Python** utilizando a biblioteca **Tkinter**. Ele permite aos usuários gerar senhas aleatórias e criptograficamente seguras, oferecendo controle total sobre os critérios de geração, como comprimento e tipos de caracteres.

##  Destaques e Funcionalidades

* **Geração Personalizável:** Defina o comprimento da senha em uma escala flexível de 6 a 32 caracteres.
* **Controle de Caracteres:** Escolha incluir letras maiúsculas (A-Z), minúsculas (a-z), números (0-9) e símbolos especiais (!@#$%).
* **Segurança Criptográfica:** Utiliza o módulo `secrets` do Python para garantir que as senhas geradas são verdadeiramente aleatórias e seguras.
* **Interface Gráfica Intuitiva (GUI):** Desenvolvido com Tkinter e estilização `ttk.Style` para uma experiência de usuário limpa e moderna, com um tema escuro atraente.
* **Cópia Rápida:** Um botão dedicado permite copiar instantaneamente a senha gerada para a área de transferência do sistema.
* **Tratamento de Erros:** Feedback claro ao usuário em caso de seleções inválidas (ex: nenhum tipo de caractere escolhido).

##  Como Executar o Projeto

Para rodar este Gerador de Senhas em sua máquina local, siga os passos abaixo:

1.  **Clone o Repositório:**
    Abra seu terminal ou prompt de comando e execute:
    ```bash
    git clone [https://github.com/Joaofernandes-DEV/GeradorDeSenhasSegurasPython.git](https://github.com/Joaofernandes-DEV/GeradorDeSenhasSegurasPython.git)
    cd GeradorDeSenhasSegurasPython
    ```

2.  **Verifique as Dependências:**
    Este projeto utiliza apenas bibliotecas padrão do Python (`tkinter`, `secrets`, `string`). Portanto, não há necessidade de instalação via `pip install` para estas bibliotecas. Certifique-se de ter o Python 3.x instalado em seu sistema.

3.  **Execute o Aplicativo:**
    Dentro da pasta do projeto (`GeradorDeSenhasSegurasPython`), execute o script principal:
    ```bash
    python password_generator.py
    ```
    Isso abrirá a janela do aplicativo Gerador de Senhas Seguras.

##  Demonstração Visual

![Sem nome (600 x 600 px)](https://github.com/user-attachments/assets/4ada226d-e6ee-46b8-9837-1e0a2eb0c212)

---

##  Desenvolvimento

Este projeto foi desenvolvido por:

| [<img src="https://avatars.githubusercontent.com/u/170758704?s=400&u=da7a33d81f3feeb953e687442cba5d042527f94d&v=4" width=115><br><sub>João Vitor Fernandes</sub>](https://github.com/Joaofernandes-DEV) |
|:----------------------------------------------------------------------------------------------------------------------------------------------------------:|

## 📝 Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.
