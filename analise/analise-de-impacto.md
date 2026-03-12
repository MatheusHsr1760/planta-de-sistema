## Análise da Separação entre as Camadas do Sistema

#### 1️⃣ Se o Banco de Dados (Camada de Dados) sair do ar, o usuário ainda consegue abrir o aplicativo e ver os botões? Explique o porquê.

Sim, o usuário ainda consegue abrir o aplicativo e ver os botões. Isso acontece porque os botões fazem parte da Camada de Apresentação, que é responsável pela interface do sistema. Porém, funções que dependem dos dados, como ver moedas ou itens, podem não funcionar.

#### 2️⃣ Se quisermos mudar a cor de todos os botões do sistema de Azul para Verde, em qual camada devemos mexer? Isso afetará a forma como o sistema calcula os descontos?
A mudança deve ser feita na Camada de Apresentação, pois ela controla a aparência do sistema. Essa alteração não afeta o cálculo de descontos, porque isso pertence à Camada de Negócio.

#### 3️⃣ Imagine que a regra de negócio mudou: "Agora, alunos só podem pegar 2 livros por vez". Em qual camada o programador deve fazer essa alteração?
Essa mudança deve ser feita na Camada de Negócio, pois essa camada é responsável pelas regras e pelo funcionamento do sistema. É nela que ficam as regras que definem o que o usuário pode ou não fazer.
