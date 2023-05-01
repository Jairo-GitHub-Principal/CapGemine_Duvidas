# CapGemine_Duvidas


# na video aula funciona: o professor iniciou ele assim com um construtor, isso na aula 4C
![image](https://user-images.githubusercontent.com/106206316/235394763-d6396369-fa44-468f-9db7-1a6e889bc032.png)

## depois mudo pra isso, não entendi o porque dessa mudança, se o outro jeito estava errado ou se ou se é apenas um ourto jeito de fazer

export class Curso{
nomeCurso:String;valorCurso:Number;idCurso?:Number
}

![image](https://user-images.githubusercontent.com/106206316/235395575-5fd5325d-4146-4486-bc30-d19c105dc939.png)


depois na aula 
# no meu projeto da esse erro:

![image](https://user-images.githubusercontent.com/106206316/235395275-c07e02e8-268d-48e7-8612-68649fe0789f.png)

### nomeCurso:String;
### erro: Property 'nomeCurso' has no initializer and is not definitely assigned in the constructor.ts(2564)

### valorCurso:Number;
### erro: Property 'valorCurso' has no initializer and is not definitely assigned in the constructor.ts(2564)

### pesquisei sobre esses erros e uma das forma de corrigi-lo foi adicionando um undefined ou seja:

### nomeCurso:String|undefined
### valorCurso:Number|undefined

![image](https://user-images.githubusercontent.com/106206316/235396179-5f1cfd74-c9ff-4fef-9ec5-3de17d93f515.png)
#### porem ainda assim não consegui listar os dados na pagina inicial

 obs.: no arquivo app.component.html, eu fiz a declaração da tag <app-curso></app-curso>
