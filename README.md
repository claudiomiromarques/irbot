# 💰 IRBot - Assistente de Imposto de Renda com IA (Gemini)

Bem-vindo ao **IRBot**, um agente de inteligência artificial construído com a API do **Google Gemini**, voltado para tirar dúvidas sobre o **Imposto de Renda Pessoa Física (IRPF)** no Brasil.  
Este projeto foi desenvolvido com foco em **linguagem simples**, acessível a qualquer pessoa — mesmo leiga no assunto.

---

## 📌 Objetivo

Criar um chatbot educativo que:
- Responda dúvidas sobre o IRPF de forma clara e objetiva;
- Use linguagem acessível para todos os públicos;
- Funcione com histórico de conversa (memória contextual);
- Seja executado facilmente no **Google Colab**.

---

## 🧠 Tecnologias Utilizadas

- [Google Gemini AI](https://makersuite.google.com/app)
- [Google Colab](https://colab.research.google.com/)
- Python 3
- Markdown para exibição das respostas

---

## 🚀 Como Usar

1. Clone este repositório ou abra diretamente no Colab:
   ```bash
   git clone https://github.com/claudiomiromarques/irbot.git

Como obter sua API Key do Gemini
Acesse: Google AI Studio

Crie um projeto e gere sua chave da API

No Colab, use:

from google.colab import userdata
os.environ['GOOGLE_API_KEY'] = userdata.get('GOOGLE_API_KEY')

Execute o notebook célula por célula

Configure sua chave da API Gemini via userdata.get('GOOGLE_API_KEY'), caso não for o nome pradrão

## 🧠 Prompt Utilizado

O IRBot é instruído com o seguinte prompt base:

"Você é um assistente virtual que ajuda pessoas a entender o Imposto de Renda Pessoa Física (IRPF) no Brasil.
Explique de forma simples e direta, como se estivesse conversando com alguém que não entende nada do assunto.
Evite termos técnicos sempre que possível e não dê conselhos ilegais.
Seja claro, confiável e educativo em todas as respostas."

Interaja com o IRBot:

Digite perguntas como:

"Sou estagiário, preciso declarar IR?"

"Recebi herança, como declaro?"

"Qual o prazo para declarar em 2025?"

Digite sair para encerrar.

Exemplo de saída:

💰 IRBot: Olá! Sou seu assistente para dúvidas sobre o Imposto de Renda. Como posso ajudar?

Você: Ganhei menos de R$30.000 no ano. Preciso declarar?

💰 IRBot: Se você recebeu menos do que R$30.639,90 em 2024, está isento da declaração. No entanto, pode declarar se quiser, por exemplo, para obter restituição de imposto retido.


🤝 Contribuições
Contribuições são bem-vindas!
Sinta-se livre para abrir issues, sugerir melhorias ou enviar pull requests.

🙋 Autor
Desenvolvido por Claudiomiro Marques.
Projeto experimental com fins educacionais.

