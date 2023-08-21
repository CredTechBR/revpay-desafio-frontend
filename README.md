# revpay-desafio-frontend

## Regras

Elaborar um formulário com as seguintes regras:

```
1 - Campos devem ser obrigatórios, porém apenas UM poderá ser opcional.
2 - Ao inserir um valor problemático, a validação deverá ser ativada.
3 - Campos deverão mostrar MASCARAS.
4 - Campos que possuem MASCARAS devem ser normalizados, ou seja, devem ser removidos antes de enviar para o backend.
5 - Permitir cadastro de pessoas maiores de 18 anos apenas.
```

### Requisitos

```
1 - Você poderá usar qualquer alternativa CSS (Chakra UI, Radix UI, Tailwind, SASS, etc).
2 - Projeto deverá usar React 18, TypeScript, React Query, React Hook Form e Zod.
```

### O que iremos avaliar:

Formulários em React podem gerar uma grande dor de cabeça se o código não for organizado, visto que podem crescer
rapidamente. Por isso, avaliaremos como você organizará o seu projeto.


### Entrada

Campo   | Possui mascara? | Validação (caracteres)
--------- | ------ | --------
NOME COMPLETO | Não | Mínimo 1, Máximo 100
CPF | Sim | Mínimo 11
DATA DE NASCIMENTO | Sim | Mínimo 9
EMAIL | Não | Obrigatório
CEP | Sim | Mínimo 8
CONTATO | Sim | Mínimo 11
NÚMERO | Não | Mínimo 1, Máximo 40
ESTADO | Não | Obrigatório, Máximo 2
PAÍS | Não | Obrigatório
CIDADE | Não | Obrigatório
RUA | Não | Obrigatório
ENDEREÇO  | Não | Obrigatório
COMPLEMENTO (Opcional)  | Não | Opcional
ESCOLARIDADE  | Não | Obrigatório
RENDA MENSAL | Sim | Obrigatório
SENHA  | Não | Minimo 10
CONFIRMAR SENHA | Não | Minimo 10

### Saída

```
fullname: string
documentNumber: string
birthdate: string
email: string
zipcode: string
phoneNumber: string
addressNumber: number
country: string
city: string
addressComplement: string | null
street: string
educationLevel: string
minimumWage: number
password: string
```
### FIGMA

![image](https://github.com/CredTechBR/revpay-desafio-frontend/assets/91689754/67a246a4-5870-45b7-a4aa-fdfacb78c63d)

Tente replicar o máximo possível.

<https://www.figma.com/file/vETB61Hj0vmkCyEI9DpxjC/Teste-RevPay---Frontend?type=design&node-id=0%3A1&mode=design&t=HvhsfPlv5Q42Qoes-1>
