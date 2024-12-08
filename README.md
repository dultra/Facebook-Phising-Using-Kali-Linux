# Phishing do Facebook com SEToolkit

## Passos:

1. **Usei o SEToolkit**:
   - Executei o comando `sudo su` para obter permissões de root
   - Iniciei o SEToolkit com o comando `setoolkit`

2. **Escolhi as seguintes opções**:
   - Selecionei a opção `Social-Engineering Attacks`
   - Em seguida, escolhi `Website Attack Vectors`
   - Depois, escolhi `Credential Harvester Attack Method`
   - Por fim, selecionei `Site Cloner`

3. **Configurei o ataque**:
   - Usei o IP da minha VM Kali como o servidor
   - Insiri a URL para clonar: `http://www.facebook.com`

5. **Ataque ativo**:
   - O SEToolkit gerou um site clonado onde estava a exata pagina de login que me devolvia email e senha inseridos
