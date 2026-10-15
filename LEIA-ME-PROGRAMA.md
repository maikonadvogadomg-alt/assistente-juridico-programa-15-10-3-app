# Assistente Jurídico como programa do Windows (.exe)

Abre numa janela própria. Sem .bat, sem janela preta, sem navegador e sem instalar o Node.

## Como gerar (uma vez)
1. Mande esta pasta para um repositório no GitHub (Mini SK → 🐙 GitHub).
2. No GitHub: aba **Actions** → **Programa .exe para Windows** → **Run workflow**.
3. Espere uns 10 a 15 minutos. Antes de entregar, o GitHub liga o programa e confere se ele responde.
   - Verde ✔: abra a execução → **Artifacts** → baixe **Assistente-Juridico-Windows**.
   - Vermelho ✖: abra o passo vermelho e mande um print.

## No computador
Dentro do zip baixado vêm dois arquivos (use um só):
- **Assistente-Juridico-Instalar.exe**: instala e cria o ícone na área de trabalho. É o recomendado.
- **Assistente-Juridico-sem-instalar.exe**: abre direto, sem instalar (demora um pouco mais para abrir).

Se o Windows avisar "protegeu o computador": **Mais informações → Executar assim mesmo**.

## Seus dados
Ficam em **Documentos\Assistente-Juridico** (pasta *dados*). Para backup, copie essa pasta.
Chaves de IA: pode pôr um arquivo **.env** nessa mesma pasta (veja o .env.exemplo), ou usar as configurações do próprio app.
Se der erro, o motivo fica em **Documentos\Assistente-Juridico\registro.txt**. Mande esse arquivo.

## IA grátis no computador (Ollama)
Com o Ollama instalado e ligado (a lhama 🦙 perto do relógio), escreva **ollama** no lugar da chave da IA nas configurações do app.
Para outro modelo: **ollama:qwen2.5:3b** (o padrão é o phi4-mini, que fala português). A 1ª resposta demora 1 a 3 minutos.
