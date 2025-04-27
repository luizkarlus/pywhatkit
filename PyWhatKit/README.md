# WhatsApp Message Sender usando PyWhatKit 📱

Este projeto demonstra como enviar mensagens instantâneas no WhatsApp usando Python e a biblioteca **PyWhatKit**.

## 📋 Pré-requisitos

Antes de começar, você precisa ter:

- Python instalado (recomendo Python 3.8 ou superior)
- Google Chrome instalado
- A biblioteca `pywhatkit` instalada

## 📦 Instalação

1. Clone este repositório ou crie seu arquivo Python:
   ```bash
   git clone https://github.com/luizkarlus/pywhatkit.git
   ```

2. Instale o **PyWhatKit**:
   ```bash
   pip install pywhatkit
   ```

## 🚀 Como usar

No seu script Python, adicione o seguinte código:

```python
import pywhatkit as kit

kit.sendwhatmsg_instantly("+5521912345678", "Teste PyWhatKit")
```

### Explicação:

- **`+5521912345678`** → Número de telefone do destinatário (incluindo o código do país).
- **`"Teste PyWhatKit"`** → Mensagem de texto que será enviada.

> ⚠️ Atenção:  
> Certifique-se que seu WhatsApp Web esteja logado no navegador padrão (normalmente o Chrome). O script abrirá automaticamente uma nova aba para o envio.

## 🛠 Detalhes Técnicos

- `sendwhatmsg_instantly` é uma função que envia a mensagem imediatamente após abrir o WhatsApp Web.
- O PyWhatKit simula o comportamento humano, esperando alguns segundos para garantir o carregamento da página.

## 🎥 Tutorial usado

Este projeto foi inspirado no tutorial do YouTube:  
[Automação de envio de mensagens com PyWhatKit (Vídeo)](https://www.youtube.com/watch?v=cz7vTT9UhUk&t=1s)

## 📜 Licença

Este projeto é livre para uso pessoal e educacional. 🚀