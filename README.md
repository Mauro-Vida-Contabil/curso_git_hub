# Título Principal

Este é um exemplo de documento escrito em **Markdown**.

Markdown é uma linguagem simples de formatação de texto. Ela permite criar títulos, listas, tabelas, links, destaques e outros elementos usando apenas caracteres comuns do teclado.

---

## 1. Título de Segundo Nível

Você pode organizar o documento utilizando vários níveis de títulos.

### 1.1 Título de Terceiro Nível

#### 1.1.1 Título de Quarto Nível

##### Título de Quinto Nível

###### Título de Sexto Nível

---

## 2. Formatação de Texto

Texto normal.

**Texto em negrito**

*Texto em itálico*

***Texto em negrito e itálico***

~~Texto riscado~~

Você também pode destacar uma palavra ou comando usando `código em linha`.

---

## 3. Parágrafos

Este é o primeiro parágrafo do documento.

Este é um segundo parágrafo. Para criar um novo parágrafo, normalmente deixamos uma linha em branco entre os textos.

---

## 4. Lista com Marcadores

* Contabilidade
* Fiscal
* Departamento Pessoal
* Financeiro
* Consultoria

Também é possível criar subitens:

* Contabilidade

  * Escrituração contábil
  * Balancete
  * Balanço Patrimonial
* Fiscal

  * Apuração de tributos
  * Obrigações acessórias

---

## 5. Lista Numerada

1. Receber os documentos
2. Conferir os documentos
3. Realizar a escrituração
4. Apurar os tributos
5. Emitir as guias
6. Enviar ao cliente

Também podemos criar níveis:

1. Receber documentos

   1. Documentos fiscais
   2. Documentos contábeis
   3. Documentos financeiros
2. Conferir documentos
3. Processar informações

---

## 6. Lista de Tarefas

* [x] Criar o projeto
* [x] Configurar o ambiente
* [ ] Criar o banco de dados
* [ ] Realizar os testes
* [ ] Publicar a aplicação

Esse tipo de lista é muito utilizado em projetos de software.

---

## 7. Citação

> Este é um exemplo de citação em Markdown.
>
> O símbolo `>` é utilizado no início da linha.

Também pode ser utilizado para destacar uma observação importante:

> **Observação:** Antes de realizar qualquer alteração no sistema, faça uma cópia de segurança.

---

## 8. Links

Você pode criar um link desta forma:

[Site da ICONTE](https://iconte.com.br)

Outro exemplo:

[GitHub](https://github.com)

---

## 9. Imagens

A estrutura para inserir uma imagem é:

```markdown
![Descrição da imagem](endereco-da-imagem.png)
```

Exemplo:

```markdown
![Logotipo da empresa](logo.png)
```

---

## 10. Tabela

| Serviço              | Responsável | Situação     |
| -------------------- | ----------- | ------------ |
| Contabilidade        | João        | Concluído    |
| Fiscal               | Maria       | Em andamento |
| Financeiro           | Carlos      | Pendente     |
| Departamento Pessoal | Ana         | Concluído    |

---

## 11. Linha Horizontal

Uma linha horizontal pode ser criada com três hífens:

---

Ela é útil para separar partes do documento.

---

## 12. Código em Linha

Para destacar pequenos comandos, podemos usar crases:

Use o comando `git status` para verificar a situação do repositório.

Outro exemplo:

Execute `docker compose up -d`.

---

## 13. Bloco de Código

Para apresentar várias linhas de código:

```python
def calcular_total(valor1, valor2):
    total = valor1 + valor2
    return total

resultado = calcular_total(100, 200)

print(resultado)
```

Também podemos identificar a linguagem utilizada.

### Exemplo em JavaScript

```javascript
function somar(a, b) {
    return a + b;
}

console.log(somar(10, 20));
```

### Exemplo de comando de terminal

```bash
git status
git add .
git commit -m "Primeiro commit"
git push
```

---

## 14. Destaques

### Importante

**ATENÇÃO:** Verifique os dados antes de continuar.

### Informação

> ℹ️ Este é apenas um exemplo didático.

### Alerta

> ⚠️ Não utilize dados reais de clientes em ambientes de teste.

---

## 15. Estrutura de um Projeto

Um documento Markdown pode ser usado para documentar um projeto.

### Objetivo

Criar uma aplicação para análise tributária.

### Escopo

A aplicação deverá comparar:

* Simples Nacional;
* Lucro Presumido;
* Lucro Real.

### Entradas

O sistema poderá receber:

* Arquivos Excel;
* Arquivos PDF;
* Dados digitados manualmente.

### Saídas

O sistema deverá apresentar:

1. Tributos calculados;
2. Carga tributária;
3. Comparação entre regimes;
4. Relatório final.

---

## 16. Exemplo de Documentação de Projeto

# Projeto de Planejamento Tributário

## 1. Brainstorm

Nesta fase são discutidas as ideias iniciais do projeto.

### Problema

Empresas possuem dificuldade para identificar qual regime tributário apresenta menor carga tributária.

### Ideia

Criar uma aplicação capaz de comparar diferentes regimes tributários.

---

## 2. Define

Nesta fase são definidos os requisitos.

### Requisitos

* Importar dados financeiros;
* Calcular tributos;

