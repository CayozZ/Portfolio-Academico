# Portfólio acadêmico Cayo Luiz

Repositório que reúne as atividades das unidades curriculares e o material do Projeto Integrador (PI) do curso de Análise e Desenvolvimento de Sistemas, turma TADS039M, Faculdade Senac Pernambuco.

A organização segue os conceitos de Arquitetura da Informação trabalhados na Aula 5 de Gestão da Informação: classificação, taxonomia, metadados, navegação, encontrabilidade e relações entre conteúdos. A seção seguinte explica como cada um foi aplicado aqui.

## Como o repositório está organizado

### Classificação e taxonomia

O repositório é dividido em dois grandes grupos, que são as duas categorias de conteúdo que um aluno do curso realmente produz:

- `projeto-integrador/`: tudo relacionado ao PI do 5º período, o InvestCase, plataforma de matchmaking entre startups e investidores anjo do Nordeste.
- `unidades-curriculares/`: atividades de cada disciplina que não fazem parte do PI.

Dentro de `projeto-integrador/`, a taxonomia segue a ordem natural de um projeto de produto, não a ordem cronológica das aulas, porque isso facilita achar o conteúdo por fase do trabalho:

- `01-descoberta/`: pesquisa de problema, qualidade da informação e Customer Discovery.
- `02-design/`: modelo de dados, protótipos de tela e decisões de UX.
- `03-governanca/`: segurança, LGPD e perfis de acesso.

Dentro de `unidades-curriculares/`, cada pasta é uma disciplina, nomeada igual ao nome usado no Teams, para bater com o que já está na cabeça de quem procura.

### Metadados

Cada pasta tem um `README.md` com uma tabela de metadados no topo, contendo disciplina, aula de referência, data de entrega, status e uma descrição curta. Isso permite entender o conteúdo de uma pasta sem precisar abrir cada arquivo.

### Navegação

A navegação acontece em três níveis: este README geral, o README de cada pasta principal, e o nome dos arquivos dentro dela. Em nenhum nível é preciso abrir um arquivo para saber o que ele é, porque o nome e a tabela de metadados já respondem isso.

### Encontrabilidade

Os nomes de arquivo e pasta usam termos que uma pessoa de fora do projeto também usaria para buscar (ex: `modelo-de-dados`, `customer-discovery`, em vez de siglas internas do grupo). Isso facilita tanto a busca pelo GitHub quanto por quem só conhece o nome da atividade, não o nome interno do arquivo.

### Relações entre conteúdos

Algumas atividades pertencem ao mesmo tempo ao PI e a uma disciplina específica, por exemplo o Modelo de Dados foi produzido para a disciplina de Gestão da Informação, mas também é parte do design do PI. Nesses casos, o arquivo fica fisicamente numa única pasta (a do PI, por ser o lugar mais específico) e a pasta da disciplina correspondente linka para ele, em vez de duplicar o arquivo. Essa relação fica explícita na tabela de metadados de cada README, numa coluna chamada "relacionado a".

## Sobre o Projeto Integrador

O InvestCase é uma plataforma SaaS de matchmaking que conecta startups nascentes do Porto Digital a investidores anjo, incluindo modelo de negócio e governança. Professor focal: Geraldo Gomes da Cruz Júnior. Primeira entrega em 15/10/2026 (MVP, backend, banco de dados e modelo de negócio inicial), segunda entrega em 11/12/2026 (plataforma final, matchmaking, governança, validação e go to market).

Mais detalhes em [`projeto-integrador/README.md`](projeto-integrador/README.md).
