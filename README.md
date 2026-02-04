# 🇵🇹 Linux em Português: Terminal para Todos

Este projeto nasceu da ideia de tornar o terminal Linux mais amigável para quem fala português. Através de **aliases** (atalhos), traduzimos os comandos técnicos em inglês para termos intuitivos que usamos no dia a dia.

---

##  O que este projeto faz?
Ele cria uma camada de tradução sobre o seu terminal. Você não precisa mais decorar comandos como `sudo apt update`; basta digitar `atualizar`.

###  Exemplos de Comandos Inclusos:

| Comando em PT | Comando Original | O que faz? |
| :--- | :--- | :--- |
| `atualizar` | `sudo apt update && sudo apt upgrade` | Atualiza todo o sistema |
| `instalar` | `sudo apt install` | Instala um novo programa |
| `limpar` | `clear` | Limpa a tela do terminal |
| `ondeestou` | `pwd` | Mostra a pasta atual |
| `pc-info` | `neofetch` | Mostra detalhes do PC com estilo |

---

## 🛠️  Como Instalar no seu Linux (Mint, Kali, Ubuntu, etc.)

Para usar esses comandos no seu computador, siga estes passos simples:

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/MarcosHigildo-hub/comandos-pt.git](https://github.com/MarcosHigildo-hub/comandos-pt.git) ~/comandos-pt

2. **Ative os comandos no seu sistema:**
   Adicione a linha de ativação ao seu ficheiro de configuração do terminal (.bashrc):
    echo "source ~/comandos-pt/alias.sh" >> ~/.bashrc

3. **Reinicie o terminal:**
    Basta fechar e abrir o terminal ou digitar:
     source ~/.bashrc
---

### Contribuição
  **Este é um projeto aberto! Se você tiver uma ideia de um novo comando traduzido, sinta-se à vontade para:**
       1. Abrir uma Issue relatando a sugestão.
       2. Fazer um Pull Request com as suas próprias traduções.
