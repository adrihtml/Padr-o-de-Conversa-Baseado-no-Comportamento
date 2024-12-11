# Padrão de Conversa Baseado no Comportamento
Este projeto foi criado para mapear traços de personalidade e comportamentos com base em uma conversa exportada do WhatsApp. O script analisa mensagens filtradas e gera estatísticas detalhadas sobre padrões de linguagem e uso de emojis, oferecendo um resumo personalizado.

# 📋 Funcionalidades
- **Carregar mensagens**: Importa mensagens de um arquivo de texto exportado do WhatsApp.
- **Filtrar mensagens**: Filtra mensagens com base em um termo ou nome específico.
- **Analisar comportamento**: Identifica termos relacionados a carinho, raiva, assertividade, humor e emojis.
- **Gerar padrões de conversa**: Produz um resumo detalhado dos traços de personalidade.

## 🚀 Como usar
1. **Pré-requisitos**:  
   - Python 3.8 ou superior.
   - Arquivo de conversa do WhatsApp exportado (.txt).

2. **Preparação do ambiente**:  
   - Certifique-se de ter o Python instalado no seu sistema.
   - Instale dependências (caso necessário) usando:  
     ```bash
     pip install -r requirements.txt
     ```
   *(Nenhuma biblioteca externa é usada neste projeto.)*

3. **Executando o script**:  
   - Salve o arquivo de conversa exportado no formato `.txt`.
   - Execute o script:  
     ```bash
     python analisador_personalidade.py
     ```
   - Insira os dados solicitados:  
     - **Caminho do arquivo** (ex.: `/content/Conversa.txt`).
     - **Nome ou termo para filtrar** (ex.: `Adri`).

4. **Resultado**:  
   O script irá exibir o padrão de conversa com as estatísticas da personalidade no terminal.

## 📊 Exemplo de Saída

![image](https://github.com/user-attachments/assets/fae09fab-c84c-47cb-be79-20b395c14703)

# 🛠️ Personalizações
Você pode ajustar os seguintes elementos:

Palavras-chave e emojis: Adicione ou remova palavras e emojis nas listas de palavras-chave para personalizar a análise.
Limites de análise: Modifique a lógica de contagem ou crie novos parâmetros para análise.


# 🐞 Possíveis Problemas
Arquivo não encontrado: Certifique-se de fornecer o caminho correto do arquivo.
Nenhuma mensagem encontrada: Verifique o termo usado no filtro e se há correspondências no arquivo.




