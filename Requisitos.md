Requisitos do Sistema de Gestão Acadêmica (SGA)

Requisitos Funcionais (RF)

Módulo de Autenticação e Perfis:
  RF01: O sistema deve permitir a autenticação de usuários (aluno, professor, administrador) com login e senha.
  RF02: O sistema deve ter diferentes níveis de acesso baseados no perfil do usuário.
  RF03: O sistema deve permitir a recuperação de senha.

 Módulo Administrativo:
  RF04: O sistema deve permitir que administradores cadastrem, editem e excluam cursos.
  RF05: O sistema deve permitir que administradores cadastrem, editem e excluam disciplinas, associando-as a um curso.
  RF06: O sistema deve permitir que administradores cadastrem, editem e excluam alunos.
  RF07: O sistema deve permitir que administradores cadastrem, editem e excluam professores.
  RF08: O sistema deve permitir que administradores matriculem alunos em disciplinas.
  RF09: O sistema deve permitir que administradores associem professores a disciplinas.

Módulo do Professor:
 RF10: O sistema deve permitir que professores visualizem as turmas (disciplinas) que lecionam.
 RF11: O sistema deve permitir que professores lancem as notas dos alunos em suas turmas.
 RF12: O sistema deve permitir que professores registrem a frequência (presenças e faltas) dos alunos.
 RF13: O sistema deve permitir que professores publiquem materiais de aula (arquivos, links) para suas turmas.

Módulo do Aluno
 RF14: O sistema deve permitir que o aluno visualize as disciplinas em que está matriculado.
 RF15: O sistema deve permitir que o aluno consulte suas notas e frequência em cada disciplina.
 RF16: O sistema deve permitir que o aluno acesse os materiais de aula publicados pelos professores.
 RF17: O sistema deve permitir que o aluno realize sua inscrição em disciplinas disponíveis para o seu curso (em período de matrícula).

 Requisitos Não Funcionais (RNF)
  RNF01 (Segurança): A comunicação com o servidor deve ser feita via HTTPS. As senhas devem ser armazenadas de forma criptografada (hash).
  RNF02 (Desempenho): As páginas do sistema devem carregar em no máximo 3 segundos.
  RNF03 (Usabilidade): O sistema deve possuir uma interface intuitiva e responsiva, adaptando-se a diferentes tamanhos de tela (desktop, tablet, mobile).
  RNF04 (Disponibilidade): O sistema deve estar disponível 99.5% do tempo.
  RNF05 (Compatibilidade): O sistema deve ser compatível com os principais navegadores do mercado (Google Chrome, Firefox, Safari, Edge).

