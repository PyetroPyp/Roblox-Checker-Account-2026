Um verificador de contas Roblox que testa automaticamente combinações de usuário/senha e coleta informações das contas válidas.

⚙️ Como Funciona (Simples)
Você fornece uma lista de combinações usuário:senha

O programa tenta fazer login automaticamente no Roblox

Se conseguir entrar, ele coleta:

Quantidade de Robux na conta

Se é conta Premium (assinatura paga)

Cookies de sessão

Salva as contas válidas em arquivos separados

Mostra estatísticas do que encontrou

📁 Arquivos Necessários
1. contas.txt (OBRIGATÓRIO)
text
usuario1:senha123
usuario2:outrasenha
gamer:password123
2. proxies.txt (OPCIONAL - ajuda a evitar bloqueios)
text
http://proxy1.com:8080
socks5://proxy2.com:1080
http://usuario:senha@proxy3.com:3128
🚀 Como Executar
Método 1: Interface Gráfica (Recomendado)
bash
python zezo_checker.py
# Escolha opção 1
Método 2: Linha de Comando
bash
python zezo_checker.py
# Escolha opção 2
📊 Resultados Gerados
As contas válidas são salvas em:

HITS.txt - Todas as contas funcionando

HITS_PREMIUM.txt - Apenas contas Premium

HITS_COOKIES.txt - Com sessões salvas

⚠️ Aviso Importante
Use apenas para:

Verificar SUAS contas esquecidas

Testes educacionais

Recuperação de contas próprias

NÃO USE para:

Tentar acessar contas alheias

Atividades ilegais

Violar termos do Roblox

🛡️ Proteções Incluídas
O checker tem:

Delays entre tentativas (evita bloqueio)

Suporte a proxies (rotação de IP)

Modo stealth (evita detecção)

Controles de pausa/retomar

Requisições: Python 3.7+, Google Chrome, Conexão com internet

Desenvolvido: 2026 | Versão: 6.2 Completa
