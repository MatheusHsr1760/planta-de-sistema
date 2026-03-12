## Regras de Boa Vizinhança na Arquitetura de Software

**Situação A:** O botão de "Comprar" faz o cálculo do desconto e salva direto no banco de dados, sem passar pela camada de negócio.

**Por que isso é ruim?**  
Isso é ruim porque a **Camada de Apresentação** (o botão) está fazendo tarefas que deveriam ser da **Camada de Negócio**. Cada camada deve ter sua própria responsabilidade. Quando a interface faz cálculos e salva dados diretamente, o sistema fica mais desorganizado e difícil de manter.

---

**Situação B:** A camada de dados decide que a data deve aparecer no formato "dia/mês/ano" na tela do celular.

**Qual camada deveria ser responsável por essa "beleza"?**  
Essa responsabilidade deveria ser da **Camada de Apresentação**, pois ela é responsável pela forma como as informações aparecem para o usuário, incluindo formatação e aparência na tela.
