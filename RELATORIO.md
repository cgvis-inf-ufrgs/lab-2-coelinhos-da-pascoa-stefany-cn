# Relatório - Coelinhos da Páscoa

> [!CAUTION]
> - Lembre-se que você <ins>**não pode utilizar ferramentas de IA para
>   escrever este relatório**</ins>

## Dados do aluno

- **Cartão UFRGS**: 00263870
- **Nome**: Stefany Nascimento

## Passos que eu segui para resolver o problema especificado (em formato de *"prompt"*)

> [!IMPORTANT]
> - Coloque aqui todas as informações necessárias para que alguém
>   (pessoa ou ferramenta de IA) possa reproduzir os seus passos para
>   solucionar o problema
> - Escreva em formato imperativo, como se fosse um *prompt* com as
>   instruções a serem seguidas na solução do problema
> - Seja objetivo e conciso: quanto *menos palavras* você utilizar,
>   melhor
> - Seja técnico e use terminologia adequada: assuma que quem irá ler
>   os seus passos possui conhecimento de Ciência da Computação e
>   Computação Gráfica
> - Caso você queira incluir informações "longas" (como algum *prompt*
>   grande usado com alguma ferramenta de IA), crie arquivos à parte e
>   adicione links no texto (por exemplo, crie o arquivo `PROMPTS.md`
>   e adicione um link markdown `[os prompts detalhados estão
>   aqui](PROMPTS.md)`)
> - Novamente, lembre-se que você *não pode utilizar ferramentas
>   de IA para escrever este relatório*

<h3>Prompt</h3>
Desenhe 16 coelhos, de tal forma que eles estejam distribuídos em um círculo. Faça cada coelho transladar circularmente centrado no círculo em que foram desenhados. Aplique uma rotação horizontal, sobre seu próprio eixo, em cada coelho, no sentido anti-horário. A taxa de rotação pode ser calculada usando o ângulo relativo da posição do coelho. Faça cada coelho se movimentar verticalmente senoidalmente. A frequência de cada onda deve ser o dobro. Ou seja, o comprimento da onda será a metade. A cada 4 coelhos, aplique uma rotação vertical no coelho correspondente, tal que ele termine uma rotação completa utilizando o mesmo comprimento utilizado no movimento vertical. Para cada coelho, desenhe duas esferas de cada lado, escalone para que fique no formato de um ovo e aplique uma translação circular centrada no coelho correspondente. A posição das esferas e translação em relação ao tempo deve ser sempre relativa ao coelho correspondente.

## Principais dificuldades encontradas durante o desenvolvimento (formato livre)

A principal dificuldade foi entender como e onde eu deveria fazer as mudanças necessárias. No papel eu já tinha "resolvido", porém não tinha nem uma ideia de como aplicar essa solução no código. 

## Você acha que conseguiu resolver o problema de forma adequada?

Acredito que sim, fiquei bem satisfeita e contente com o resultado.

## Se você quiser compartilhar mais alguma coisa, coloque aqui:

Minha linha de raciocínio:<br>
1. Desenhar 16 coelhos e ajustar o tamanho
2. Distribuir os coelhos, tal que cada um estivesse posicionado em uma "fatia" de um círculo
3. Adicionar duas esferas "deformadas" para cada coelho e ajustar o tamanho
4. Fazer o movimento de translado circular dos coelhos centrados no mesmo lugar
5. Fazer o movimento vertical dos coelhos 
6. Fazer a rotação dos coelhos
7. Fazer a órbita das esferas em torno dos coelhos
8. A cada 4 coelhos, colocar a "pirueta" em um
9. Ajustar velocidades

## Se você possui alguma sugestão para o professor sobre esta atividade, coloque aqui:

Minha sugestão seria mostrar um exemplo bem simples, mostrando com calma como podemos fazer as transformações já que tive bastante dificuldade para saber o que mudar e onde mudar para poder desenvolver o que eu já tinha "resolvido" no papel.<br>
Também sugiro liberar para deixarmos os nossos repositórios como "privados" :P.
