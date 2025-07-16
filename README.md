# 🧙‍♂️ Desafio DIO: Classe Herói em JavaScript

[![Badge - Linguagem](https://img.shields.io/badge/JavaScript-yellow?style=for-the-badge&logo=javascript)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
[![Badge - Status](https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge)]()
[![Badge - Projeto DIO](https://img.shields.io/badge/DIO-Projeto-blueviolet?style=for-the-badge&logo=github)](https://dio.me)

Este repositório contém a resolução do desafio "Escrevendo as Classes de um Jogo" da plataforma **DIO.me**.

---

## 📌 Descrição do Desafio

Criar uma classe `Heroi` com as seguintes propriedades:

- `nome`
- `idade`
- `tipo` → "guerreiro", "mago", "monge", "ninja"

E um método `atacar()` que imprime:

```
"O {tipo} atacou usando {ataque}"
```

### 💥 Ataques por tipo:

| Tipo      | Ataque           |
|-----------|------------------|
| mago      | magia            |
| guerreiro | espada           |
| monge     | artes marciais   |
| ninja     | shuriken         |

---

## 📂 Estrutura do Projeto

```bash
classe-heroi-jogo-dio/
├── index.js       # Código principal
├── README.md      # Documentação
└── .gitignore     # Arquivos ignorados (opcional)
```

---

## 🧠 Código de Exemplo

```javascript
class Heroi {
  constructor(nome, idade, tipo) {
    this.nome = nome;
    this.idade = idade;
    this.tipo = tipo;
  }

  atacar() {
    let ataque = "";

    switch (this.tipo) {
      case "mago":
        ataque = "magia"; break;
      case "guerreiro":
        ataque = "espada"; break;
      case "monge":
        ataque = "artes marciais"; break;
      case "ninja":
        ataque = "shuriken"; break;
      default:
        ataque = "um ataque desconhecido";
    }

    console.log(`O ${this.tipo} atacou usando ${ataque}`);
  }
}
```

---

## ✅ Objetivos alcançados

- Uso de classes e objetos
- Estrutura de controle `switch`
- Organização de projeto em JS
- Envio para GitHub com versionamento

---

Desenvolvido por **Bruno Mateus** 🚀  
Projeto prático da [DIO.me](https://dio.me)