# Atendente de IA para clínica de estética — Demo

Demonstração interativa de um **atendente virtual no estilo WhatsApp** para uma clínica de estética. Simula o atendimento automático que responde dúvidas e faz o **agendamento** do início ao fim.

## ▶️ Demo ao vivo
**https://lo1ro.github.io/atendente-ia-clinica-demo/**

Abra no celular e converse com o atendente — peça preços, procedimentos, endereço ou marque um horário.

## O que ele demonstra
- Conversa natural: saudação → dúvidas → agendamento → confirmação
- Reconhecimento de intenção: preços, procedimentos, endereço, horário de funcionamento, falar com humano
- Agendamento guiado: procedimento → dia → horário → nome → confirmação
- Interface no estilo WhatsApp, responsiva

## Personalização por URL
A mesma página vira a demo de qualquer negócio, sem hospedar nada novo — é só mudar o link:

```
https://lo1ro.github.io/atendente-ia-clinica-demo/?negocio=Fisiobeauty&cidade=Franca&nicho=estetica
```

| Parâmetro | O que faz | Valores |
|-----------|-----------|---------|
| `negocio` | Nome no cabeçalho, na abertura e nas respostas (use `+` no lugar de espaço) | texto livre |
| `cidade`  | Aparece na resposta de endereço | texto livre |
| `nicho`   | Troca serviços, preços e o fluxo guiado (agendamento, pedido, orçamento ou busca de imóvel) | `estetica` (padrão) · `odonto` · `salao` · `papelaria` · `informatica` · `imobiliaria` |
| `genero`  | Concordância do artigo: `a` = "da/na Clínica X" (padrão), `o` = "do/no Espaço X" | `a` · `o` |

Sem parâmetros, a demo mantém o comportamento genérico original (Bella Estética).

## Tecnologias
HTML, CSS e JavaScript puro — sem dependências, roda em qualquer navegador.

## Sobre
Feito por **João Vitor Rizzieri** (FiumariAI) — automações e atendentes de IA para pequenos negócios.
A versão de produção roda em **n8n + IA**; veja os outros repositórios do meu perfil.
