# 💻 Projetos em C — Rafael Costa

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![Status](https://img.shields.io/badge/status-ativo-35e3a3?style=flat-square)
![License](https://img.shields.io/badge/licença-MIT-34c3e6?style=flat-square)
[![Rodar ao vivo](https://img.shields.io/badge/▶_rodar_ao_vivo-no_navegador-35e3a3?style=flat-square)](https://rafscorp.github.io/Projetos_Interativos/)

Projetos que fui construindo aprendendo C na prática — sem curso pronto, direto no terminal, testando até funcionar.

As pastas estão na ordem que fui evoluindo mesmo: do primeiro programa depois de poucos dias de C até um sistema com structs e memória dinâmica.

## 📂 Projetos

| Projeto | Nível | O que tem dentro |
|---|---|---|
| [`Caixa - Eletrônico`](./Projetos%20-%20\(C\)/Caixa%20-%20Eletrônico) | 🟢 Iniciante | Caixa eletrônico: saques, distribuição de cédulas, interface colorida |
| [`Calculadora_Dinamica`](./Projetos%20-%20\(C\)/Calculadora_Dinamica) | 🟡 Intermediário | Calculadora científica + uni-funcional, Fibonacci, PA, logs em arquivo |
| [`Mercado_project`](./Projetos%20-%20\(C\)/Mercado_project) | 🔴 Avançado | Cadastro de produtos/clientes com struct, malloc/realloc/free, validação de CPF |

Cada pasta tem seu próprio README com instruções de compilação.

## Como compilar

```bash
cd "Projetos - (C)/<nome-do-projeto>"
gcc <arquivo>.c -o programa      # -lm se usar sqrt/pow
./programa                        # Linux/macOS
programa.exe                      # Windows (MinGW)
```

## Tecnologias

C puro (GCC), códigos ANSI pra cor no terminal, ponteiros e memória dinâmica, struct, `#ifdef _WIN32` pra portabilidade.

## Próximos passos

Modularizar os maiores em `.h`/`.c`, persistência em arquivo no Mercado_project, e novos projetos conforme eu for avançando.

## Autor

Rafael Costa — [github.com/rafscorp](https://github.com/rafscorp) · [LinkedIn](https://www.linkedin.com/in/adrian-rafael-28455a361)

## Licença

MIT — uso livre, veja [LICENSE](./LICENSE).
