# Fluxograma — Sistema de Agendamento de Laboratórios (LabEscola)

Fluxograma do sistema de agendamento dos laboratórios e do auditório da escola (CEPK).

## Arquivos

- `fluxograma/fluxograma-sistema.png` — imagem do fluxograma
- `fluxograma/fluxograma-sistema.drawio` — arquivo editável do draw.io

## Como visualizar/editar no draw.io

1. Acesse https://app.diagrams.net
2. **File → Open From → Device** e selecione `fluxograma/fluxograma-sistema.drawio`
   (ou arraste o arquivo para a tela do draw.io)
3. O fluxograma abre editável, com símbolos corretos:
   - **Oval** = início/fim
   - **Retângulo** = processo
   - **Losango** = decisão
   - **Setas** = fluxo e caminhos (Sim/Não)

## Resumo do fluxo

Início → tela de login → validação de credenciais (loop de erro) → criar sessão → menu principal → decisão entre:

- **Novo agendamento:** preencher formulário → validar → conflito de horário? → salvar → mensagem de sucesso → menu
- **Ver reservas:** listar → filtrar por turno → selecionar → é o dono? → editar/excluir ou somente leitura → menu
- **Sair:** encerrar sessão → Fim

## Repositório do sistema completo

O código-fonte do sistema está em: https://github.com/izabellahonoratosantos-source/sistema-super-legal
