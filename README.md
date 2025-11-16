# 🚀 vs-code-setup (Foco: C#/.NET)

> Um repositório para centralizar e **armazenar todas as minhas configurações pessoais** do Visual Studio Code para desenvolvimento C#/.NET.

Este projeto serve como um backup pessoal e um "kit de produtividade" do meu ambiente de desenvolvimento. O objetivo é armazenar e versionar minhas configurações (`settings.json`), extensões e snippets customizados.

Isso resolve dois problemas principais:
1.  **Backup e Sincronização:** Permite que eu replique meu ambiente de desenvolvimento completo em qualquer máquina rapidamente.
2.  **Produtividade:** Resolve gargalos comuns (como criar classes/namespaces manualmente) através de snippets otimizados.

---

## 🎯 O Problema que Isso Resolve

Comecei este projeto porque precisava de um local central para minhas configurações e, ao mesmo tempo, estava cansado de criar manualmente a estrutura de classes, interfaces e ajustar o `namespace` baseado na estrutura de pastas do projeto no VS Code.

Estes arquivos automatizam esses processos e aceleram o desenvolvimento diário.

## ✨ O que este repositório armazena?

* **`/snippets/csharp.json`**: Meu conjunto de snippets de código C# que automatiza a criação de classes, propriedades, construtores e mais.
* **`(Em Breve) /extensions.json`**: A lista exata de extensões que eu uso para C# e desenvolvimento geral.
* **`(Em Breve) /settings.json`**: Minhas configurações pessoais (`settings.json`) para formatação, fontes e comportamento do editor.

---

## 🚀 Como Usar

Você pode usar o repositório inteiro para replicar meu setup ou apenas as partes que lhe interessam (como os snippets).

### 1. Snippets de C#

Estes são os atalhos que mais economizam tempo.

**Como Instalar:**

1.  No VS Code, aperte `Ctrl+Shift+P` (ou `Cmd+Shift+P` no Mac).
2.  Digite `Snippets` e escolha a opção: **"Preferences: Configure User Snippets"**.
3.  Na lista, selecione `csharp.json`. (Se não existir, o VS Code criará o arquivo).
4.  Copie o conteúdo do arquivo `snippets/csharp.json` [deste repositório](#) e cole dentro do arquivo que o VS Code abriu.
5.  Salve e pronto!

**Snippets Disponíveis:**

| Prefixo (Atalho) | Descrição |
| :--- | :--- |
| `csclass` | Cria uma classe C# com `namespace` dinâmico (baseado no projeto/pasta). |
| `csinterface` | Cria uma interface C# com `namespace` dinâmico. |
| `csservice` | Cria uma classe de serviço que já implementa sua interface. |
| `csprop` | Gera uma auto-property (`public string Nome { get; set; }`). |
| `csctor` | Insere um construtor para a classe atual. |
| `log` | Insere um `Console.WriteLine();` para debug rápido. |
| `csrecord` | Cria a estrutura de um Record com `namespace` dinâmico. |
| `csenum` | Cria a estrutura de um Enum com `namespace` dinâmico. |
| `csmethod` | Cria um método público simples. |
| `cstoString`| Override do método `ToString()`. |


[SEU-JSON-AQUI]
// Cole aqui o JSON completo que você me mostrou



-----

### 2\. Extensões (Em Breve)

Para armazenar sua lista de extensões, rode este comando no seu terminal. Ele criará um arquivo `extensions.json` com todas as suas extensões atuais:

```bash
code --list-extensions > extensions.json
```

Depois, basta fazer o commit desse arquivo.

### 3\. Configurações (Em Breve)

Para armazenar suas configurações:

1.  No VS Code, aperte `Ctrl+Shift+P` e escolha **"Preferences: Open User Settings (JSON)"**.
2.  Copie o conteúdo desse arquivo.
3.  Cole-o em um arquivo `settings.json` neste repositório e faça o commit.

-----

## 🤝 Como Contribuir

Embora este seja meu setup pessoal, estou aberto a sugestões\! Se você tem um snippet matador que eu esqueci, uma sugestão de extensão ou uma melhoria:

1.  Faça um **Fork** deste repositório.
2.  Crie uma **Branch** para sua modificação (`git checkout -b feature/meu-snippet-incrivel`).
3.  Faça o **Commit** das suas mudanças.
4.  Abra um **Pull Request**.

Você também pode abrir uma **Issue** para sugerir uma nova feature.

## 📝 Licença

Este projeto é distribuído sob a licença MIT. Sinta-se livre para usar e modificar como quiser.

