# PACOTE OFFICE OFICIAL

[Ferramenta de Personalização do Office](https://config.office.com/deploymentsettings).
A ferramenta cria os arquivos de configuração usados para implantar o Office em grandes organizações.

Os arquivos de configuração oferecem mais controle sobre uma instalação do Office: você pode definir quais aplicativos e idiomas estão instalados, como esses aplicativos devem ser atualizados e preferências do aplicativo. Depois de criar os arquivos de configuração, você pode usá-los com a [Ferramenta de Implantação do Office](https://www.microsoft.com/en-us/download/details.aspx?id=49117) para implantar uma versão personalizada do Office.


## 📚 Documentação
- [Ferramenta de Personalização do Office](https://config.office.com/deploymentsettings)
- [Ferramenta de implantação do Office](https://www.microsoft.com/en-us/download/details.aspx?id=49117)

## 💻 Instalação

1. Crie uma nova pasta no seu **Disco Local (C:)** e renomeie com o nome **MS OFFICE SETUP**.

2. Faça sua exportação da [personalização do Office](https://config.office.com/deploymentsettings), certifique-se de exportar no **Formato Office Open XML**.

> Arquvio: configuração.xml

3. Faça download da [ferramenta de implantação do Office](https://www.microsoft.com/en-us/download/details.aspx?id=49117).

> Arquivo: officedeploymenttool_17531-20046.exe

4. Certifique-se se possui os arquivos nécessarios e depois coloqueos dentro da pasta criada lá no **Disco Local (C:)**.

5. Execute o software **officedeploymenttool_17328-20162.exe**, aceite os termos depois selecione o caminho onde está a sua pasta criada.
**Este Computador** > **Disco Local (C:)** > **MS OFFICE SETUP**.

6. Abra o Prompt de Comando (CMD) como Administrador.

7. Digite os seguintes comandos:

```
cd\
```

```
cd c:\MS OFFICE SETUP
```

```
setup.exe /configure Configuração.xml
```

## 🔍 Referências
- [Microsoft Build](https://learn.microsoft.com/pt-br/deployoffice/admincenter/overview-office-customization-tool)
