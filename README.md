# exercício de array-
let tarefas = ['Estudar', 'Lavar a louça', 'Fazer exercícios'];
tarefas.push('comprar pão','ler um livro')//1adiciona no final
let ultimaTarefa= tarefas[tarefas.length - 1]//2adicionar o ultimo item da lista
tarefas.pop()

tarefas.unshift('Acordar cedo', 'Tomar café');//3adiciona no começo
let primeiraTarefa=tarefas.splice(0,1)//4tira de tarefas e coloca aí
tarefas.splice(0, 2, 'Fazer café da manhã', 'Organizar a mesa');//5 substitui o que etsava aí
let tarefasSelecionadas = tarefas.slice(1, 4);//6 copia e coloca aí
let tarefasCompletas = tarefas.concat(['Ver um filme', 'Descansar']);//7 junta

console.log("Lista original de tarefas:", tarefas);
console.log("Última tarefa removida:", ultimaTarefa);
console.log("Primeira tarefa removida:", primeiraTarefa);
console.log("Tarefas selecionadas:", tarefasSelecionadas);
console.log("Lista final de tarefas:", tarefasCompletas);
