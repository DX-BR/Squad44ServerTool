# Squad44 Server Tool - Wiki de Uso

## 📋 Índice
- [Visão Geral](#visão-geral)
- [Instalação](#instalação)
- [Interface Principal](#interface-principal)
- [Aba Servidor](#aba-servidor)
- [Aba Arquivos](#aba-arquivos)
- [Aba Mods](#aba-mods)
- [Aba Configurações](#aba-configurações)
- [Idiomas Suportados](#idiomas-suportados)
- [Verificação de Atualizações](#verificação-de-atualizações)
- [Solução de Problemas](#solução-de-problemas)

## 🎯 Visão Geral

O Squad44 Server Tool é uma aplicação completa para gerenciar servidores dedicados do Squad 44. Com interface intuitiva e suporte a múltiplos idiomas, permite controlar todos os aspectos do seu servidor de forma simples e eficiente.

### Principais Funcionalidades
- ✅ Controle completo do servidor (iniciar, parar, reiniciar)
- ✅ Agendamento automático de reinicializações
- ✅ Gerenciamento de mods via Steam Workshop
- ✅ Instalação e atualização automática via SteamCMD
- ✅ Interface em português, inglês e espanhol
- ✅ Verificação automática de atualizações
- ✅ Console integrado para monitoramento

## 🚀 Instalação

### Requisitos do Sistema
- Windows 10/11 (64-bit)
- .NET 8.0 Runtime
- Conexão com a internet
- Pelo menos 2GB de espaço livre em disco

### Passos de Instalação
1. Baixe a versão mais recente na página de [Releases](https://github.com/DX-BR/Squad44ServerTool/releases)
2. Extraia o arquivo ZIP em uma pasta de sua escolha
3. Execute `Squad44ServerTool.exe` como administrador
4. A aplicação criará automaticamente as pastas necessárias

## 🖥️ Interface Principal

A interface é dividida em 4 abas principais:

### Menu Superior
- **Arquivo**: Limpar dados salvos e sair da aplicação
- **Ajuda**: Informações sobre o programa e verificação de atualizações

### Barra de Status
- Mostra a versão atual da aplicação
- Indica o status da conexão com a internet

## 🎮 Aba Servidor

![Aba Servidor](docs/images/server-tab.png)

### Controles Principais
- **Iniciar**: Inicia o servidor dedicado
- **Parar**: Para o servidor em execução
- **Reiniciar**: Reinicia o servidor (para + iniciar)

### Opções de Configuração
- **Atualizar servidor ao iniciar**: Verifica atualizações antes de iniciar
- **Auto-reiniciar**: Habilita agendamento automático de reinicializações

### Configurações do Servidor
- **ServerName**: Nome que aparecerá na lista de servidores
- **MaxPlayers**: Número máximo de jogadores (padrão: 100)
- **NumReservedSlots**: Slots reservados para admins
- **ShouldAdvertise**: Torna o servidor visível publicamente

### Parâmetros de Inicialização
- **Port**: Porta principal do servidor (padrão: 7780)
- **QueryPort**: Porta para consultas (padrão: 27165)
- **FIXEDMAXTICKRATE**: Taxa de atualização do servidor
- **RANDOM**: Configuração de aleatoriedade
- **-log**: Habilita logs detalhados

### Agendamento de Reinicializações

![Agendamento](docs/images/schedule.png)

1. Marque **Auto-reiniciar**
2. Selecione a hora desejada (formato 24h)
3. Clique em **Agendar Reinício**
4. O contador mostrará o tempo restante até o próximo reinício

**Dicas:**
- Você pode agendar múltiplos horários
- Use **Remover Selecionado** para excluir um horário específico
- Use **Limpar Todos** para remover todos os agendamentos

## 📁 Aba Arquivos

![Aba Arquivos](docs/images/files-tab.png)

### SteamCMD e Instalação do Servidor

#### Primeira Configuração
1. Clique em **Baixar SteamCMD** (necessário apenas uma vez)
2. Aguarde o download e instalação automática
3. Clique em **Instalar/Atualizar Servidor**
4. O processo pode demorar 10-30 minutos dependendo da conexão

#### Atualizações Regulares
- Use **Instalar/Atualizar Servidor** para manter o servidor atualizado
- O processo verifica automaticamente por atualizações
- Use **Parar Tarefa** se precisar cancelar uma operação

#### Limpeza e Manutenção
- **Deletar SteamCMD**: Remove o SteamCMD (será necessário baixar novamente)
- **Deletar Servidor**: Remove completamente os arquivos do servidor
- **Deletar Mods**: Remove todos os mods instalados

### Console de Monitoramento
O console mostra em tempo real:
- Status das operações
- Progresso de downloads
- Mensagens de erro
- Logs do servidor

## 🔧 Aba Mods

![Aba Mods](docs/images/mods-tab.png)

### Gerenciamento de Mods

#### Adicionando Mods
1. Clique em **Adicionar Mod**
2. Digite o ID do mod do Steam Workshop
3. O mod aparecerá na lista com status "Não instalado"

#### Instalando Mods
1. Selecione os mods desejados na lista
2. Clique em **Instalar Mods**
3. Aguarde o download e instalação

#### Removendo Mods
- **Remover Selecionado**: Remove o mod selecionado da lista
- Para desinstalar: use **Deletar Mods** na aba Arquivos

### Status dos Mods
- **Instalado**: Mod baixado e pronto para uso
- **Não instalado**: Mod na lista mas não baixado

**Dica**: Encontre IDs de mods na URL do Steam Workshop
- Exemplo: `https://steamcommunity.com/sharedfiles/filedetails/?id=123456789`
- O ID é: `123456789`

## ⚙️ Aba Configurações

![Aba Configurações](docs/images/settings-tab.png)

### Tema da Interface
- **Claro**: Interface com cores claras
- **Escuro**: Interface com cores escuras (padrão)

### Idioma
- **Português (Brasil)**: Idioma padrão
- **English (US)**: Interface em inglês
- **Español (ES)**: Interface em espanhol

**Nota**: Use **Recarregar Idiomas** se adicionar novos arquivos de tradução

### Comportamento
- **Iniciar com o Windows**: Inicia automaticamente com o sistema
- **Minimizar para a bandeja**: Minimiza para a área de notificação

### Recursos
- **Documentação**: Abre este guia
- **Discord**: Acesso ao servidor de suporte
- **GitHub**: Repositório oficial do projeto

## 🌍 Idiomas Suportados

### Idiomas Disponíveis
- 🇧🇷 **Português (Brasil)** - Completo
- 🇺🇸 **English (US)** - Completo  
- 🇪🇸 **Español (ES)** - Completo

### Alterando o Idioma
1. Vá para **Configurações** > **Idioma**
2. Selecione o idioma desejado
3. A interface será atualizada automaticamente

### Arquivos de Idioma
Os arquivos de tradução ficam em `languages/`:
- `pt-BR.json` - Português
- `en-US.json` - Inglês
- `es-ES.json` - Espanhol

## 🔄 Verificação de Atualizações

### Verificação Manual
1. Vá para **Ajuda** > **Buscar Atualização**
2. O sistema verificará a versão mais recente no GitHub
3. Se houver atualização, abrirá a página de download

### Processo de Atualização
1. Baixe a nova versão da página de releases
2. Feche a aplicação atual
3. Substitua os arquivos pela nova versão
4. Seus dados e configurações serão preservados

**Importante**: O sistema não baixa atualizações automaticamente por segurança

## 🛠️ Solução de Problemas

### Problemas Comuns

#### "Erro de conexão com a internet"
- Verifique sua conexão
- Desative temporariamente antivírus/firewall
- Execute como administrador

#### "SteamCMD não encontrado"
- Use **Baixar SteamCMD** na aba Arquivos
- Verifique se não foi bloqueado pelo antivírus
- Execute como administrador

#### "Servidor não inicia"
- Verifique se as portas estão livres
- Confirme se o servidor foi instalado completamente
- Verifique os logs no console

#### "Mods não carregam"
- Certifique-se que os mods estão instalados
- Verifique se os IDs estão corretos
- Reinstale os mods se necessário

### Logs e Diagnóstico
- Console integrado mostra informações em tempo real
- Arquivos de log ficam na pasta do servidor
- Use **Limpar Dados** para reset completo (cuidado!)

### Suporte
- 💬 **Discord**: Suporte da comunidade
- 🐛 **GitHub Issues**: Reportar bugs
- 📧 **Email**: Contato direto com desenvolvedores

## 📝 Dicas Avançadas

### Otimização de Performance
- Use SSD para melhor performance
- Configure FIXEDMAXTICKRATE baseado no hardware
- Monitore uso de CPU e RAM

### Backup e Segurança
- Faça backup regular das configurações
- Mantenha o servidor sempre atualizado
- Use senhas fortes para acesso admin

### Automação
- Configure reinicializações automáticas
- Use scripts personalizados se necessário
- Monitore logs regularmente

---

## 📞 Contato e Suporte

- **GitHub**: [Squad44ServerTool](https://github.com/DX-BR/Squad44ServerTool)
- **Discord**: [Squad44ServerTool](https://discord.gg/Mz5FHTUPgn)
- **Documentação**: Este arquivo sempre atualizado

**Versão da Wiki**: 1.0  
**Última atualização**: Janeiro 2025

---

*Este guia é mantido pela comunidade. Contribuições são bem-vindas!*