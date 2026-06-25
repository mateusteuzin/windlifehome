- [x] Entender onde está a lógica atual de check-in/check-out/noites em script.js
- [x] Apagar/neutralizar toda lógica antiga conflitante desses 3 campos (sem tocar outras partes)
- [x] Implementar UMA função central updateDates(trigger) com as regras especificadas
- [x] Garantir inicialização do estado: check-in=hoje, noites=7, check-out=check-in+7
- [x] Garantir que '+'/'−' recalculam check-in a partir de check-out e noites nunca < 1
- [x] Garantir que mudança manual de check-out recalcula noites e ignora check-out<=check-in
- [x] Garantir updateTotals/WhatsApp usa NOITES recalculado
- [ ] Rodar testes manuais (passos obrigatórios) e registrar resultados
- [x] Validar que não existe mais de uma função mexendo em check-in/check-out/noites


