# 💻 Projetos em C — Rafael Costa

Repositório com os projetos que venho construindo enquanto aprendo a linguagem C "na prática" — sem curso pronto, direto no terminal, testando ideia por ideia até funcionar de verdade.

A ordem das pastas abaixo é também a ordem em que fui evoluindo: do primeiro programa depois de poucos dias de C até um sistema com structs, memória dinâmica e validação de dados.

---

## 📂 Projetos

| Projeto | Nível | O que tem dentro |
|---|---|---|
| [`Caixa - Eletrônico`](./Projetos%20-%20\(C\)/Caixa%20-%20Eletrônico) | 🟢 Iniciante | Simulador de caixa eletrônico: saques, distribuição de cédulas, interface colorida no terminal |
| [`Calculadora_Dinamica`](./Projetos%20-%20\(C\)/Calculadora_Dinamica) | 🟡 Intermediário/Avançado | Calculadora científica + uni-funcional, Fibonacci, Progressão Aritmética e um sistema de **logs em arquivo** |
| [`Mercado_project`](./Projetos%20-%20\(C\)/Mercado_project) | 🔴 Avançado | Cadastro de produtos e clientes com `struct`, memória dinâmica (`malloc`/`realloc`/`free`) e validação de CPF/preço |

Cada pasta tem seu próprio `README.md` com detalhes, exemplos de uso e instruções de compilação específicas.

---

## 🚀 Como compilar (padrão geral)

```bash
cd "Projetos - (C)/<nome-do-projeto>"
gcc <arquivo>.c -o programa
./programa          # Linux/macOS
programa.exe         # Windows (MinGW)
```

> Alguns projetos usam funções matemáticas (`sqrt`, `pow`) e nesse caso precisam do `-lm` na compilação — isso está anotado no README de cada um.

---

## 🧠 Por que esse repositório existe

Não é um repositório de "curso", é o registro real da minha evolução em C: cada pasta é um projeto fechado, funcional, que resolve um problema específico (caixa eletrônico, calculadora, sistema de cadastro). Prefiro aprender construindo coisa que roda de verdade a decorar sintaxe solta.

Os comentários dentro do código explicam o raciocínio de cada parte — não só o "o quê", mas o "por quê" das escolhas (por que usar `realloc` em vez de um array fixo, por que validar CPF daquele jeito, etc.).

---

## 🛠️ Tecnologias e conceitos por trás

- **C puro** (sem frameworks), compilado com GCC
- Códigos ANSI para cores e formatação no terminal
- Ponteiros e alocação dinâmica de memória
- `struct` para modelar dados (produtos, clientes)
- Validação de entrada do usuário
- Compatibilidade Windows/Linux via `#ifdef _WIN32`

---

## 📈 Próximos passos

- Modularizar os projetos maiores em `.h` / `.c`
- Adicionar persistência em arquivo no `Mercado_project`
- Testes automatizados básicos
- Novos projetos conforme eu for avançando (listas ligadas, arquivos, structs mais complexas)

---

## 👤 Autor

**Rafael Costa**
GitHub: [github.com/rafscorp](https://github.com/rafscorp)
LinkedIn: [linkedin.com/in/adrian-rafael-28455a361](https://www.linkedin.com/in/adrian-rafael-28455a361)

---

## 📄 Licença

Este repositório está sob a licença MIT — uso livre para estudo, modificação e evolução (veja [LICENSE](./LICENSE)).
