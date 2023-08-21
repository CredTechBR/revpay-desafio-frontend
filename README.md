# revpay-desafio-frontend

Primeiramente, obrigado pelo seu interesse em trabalhar conosco.

## Avisos antes de começar

- Crie um repositório no seu GitHub **sem citar nada relacionado a RevPay**.
- Faça seus commits no seu repositório.
- Envie o link do seu repositório para o email: renan.almeida@revpay.com.br, carlos.eduardo@revpay.com.br ou felipemirandahoje@gmail.com
- Você poderá consultar o Google, Stackoverflow ou algum projeto particular na sua máquina.
- Fique à vontade para perguntar qualquer dúvida aos recrutadores.

*Corpo do Email com o link do repositório do desafio*

>Seu Nome
>
>Link do repositório

### Sobre o ambiente da aplicação:

Você pode utilizar Vite ou Next Js.

## Regras

Elaborar um formulário com as seguintes regras:

```
1 - Campos devem ser obrigatórios, porém apenas UM poderá ser opcional.
2 - Ao inserir um valor problemático, a validação deverá ser ativada.
3 - Campos deverão mostrar MASCARAS.
4 - Campos que possuem MASCARAS devem ser normalizados, ou seja, devem ser removidos antes de enviar para o backend.
5 - Permitir cadastro de pessoas maiores de 18 anos apenas.
```
Ao inserir CEP, preencher os campos ENDEREÇO, BAIRRO, e ESTADO por meio desta [API](https://viacep.com.br/).

### Requisitos

```
1 - Você poderá usar qualquer alternativa CSS (Chakra UI, Radix UI, Tailwind, SASS, etc).
2 - Projeto deverá usar React 18, TypeScript, React Query, React Hook Form e Zod.
```

### O que iremos avaliar:

Formulários em React podem gerar uma grande dor de cabeça se o código não for organizado, visto que podem crescer
rapidamente. Por isso, avaliaremos como você organizará o seu projeto.


### Entrada

Campo   | Possui mascara? | Validação (caracteres) | Saída
--------- | ------ | -------- | -----------
NOME COMPLETO | Não | Mínimo 1, Máximo 100 | fullname
CPF | Sim | Mínimo 11 | documentNumber
DATA DE NASCIMENTO | Sim | Mínimo 9 | birthdate
EMAIL | Não | Obrigatório | email
CEP | Sim | Mínimo 8 | zipcode
CONTATO | Sim | Mínimo 11 | phoneNumber
NÚMERO | Não | Mínimo 1, Máximo 40 | addressNumber
ESTADO | Não | Obrigatório, Máximo 2 | addressState
PAÍS | Não | Obrigatório | country
CIDADE | Não | Obrigatório | city
BAIRRO | Não | Obrigatório | district
RUA | Não | Obrigatório | street
ENDEREÇO  | Não | Obrigatório | address
COMPLEMENTO (Opcional)  | Não | Opcional | addressComplement
ESCOLARIDADE  | Não | Obrigatório | educationLevel
RENDA MENSAL | Sim | Obrigatório | minimumWage
SENHA  | Não | Minimo 10 | password
CONFIRMAR SENHA | Não | Minimo 10 | confirmPassword

### Saída

Ao clicar quem cadastrar, o resultado deverá ser mostrado por meio de um Alert.

[Window: alert() method](https://developer.mozilla.org/en-US/docs/Web/API/Window/alert)

```
fullname: string
documentNumber: string
birthdate: string
email: string
zipcode: string
phoneNumber: string
addressNumber: string
country: string
city: string
addressDistrict: string
addressComplement: string | null
street: string
educationLevel: string
minimumWage: number
password: string
```
### FIGMA

Está disponível por meio deste [link](https://www.figma.com/file/vETB61Hj0vmkCyEI9DpxjC/Teste-RevPay---Frontend?type=design&node-id=0%3A1&mode=design&t=HvhsfPlv5Q42Qoes-1)

![image](https://github.com/CredTechBR/revpay-desafio-frontend/assets/91689754/67a246a4-5870-45b7-a4aa-fdfacb78c63d)

Tente replicar o máximo possível.
