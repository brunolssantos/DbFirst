# DbFirst

Projeto .NET (Database-First) contido neste repositório.

Descrição
- Exemplo/implementação de um projeto .NET que utiliza abordagem Database-First para mapear um banco de dados para modelos no código.

Requisitos
- Visual Studio 2022/2026 (ou equivalente) com suporte a .NET Framework.
- .NET Framework 4.8.1
- Acesso ao banco de dados usado pelo projeto (servidor SQL ou outro providenciado)

Como abrir e compilar
1. Abra a solução no Visual Studio (arquivo .sln).
2. Restaure os pacotes NuGet (Tools -> NuGet Package Manager -> Restore) se necessário.
3. Compile a solução (Build -> Build Solution).

Configurar a conexão com o banco de dados
- Atualize a cadeia de conexão no arquivo App.config (ou Web.config) para apontar para sua base de dados.
- A aplicação assume que as entidades e modelos foram gerados a partir do banco (Database-First). Se necessário, re-genere o modelo a partir do banco usando as ferramentas do Entity Framework ou o provedor usado no projeto.

Executando
- Execute a aplicação a partir do Visual Studio (F5 ou Debug -> Start Debugging) ou rode o executável gerado em bin/.

Contribuição
- Pull requests são bem-vindos. Para mudanças maiores, abra uma issue primeiro para discutir a proposta.

Licença
- Verifique se há um arquivo LICENSE neste repositório para detalhes sobre a licença. Se não houver, entre em contato com o mantenedor.

Contato
- Consulte o histórico do repositório para informações sobre o autor e remotes configurados.