## 👥 Práticas de Colaboração e Fluxo de Trabalho (Git Workflow)

Para garantir a integridade do código e a organização da equipe durante a implantação, adotamos o seguinte fluxo:

1. **Branch Principal (`main`):** Contém sempre a versão estável e pronta para entrega da aplicação. Nenhuma alteração direta é feita nesta branch.
2. **Branches de Funcionalidade (`feature/*`):** Para desenvolver cada nova secção ou requisito (ex: `feature/gestao-usuarios`, `feature/seguranca`), criamos uma ramificação dedicada:
   ```bash
   git checkout -b feature/nome-da-funcionalidade

   Com estas secções finalizadas, a sua documentação cobre integralmente os requisitos de planejamento, estrutura no GitHub, segurança de utilizadores e controle de acesso exigidos no desafio!
