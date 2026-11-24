# Simulador de Jornada 5x2

Ferramenta de apoio ao planejamento de jornadas após a **Emenda Constitucional nº 141/2026** (fim da escala 6x1): **42h semanais a partir de 16/12/2026** e **40h semanais a partir de 16/12/2027**, com dois dias de repouso por semana.

> **Aviso:** a ferramenta é um apoio de planejamento, não um parecer jurídico, e é fornecida sem garantia. Cada empresa é responsável pela conferência e pela decisão final. Antes de implantar qualquer escala, confirme com o Jurídico e o sindicato e confira a convenção coletiva aplicável.

## O que a ferramenta faz

- **Simula opções** de novas escalas (5x2) e **confere jornadas** já definidas.
- Trabalha com jornada igual toda semana, semanas alternadas, 12x36 e revezamento (teste).
- Compara a jornada com os limites de 42h e 40h e aponta alertas e situações que dependem de convenção ou acordo coletivo.
- Mostra a escala do mês, a média semanal, as folgas e, na 12x36, o mínimo de folgas do mês e o excedente sobre os limites.
- Calcula o novo **salário-hora** (divisor 210 para 42h e 200 para 40h) mantendo o salário mensal.
- Gera **Imprimir / PDF** e **Copiar resumo**.

## Como usar

Abra o arquivo `index.html` no navegador (ou acesse o endereço publicado) e siga os passos da tela:

1. Escolha o uso: simular opções ou conferir uma jornada.
2. Diga como é a jornada e informe os horários.
3. Escolha o limite (42h, 40h ou comparar) e clique em **Calcular**.
4. Leia as opções, os alertas e as folgas, e compartilhe pelo PDF ou pelo resumo.

Não precisa instalar nada: é um único arquivo HTML. Nenhum dado digitado é enviado a servidor; tudo fica apenas no navegador de quem usa.

## Base legal

Emenda Constitucional nº 141/2026, Decreto nº 13.173/2026, Portaria MTE nº 2.041/2026, CLT, Lei nº 605/1949, Lei nº 10.101/2000 e Portaria MTP nº 671/2021. A lista completa está no fim da ferramenta, em "Legislação de referência".

## Limitações

- Não verifica as regras de domingos e feriados (comércio, mulheres); elas aparecem como orientação.
- Não decide sobre atividades insalubres, regimes especiais ou jornadas definidas em norma coletiva.
- A decisão liminar do STF de 12/11/2026 ainda depende do plenário e não foi aplicada.
- Na 12x36, as horas noturnas entram na hora reduzida de 52min30s; confirme com o Jurídico se ela entra na média do limite semanal.

## Estrutura do projeto

```
index.html   → a ferramenta completa (HTML, CSS e JavaScript em um só arquivo)
README.md    → este arquivo
```

## Atualizações

Quando houver mudança na legislação, o `index.html` é substituído pela nova versão e publicado novamente.
