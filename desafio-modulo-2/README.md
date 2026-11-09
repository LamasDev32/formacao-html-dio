# Clínica VivaBem

Site estático de uma clínica médica fictícia, criado como desafio do Módulo 2 da trilha de HTML da DIO. O projeto demonstra estruturação de páginas com HTML e apresentação visual com CSS.

## Páginas

- **Página Principal** — apresentação da clínica e links para os serviços.
- **Sobre a clínica** — história, equipe e proposta de atendimento.
- **Horário de Atendimento** — tabela de horários por especialidade e dia.
- **Contato** — telefones, endereço, mapa do Google Maps e formulário demonstrativo.

## Tecnologias e recursos

- HTML semântico, com navegação entre páginas.
- CSS responsivo para telas menores.
- Tabela acessível com cabeçalhos de linha e coluna.
- Formulário com campos obrigatórios, validação básica do navegador e botão para limpar.
- Ilustrações SVG locais e mapa incorporado.

## Como visualizar

Abra `index.html` em um navegador. Para executar por um servidor local, inicie-o na pasta `desafio-modulo-2` e acesse a página inicial. Não é necessário instalar dependências nem realizar build.

## Estrutura

```text
desafio-modulo-2/
├── index.html
├── README.md
└── assets/
    ├── css/
    │   └── base.css
    ├── images/
    │   ├── contato.svg
    │   ├── horarios.svg
    │   ├── principal.svg
    │   └── sobre.svg
    └── pages/
        ├── contato.html
        ├── horarios.html
        └── sobre.html
```

## Observação sobre o formulário

O formulário é apenas demonstrativo. Para receber mensagens, configure um endereço de e-mail válido no atributo `action` ou integre um serviço de envio de formulários. Os dados fictícios de contato e localização também devem ser substituídos antes de qualquer uso real.
