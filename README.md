# RH_Projeto_alura
Projeto criado para entedimento e aplicação dos princípios  SOLID realizados no curso 'SOLID com Java: princípios da programação orientada a objetos' da Alura.

Anotações pessoais que realizei durante o curso:

### **Orientação a Objetos**✨

- **Coesão** → Delimitar um objetivo e ser restrito, seja em uma classe ou método
- **Encapsulamento** → Não é somente get/set, gerar validações, regras de negócio para manter os valores de uma classe e que não seja possível burlar os valores
- **Acoplamento** → Não criar classes muito dependente entra as outras, para facilitar ajustes futuros e quando for realizar ajuste ao realiza a ação em uma classe não impactar em varias outras

### **Princípios SOLID**✨

- **S** → **Single Responsibility principe** → Princípio da responsabilidade única, a classe deve ter um único motivo para mudar, ou seja, motivos que se referem a mesma coisa e não fujam do escopo. (Manter alta coesão)
- **O** → **Open Closed Principle** → Quantos menos modificações nas classes melhor, fazer um jeito de que o código possa ser extensível e não seja necessário atualização quando for necessário implementar uma nova funcionalidade
- **L** → **Liskov Substitution Principle** → Tomar cuidado quando for usar herança para não gerar casos de utilização de métodos indesejados que se não se adequam a sua regra de negócio. Pois pode causar trechos sem sentido. Se a herança não atender sua aplicação, você pode utilizar a composição.
- **I** → **Interface Segregation Principle** → Uma classe não deveria ser forçada a depender de métodos que não utilizará.
- **D** → **Dependency Inversion Principle** → A implementação deve depender da abstração e não o inverso, ou seja, não é aconselhável  se basear na implementação pois a mesma pode ter varias alterações ao decorrer do tempo.
