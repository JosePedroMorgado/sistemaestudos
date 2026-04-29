Este é um sistema robusto de Gestão de Estudos e Engenharia de Dados, desenvolvido especificamente para concurseiros que precisam de alta performance e controle total sobre o seu tempo de estudo (HBC - Horas Bunda Cadeira) e desempenho em questões.

O sistema foi projetado para rodar localmente no navegador ou como um aplicativo executável (.exe), garantindo total privacidade e controle dos seus dados.

🚀 Principais Funcionalidades
📈 Painel Analítico (Dashboard)
Métricas em Tempo Real: Acompanhamento total de questões resolvidas, média de acertos e matérias acima da meta (>80%).

Monitoramento de Tempo: Cálculo automático do tempo total estudado (horas/minutos) e média de tempo por sessão.

Gráficos de Desempenho:

Gráfico de Linha: Evolução diária da sua porcentagem de acertos.

Gráfico de Barras: Comparativo visual de acertos e erros segmentado por matéria.

Filtros Dinâmicos: Possibilidade de filtrar todo o painel por uma matéria específica para análise micro.

📋 Gestão de Ciclos e Cadastro
Multi-Concursos: Cadastre e gerencie diferentes editais no mesmo sistema.

Matérias Dinâmicas: Adicione ou remova matérias e use a ferramenta de Adição em Massa para carregar editais inteiros em segundos.

Segurança Anti-Duplicação: O sistema impede o cadastro de registros idênticos (mesma data, matéria, assunto, etc.) para evitar poluição dos dados.

📥 Importação e Backup
Importação CSV Inteligente: Alimente o sistema via Excel. Se o concurso ou matéria não existir na sua base, o sistema os cria automaticamente.

Idempotência: Algoritmo que ignora linhas duplicadas durante a importação de planilhas.

Backup JSON: Exporte uma "fotografia" completa de todo o seu banco de dados para segurança ou para migrar de computador.

🛠️ Tecnologias Utilizadas
HTML5/CSS3: Estrutura moderna e responsiva.

JavaScript (Vanilla): Lógica de processamento de dados e algoritmos de filtragem.

Chart.js: Visualização de dados de alta performance.

LocalStorage: Persistência de dados no navegador (sem necessidade de banco de dados externo).

Electron: Empacotamento para aplicação desktop executável.

📂 Estrutura da Planilha de Importação (CSV)
Para importar dados do Excel, o arquivo deve ser salvo no formato CSV (UTF-8) com as seguintes colunas (8 colunas):

Concurso: Nome do edital (ex: SESDF).

Data: No formato DD/MM/AAAA.

Matéria: Nome da disciplina.

Assunto: Tópico específico estudado.

Ponto de Parada: Onde você parou na videoaula ou PDF.

Questões: Quantidade total de questões feitas.

Acertos: Quantidade de acertos.

Tempo_Minutos: Duração da sessão em minutos.

💻 Como Rodar o Projeto
Versão Web
Basta abrir o arquivo .html em qualquer navegador moderno (Chrome, Edge, Firefox).

O sistema salvará os dados automaticamente no seu computador.

Versão Desktop (Executável)
Se você seguiu o processo de empacotamento com Electron, basta:

Navegar até a pasta gerada NomeDoMeuApp-win32-x64.

Executar o arquivo NomeDoMeuApp.exe.

(Opcional) Criar um atalho na Área de Trabalho para acesso rápido.

⚠️ Avisos Importantes
Limpeza de Cache: Como os dados ficam no localStorage, limpar os dados de navegação do Chrome pode apagar seu histórico. Sempre faça backups periódicos em JSON.

Privacidade: Seus dados nunca saem do seu computador. Não há comunicação com servidores externos.

Desenvolvido para transformar horas de estudo em aprovação. 🎯
