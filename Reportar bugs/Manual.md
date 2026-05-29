# 🐞 Manual de Reporte de Bugs

## Objetivo
Este manual tem como objetivo padronizar o processo de reporte de bugs, facilitando a identificação, reprodução e correção de problemas encontrados no sistema.

## 📋 Antes de Reportar um Bug
Antes de abrir um bug, verifique:

- Se o problema já foi reportado anteriormente;
- Se o erro realmente pode ser reproduzido;
- Se está utilizando a versão mais recente da aplicação;
- Se há evidências suficientes para análise.

## ✅ Informações Obrigatórias no Report

Todo report de bug deve conter as seguintes informações:

**1. Título do Bug**
- O título deve ser claro e objetivo.

        Exemplo: [LOGIN] Usuário não consegue acessar o sistema com credenciais válidas

**2. Pré-condição**
- Descrever o cenário necessário antes da execução do teste.

         Exemplo:
         Dado que o usuário esteja cadastrado no sistema
         E possua credenciais válidas

**3. Passos para Reproduzir**
- Descrever o passo a passo detalhado.

        Exemplo:
        1. Acessar a tela de login;
        2. Informar usuário e senha válidos;
        3. Clicar no botão "Entrar".

 **4. Resultado atual**
 - Descrever o comportamento incorreto apresentado.

        Exemplo: O sistema exibe mensagem de erro "Falha na autenticação".


 **5. Resultado esperado**
- Descrever o comportamento correto esperado.

        Exemplo: O sistema deve realizar o login e redirecionar o usuário para a página inicial.

 
 **6. Evidências**
- Adicionar evidências sempre que possível:

  - Prints;
  - Vídeos;
  - Logs;
  - Console do navegador;
  - Arquivos anexos.

 **7. Ambiente**
- Informar onde o bug ocorreu.
  
        Exemplo
        Ambiente: Homologação
        Sistema Operacional: Windows 11
        Navegador: Google Chrome
        Dispositivo: Desktop
  
 **8. Severidade**
- Classificação do impacto do bug.

| Severidade | Descrição |
|------------|------------|
| Crítica | Sistema indisponível ou perda de dados |
| Alta | Funcionalidade principal comprometida |
| Média | Funcionalidade com impacto parcial |
| Baixa | Problema visual ou baixo impacto |


 **9. Prioridade**
- Classificação da urgência da correção.

| Prioridade | Descrição |
|------------|------------|
| Alta | Correção imediata |
| Média | Correção planejada |
| Baixa | Pode aguardar |

## 🚫 O que Evitar
- Reports sem evidências;
- Títulos genéricos;
- Passos incompletos;
- Bugs sem reprodução;
- Informações vagas.

## 💡 Boas Práticas
- Seja objetivo;
- Utilize linguagem clara;
- Inclua detalhes técnicos relevantes;
- Anexe evidências sempre que possível;
- Teste novamente antes de abrir o bug.

## 📌 Observação
Um bug bem documentado reduz o tempo de análise e acelera o processo de correção pela equipe de desenvolvimento.
