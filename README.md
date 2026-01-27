WIN CONTROL PANEL

WIN CONTROL PANEL é uma ferramenta de automação e otimização de sistema desenvolvida em PowerShell com uma interface gráfica baseada em Windows Forms. O objetivo principal é centralizar tarefas de manutenção, privacidade e desempenho em um único painel intuitivo, eliminando a necessidade de navegar por múltiplos menus do Windows.
🚀 Funcionalidades
🧹 Limpeza de Sistema

    Arquivos Temporários: Limpeza profunda das pastas %TEMP% e C:\Windows\Temp.

    Prefetch: Exclusão de dados de cache do Windows para resolução de conflitos.

    Lixeira: Esvaziamento automatizado de todos os drives.

⚡ Gestão de Energia (MAXPOWER)

    Plano de Desempenho Máximo: Criação e ativação automática de um plano de energia otimizado baseado no Ultimate Performance ou High Performance.

    Otimização de Processador: Força o estado do processador em 100% para evitar latência.

    Hibernação e Suspensão: Desativação automática do modo de hibernação e timeouts de monitor para uso ininterrupto.

🛡️ Privacidade e Telemetria

    Controle de Telemetria: Habilitação ou desabilitação de serviços de coleta de dados (DiagTrack, dmwappushservice, etc.).

    Status em Tempo Real: Verificação instantânea do estado da telemetria via Registro do Windows.

📦 Atualização de Software

    Integração Winget: Atualização em massa de todos os aplicativos instalados através do Windows Package Manager.

    Processamento Assíncrono: Execução em background com barra de progresso visual (Marquee) para não travar a interface.

🛠️ Detalhes Técnicos

    Linguagem: PowerShell 5.1+.

    UI Framework: System.Windows.Forms & System.Drawing.

    Segurança: Script com auto-elevação para privilégios de Administrador.

    Personalização: Suporte a Dark Mode e Light Mode em tempo real.

    Logs: Sistema de log vivo para monitoramento de todas as ações executadas.

📋 Pré-requisitos

    Execução de scripts habilitada (Set-ExecutionPolicy RemoteSigned).

    Windows 10 ou 11.

    Gerenciador de Pacotes Winget (para a função de update).

    Desenvolvido por: Rigo
