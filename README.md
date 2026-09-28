# Ficha de Remédios

Gerador de fichas de horário de medicação para **pessoas e animais**. Basta preencher os remédios e intruções dadas pelo profissional de saúde, o site calcula os dias e horários de cada dose e monta uma tabela pronta para imprimir, com boxes para marcar um **X** a cada dose dada.

Não há necessidade de instalar nada, roda direto no navegaor.

## Privacidade

**Arquivos são guardados localmente** no navegador (`localStorage`) de quem está usando. Limpar os dados do navegador ou usar outro computador faz a ficha ficar em branco. Caso queira guardar as configurações ou continuar o preenchimento em outra maquina utilize **Salvar arquivo** para guardar as fichas.

## Funcionalidades

**Paciente**
- Modo **pessoa** ou **animal**. No modo animal aparecem espécie/raça e tutor.
- **Logo da clínica** no cabeçalho - Caso queira utilizar na sua clinica para auxiliar tutores ou pacientes.

**Ficha impressa**
- Uma linha para cada horário de dose. Casinhas riscadas indicam quando não há dose.
- Primeira e última dose calculadas automaticamente.
- Quadro **"Horários do dia"** com todos os remédios agrupados por horário (opcional).
- Espaço para observações, reações e doses esquecidas (opcional).
- **Dá para marcar as doses clicando na tela, para quem utilizar no computador ou no celular.**

**Salvar e reaproveitar**
- A ficha é salva automaticamente no navegador. **Se limpar os dados de navegação os dados salvos serão perdidos**
- **Salvar arquivo** baixa a ficha em `.json`, e **Abrir arquivo** carrega de volta.
- **Nova ficha** apaga o paciente e os remédios, mas mantém a logo, os dados do profissional e as cores salvas.

## Como usar

1. Preencha os dados do paciente e a data de início.
2. Adicione os remédios com dose, frequência, horário da primeira dose e duração.
3. Para mudar a dose ou a frequência depois de alguns dias, use **"+ Mudar dose ou frequência depois"**.
4. Confira a prévia ao lado e clique em **Imprimir ficha**.

**Dicas de impressão**
- Use papel A4.
- Na janela de impressão, desmarque **"Cabeçalhos e rodapés"** para a ficha sair mais limpa.
- Se as cores ou as casinhas riscadas não aparecerem, ative **"Gráficos de plano de fundo"**.

## Estrutura

```
index.html   site completo (HTML, CSS e JavaScript)
README.md    este arquivo
```

A única dependência externa é a fonte [Atkinson Hyperlegible](https://fonts.google.com/specimen/Atkinson+Hyperlegible), carregada do Google Fonts. Caso esteja sem acesso a internet, o site vai usar a fonte padrão do sistema.

## Aviso

Esta ferramenta ajuda a organizar horários. Ela **não substitui a orientação do médico, do veterinário ou do farmacêutico**. Sempre confira a ficha com a receita antes de usar.
