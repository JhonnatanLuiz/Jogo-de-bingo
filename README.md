# 🎲 Jogo de Bingo

Um jogo de bingo interativo e completo desenvolvido em HTML, CSS e JavaScript puro. Este projeto implementa todas as regras tradicionais do bingo com uma interface moderna e responsiva.

## 📋 Sobre o Projeto

Este é um jogo de bingo web que simula o sorteio de números seguindo as regras tradicionais do bingo americano (B-I-N-G-O). O jogo sorteia números aleatórios sem repetição e mantém um histórico visual de todos os números sorteados.

## ✨ Funcionalidades

- ✅ Sorteio aleatório de números seguindo as regras do bingo
- ✅ Sistema de letras B-I-N-G-O com faixas específicas de números
- ✅ Histórico visual de todos os números sorteados
- ✅ Indicador de progresso (números sorteados/total)
- ✅ Botão para reiniciar o jogo a qualquer momento
- ✅ Interface responsiva e moderna
- ✅ Cores diferenciadas para cada letra do bingo
- ✅ Validação para evitar números repetidos

## 🎮 Como Usar

1. Abra o arquivo `bingo.html` em seu navegador web
2. Clique no botão **"Sortear Número"** para sortear um número aleatório
3. O número sorteado aparecerá destacado na tela principal
4. Todos os números sorteados serão exibidos no histórico com cores específicas
5. Use o botão **"Reiniciar Jogo"** para começar uma nova partida

## 🎯 Regras do Jogo

O jogo segue as regras tradicionais do bingo americano:

| Letra | Faixa de Números | Cor         |
|-------|------------------|-------------|
| **B** | 1 - 15          | Vermelho    |
| **I** | 16 - 30         | Verde       |
| **N** | 31 - 45         | Azul        |
| **G** | 46 - 60         | Roxo        |
| **O** | 61 - 75         | Laranja     |

- Cada número só pode ser sorteado uma vez por jogo
- O jogo termina automaticamente quando todos os 75 números forem sorteados
- Os números são sorteados aleatoriamente respeitando as faixas de cada letra

## 💻 Tecnologias Utilizadas

- **HTML5** - Estrutura da página
- **CSS3** - Estilização e design responsivo
- **JavaScript** - Lógica do jogo e interatividade

## 🚀 Como Executar

Não é necessária nenhuma instalação ou configuração especial:

1. Clone este repositório:
   ```bash
   git clone https://github.com/JhonnatanLuiz/Jogo-de-bingo.git
   ```

2. Navegue até a pasta do projeto:
   ```bash
   cd Jogo-de-bingo
   ```

3. Abra o arquivo `bingo.html` diretamente no seu navegador web preferido

Ou simplesmente faça download do arquivo `bingo.html` e abra-o em qualquer navegador moderno.

## 📱 Compatibilidade

O jogo é compatível com todos os navegadores modernos:
- ✅ Google Chrome
- ✅ Mozilla Firefox
- ✅ Microsoft Edge
- ✅ Safari
- ✅ Opera

## 🎨 Interface

A interface do jogo conta com:
- Design moderno e limpo
- Botões com efeitos hover
- Bolas coloridas para cada letra do bingo
- Área de resultado destacada em amarelo
- Contador de progresso em tempo real
- Layout responsivo que se adapta a diferentes tamanhos de tela

## 📝 Estrutura do Código

O projeto consiste em um único arquivo HTML autocontido que inclui:
- **CSS embutido** - Todos os estilos da interface
- **JavaScript embutido** - Toda a lógica do jogo

### Principais Funções JavaScript:

- `sortearLetraBingo()` - Sorteia uma letra que ainda tenha números disponíveis
- `sortearNumeroBingo(letra)` - Sorteia um número específico de uma letra
- `sortear()` - Função principal que executa o sorteio
- `reiniciarJogo()` - Reinicia o jogo para uma nova partida

## 🤝 Contribuindo

Contribuições são sempre bem-vindas! Se você tem alguma sugestão para melhorar este projeto:

1. Faça um Fork do projeto
2. Crie uma Branch para sua feature (`git checkout -b feature/NovaFuncionalidade`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova funcionalidade'`)
4. Push para a Branch (`git push origin feature/NovaFuncionalidade`)
5. Abra um Pull Request

## 📄 Licença

Este projeto é de código aberto e está disponível para uso livre.

## 👤 Autor

**Jhonnatan Luiz**

- GitHub: [@JhonnatanLuiz](https://github.com/JhonnatanLuiz)

## 🌟 Mostre seu apoio

Se este projeto foi útil para você, considere dar uma ⭐️!

---

Desenvolvido com ❤️ por Jhonnatan Luiz
