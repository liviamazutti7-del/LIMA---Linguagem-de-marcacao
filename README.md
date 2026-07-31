# LIMA---Linguagem-de-marcacao
# 📘 Exercícios Práticos de XML

## 🎯 Objetivo
O objetivo destes exercícios é **desenvolver a habilidade de identificar e corrigir erros de sintaxe em documentos XML**, aplicando boas práticas de escrita e validação.

---

## 📂 Exercícios

### Exercício 1 – Cadastro de Livro
- **Erro:** Tag `<titulo>` não fechada.
- **Correção:**

<livro>
  <titulo>Banco de Dados</titulo>
  <autor>Maria Oliveira</autor>
  <ano>2025</ano>
</livro>


### Exercício 2 – cadastro de aluno
- **Erro:** Atributos devem estar entre aspas. <idade=20></idade> está incorreto, o valor deve estar dentro da tag.
- **Correção:**
<?xml version="1.0" encoding="UTF-8"?>

<aluno matricula="202501" curso="Informática">
  <nome>João Silva</nome>
  <idade>20</idade>
</aluno>

---

### Exercício 3 – Empresa
- **Erro:**Declaração XML incorreta (version=1.0 sem aspas).
- **Correção:**
<?xml version="1.0" encoding="UTF-8"?>

<empresa>
  <nome>Tech &amp; Sistemas</nome>
  <cidade>Curitiba</cidade>
</empresa>

---

### Exercício 4 - pedido de venda
- **Erro:**Estrutura incorreta de fechamento de <cliente> e <itens>.
- **Correção:**
<pedido>
  <cliente>
    <nome>Maria</nome>
  </cliente>
  <itens>
    <item>Notebook</item>
    <item>Mouse</item>
  </itens>
</pedido>

---

### Exercício 5 – Cadastro de Produtos
- **Erro:** Tags com espaços e iniciando com número.
- **Correção:**
<produtos>
  <produto>
    <nome>Notebook</nome>
    <preco>4500</preco>
  </produto>
</produtos>

---

### Exercício 6 – Sistema Escolar (Desafio)
- **Erro:** Declaração XML inconsistente, atributos sem aspas, & não tratado e tags não fechadas.
- **Correção:**
<?xml version="1.0" encoding="UTF-8"?>
<escola>
  <aluno matricula="202501" curso="Informática">
    <nome>Lucas &amp; Ana</nome>
    <disciplinas>
      <disciplina>Banco de Dados</disciplina>
      <disciplina>Lógica de Programação</disciplina>
    </disciplinas>
  </aluno>
</escola>

---

📌 Regras Práticas de XML
Fechamento de tags: Sempre abrir e fechar corretamente.

Atributos com aspas: Valores de atributos devem estar entre aspas.

Caracteres especiais: Usar entidades (&amp;, &lt;, &gt;).

Nomes de tags: Não usar espaços, números no início ou caracteres inválidos.

Declaração XML: Sempre começar com <?xml version="1.0" encoding="UTF-8"?>.

✅ Checklist de Correção
Use esta lista para marcar os pontos corrigidos em cada exercício:

[ ] Todas as tags estão abertas e fechadas corretamente.

[ ] Atributos possuem aspas em seus valores.

[ ] Não há espaços ou números em nomes de tags.

[ ] Caracteres especiais foram tratados com entidades (&amp;).

[ ] Declaração XML está correta no início do documento.

🔧 Como Validar
Utilize validadores XML online.

Editores como VS Code, Eclipse ou Notepad++ ajudam a identificar erros.

Ferramentas como XMLLint garantem conformidade com o padrão.

---

Esse README já está pronto para ser usado em um repositório ou como guia de estudo.  
