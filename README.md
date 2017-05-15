# Este modelo serve para Atas ou Memorandos.

## Variáveis comuns a memorandos e atas. `type: Memorando ou ATA`
* O cabeçalho é colocado conforme a definição da variável `type`
```latex
% \type{ATA}
\type{Memorando}
```
## A variável `sender` foi definida pois tanto atas, quanto memorandos podem ser emitidos pela Coordenação de Curso ou pelo Departamento.
```latex
% sender: Curso de Bacharelado em Ciência da Computação ou Departamento Acadêmico de Computação
\sender{Curso de Bacharelado em Ciência da Computação}{COCIC}
% \sender{Departamento Acadêmico de Computação}{DACOM}
```
## Número e data são comuns aos dois modelos.
```latex
\serial{02/2017}
\data{8 de março de 2017}
```
## Título é específico para Ata. Se não for uma ata não defina.
```latex
\titulo{Ata da Reunião Ordinária do Colegiado do Curso de Bacharelado em Ciência da Computação}
```
## Específicas para Memorando.
```latex
\para{Nome do Destinatário (Depto)}
\depto{Nome do Departamento (SIGLA)}
\assunto{Assunto do Memorando}
```
## Seu texto deve substituir o `\lipsum[3-15`
```latex
% Escreva seu Texto Aqui.
\lipsum[3-15]
```
## Para Memorando foi definida uma variável de saudação: "Respeitosamente" ou "Atenciosamente" ou "Cordialmente".
\greetings{Respeitosamente}

## Definição das Assinaturas
```latex
% Signatures
\doublesignature{Nome do Professor}{Cargo}{Nome do Professor}{Cargo}

% Assinatura
\signature{Nome do Professor}{Cargo}
```
