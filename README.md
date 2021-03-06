# Padrão de Projeto Memento

## Classes
- __Originator:__ Classe que precisa de backups. Sabe como fazer e restaurar seu próprio backup. Salva seus dados em "ConcreteMemento".
- __Caretaker:__ Gerencia os backups da classe originadora, porém, conhece apenas os métodos da interface IMemento.
- __ConcreteMemento:__ Tem acesso ao estado do Originator, porém não manipular os dados presententes na classe Originadora.
- __IMemento:__ Responsável por ocultar os dados da classe Originator para que a classe Caretaker não possua acesso.

## Diagrama de Classes

![Memento](https://user-images.githubusercontent.com/52468127/127525983-5f7fcc3a-dbb4-46f6-8b16-699793238719.png)

### Método de instalação para testes
1. ```git clone https://github.com/John-Rocha/design-patterns-memento.git```
2. Na raiz do projeto execute o comando ```npm install```

