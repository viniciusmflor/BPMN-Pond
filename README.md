# BPMN-Pond
Atividade Modelagem de Processos

# Modelagem BPMN - Processo Mercado Livre

## Descrição
Modelagem do fluxo de compra, pagamento e entrega de produtos no Mercado Livre, incluindo verificação de conformidade e possíveis devoluções.

## Diagrama

[Início] → [Compra] → [Pagamento (PayPal/Mercado Pago)] → [Processamento]
↓
[Preparação] → [Postagem] → [Entrega] → [Verificação]
↓
[Conforme?] → Sim → [Qualificação positiva] → [Pagamento liberado] → [Fim]
→ Não → [Negociação] → [Resolver/Devolver?]
↓            ↓
Resolver      Devolver
↓            ↓
[Qualificação]  [Reembolso] → [Fim]

## Participantes
- **Cliente**: Compra, paga, verifica, qualifica
- **Mercado Livre**: Processa, libera pagamento/reembolso
- **Vendedor**: Prepara, envia, negocia
- **Pagamento**: PayPal/Mercado Pago
- **Correios**: Entrega produto/devolução

## Fluxos
1. **Normal**: Compra → Pagamento → Envio → Verificação conforme → Pagamento liberado
2. **Problema resolvido**: Verificação não-conforme → Negociação → Resolução → Pagamento liberado
3. **Devolução**: Verificação não-conforme → Devolução → Reembolso

## Observação

Não fiz representação visual no software porque utilizo MacOS e não consegui utilizar o software indicado. 
