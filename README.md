# 🎙️ Transcritor - Edição de Pesquisa

O **Transcritor** é uma solução robusta e de alta fidelidade para transcrição de áudio e vídeo, desenvolvida especificamente para o ambiente acadêmico e de pesquisa. O diferencial principal é a **privacidade total**: o processamento de dados é 100% offline.

---

## 🚀 Funcionalidades (Features)

- **Transcrição de Mídia:** Suporte para arquivos `.mp4`, `.mkv`, `.mp3`, `.wav` e `.m4a`.
- **Privacidade LGPD:** Nenhum dado é enviado para a nuvem. Todo o processamento ocorre localmente no hardware do usuário.
- **Identificação de Silêncio (VAD):** Filtro inteligente de atividade de voz para maior precisão.
- **Exportação Multiformato:** Gera relatórios detalhados em texto puro (`.txt`) e documentos formatados (`.docx`).
- **Interface Premium:** Design escuro otimizado para longas jornadas de trabalho, focado em usabilidade corporativa.

---

## 🛠️ Tecnologias e Stacks Utilizadas

Este projeto foi construído utilizando o estado da arte em processamento de linguagem natural (NLP):

- **Linguagem Principal:** Python 3.x
- **Motor de IA:** `faster-whisper` (Baseado no modelo OpenAI Whisper com quantização CTranslate2 para alta performance em CPU).
- **Modelo Utilizado:** `Medium` (Equilíbrio ideal entre precisão linguística e velocidade).
- **Processamento de Mídia:** `MoviePy` & `FFmpeg`.
- **Interface Gráfica (GUI):** `CustomTkinter` (Arquitetura moderna e responsiva).
- **Processamento Neural:** `ONNX Runtime`.
- **Compilação e Instalação:** `PyInstaller` & `Inno Setup`.

---

## 💻 Requisitos de Sistema

Para garantir que a Inteligência Artificial processe os dados com fluidez, recomendam-se as seguintes especificações:

### Mínimos (Processamento Lento)
- **Sistema Operacional:** Windows 10 ou 11 (64 bits).
- **Processador (CPU):** Intel Core i3 (8ª geração) ou AMD Ryzen 3.
- **Memória RAM:** 8 GB.
- **Espaço em Disco:** 2 GB livres (para instalação e cache de modelos).

### Recomendados (Processamento Rápido)
- **Sistema Operacional:** Windows 10 ou 11 (64 bits).
- **Processador (CPU):** Intel Core i5/i7 (10ª geração ou superior) ou AMD Ryzen 5/7.
- **Memória RAM:** 16 GB.
- **Armazenamento:** SSD (Reduz drasticamente o tempo de carregamento do motor de IA).

---

## 🛠️ Notas de Instalação e Uso

1. **Primeira Execução:** Ao abrir o app pela primeira vez, o motor neural é inicializado. Isso pode levar alguns segundos dependendo da sua CPU.
2. **Desempenho:** Por ser uma ferramenta **100% Offline**, a velocidade da transcrição depende exclusivamente do poder de processamento do seu computador. 
3. **Privacidade:** O software não requer conexão com a internet em nenhum momento após a instalação.

## 📥 Instalação

Para utilizar o Transcritor, siga os passos abaixo:

1. Acesse a aba [Releases](https://github.com/cesajr/transcritor-app/releases) deste repositório.
2. Baixe o arquivo `Instalador_Transcritor1.0.exe`.
3. Execute o instalador e siga as instruções na tela.
4. O atalho será criado automaticamente na sua Área de Trabalho.

> **Nota de Segurança:** Por ser um software assinado de forma independente, o Windows SmartScreen pode exibir um alerta no primeiro uso. Clique em "Mais informações" e "Executar assim mesmo".

---

## 📜 Licença e Propriedade

Este software é uma licença de uso estritamente acadêmico e de pesquisa.

**Desenvolvedor:** Paulo César Junior  
**Privacidade:** Este software opera com princípio de *Privacy by Design*.  
**Contato:** [LinkedIn](https://www.linkedin.com/in/paulo-césar-junior)
