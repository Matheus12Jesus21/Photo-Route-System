# Photo-Route-System
## Descrição
Este é um projeto de minha própria autoria, utilizando auxilio da IA Gemini e as ferramentas do Notebook LM, na intenção de produzir um sistema multiagentes focado em facilitar o dia a dia de entregadores de todos os nichos.

# 📦 Photo-Route | Sistema Logístico Baseado em Agentes de IA

Solução inteligente de otimização de rotas de entrega ("Última Milha / Last Mile") desenvolvida para o contexto logístico brasileiro. O sistema transforma imagens brutas de etiquetas de pacotes em rotas geocodificadas e otimizadas através de uma arquitetura baseada em Agentes de IA e Visão Computacional.

---

## 🎯 Objetivo & Problema Resolvido

Reduzir o tempo manual de digitação e planejamento de rotas de entregadores autônomos, tratando desafios comuns do mercado brasileiro (etiquetas danificadas, abreviações informais e formatação de endereços inconsistente).

---

## 🏗️ Arquitetura do Sistema

O pipeline é orquestrado por agentes especializados:

```text
[ Câmera / Imagem ]
       │
       ▼
[ Agente de Visão ] ──(OCR)──► [ Agente Parser ] ──(Tratamento)──► [ Agente Roteador ]
(Extrai texto bruto)           (Padroniza endereço BR)           (Geocodifica & Otimiza)
