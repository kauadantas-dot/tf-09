# TF-09 - Pilares da Orientação a Objetos
- Encapsulamento: A interface expõe a leitura da propriedade destino e o método redirecionar(), enquanto a implementação esconde o atributo privado __destino nos __slots__ e a validação que barra ciclos e auto-referência.
- Herança: A interface disponibiliza os recursos herdados de Item como nome, pai, mover_para() e caminho(), enquanto a implementação do gerenciamento de nós da árvore fica resguardada na superclasse.
- Polimorfismo: A interface requer apenas o cumprimento do contrato Medivel com tamanho() e mostrar(), enquanto a implementação própria do Atalho responde com 1 byte fixo e a exibição formatada com seta (->).
