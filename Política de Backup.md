# Política de Backup  
**Versão:** 1.0  
**Data:** 30/10/2025  
**Responsável:** Equipe de Infraestrutura e Segurança  

---

## 1. Objetivo
Definir diretrizes para **cópia, armazenamento, retenção e restauração de dados** essenciais aos negócios, assegurando a **disponibilidade e integridade da informação** em caso de falhas, incidentes ou desastres.

---

## 2. Escopo
Abrange todos os **sistemas, servidores, bancos de dados e arquivos críticos** sob responsabilidade da organização, tanto em ambiente local quanto em nuvem.

---

## 3. Diretrizes Gerais
1. Backups devem ser **executados automaticamente** e monitorados diariamente.  
2. Os dados críticos devem ter cópias **armazenadas em local físico e lógico distinto**.  
3. Todos os backups devem ser **criptografados** com algoritmos robustos (AES-256).  
4. Deve existir ao menos **três cópias** dos dados (regra 3-2-1):
   - 3 cópias dos dados;
   - 2 mídias diferentes;
   - 1 cópia fora do ambiente principal.  
5. O acesso aos backups deve ser **restrito e controlado**.

---

## 4. Retenção e Restauração
- Backups diários devem ser mantidos por **30 dias**.  
- Backups semanais por **3 meses**.  
- Backups mensais por **1 ano**.  
- Testes de restauração devem ser realizados **trimestralmente** para verificar a integridade dos dados.

---

## 5. Responsabilidades
- **Equipe de Infraestrutura:** realizar e monitorar os backups.  
- **Gestor de TI:** garantir que os planos e políticas estejam atualizados.  
- **Gestor de Segurança:** verificar a conformidade e participar dos testes de restauração.

---

## 6. Continuidade e Incidentes
- Em caso de incidente, os dados devem ser restaurados conforme o **Plano de Recuperação de Desastres (DRP)**.  
- O tempo máximo aceitável de restauração (**RTO**) e perda de dados (**RPO**) deve estar definido para cada sistema.

---

## 7. Auditoria e Conformidade
- Logs de backup e restauração devem ser **mantidos por 12 meses**.  
- Auditorias internas anuais devem avaliar o cumprimento desta política.

---

## 8. Referências
- ISO/IEC 27001:2022 – A.5.28 e A.8.13  
- ISO/IEC 22301 – Continuidade de Negócios  
- NIST SP 800-34 Rev.1 – Contingency Planning

---
