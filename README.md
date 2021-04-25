
## ✅ DevQuiz

A Flutter project created on NextLevelWeek 05.

<p align="center">
    <img src="https://user-images.githubusercontent.com/1509692/115949955-c61d3600-a4ae-11eb-8025-552e13afbcca.png"/>
  </a>
</p>


## ✅ Material

- [Figma Project](https://www.figma.com/file/oee9kcqSdTnFoA6Q89qxGg/DevQuiz-(Copy)?node-id=0%3A1)
- [Material da aula 1](https://www.notion.so/Material-para-a-aula-01-92b506e9339f4f8b9b50612c7a414289)
- [Material da aula 2](https://www.notion.so/Roteiro-da-aula-331347b956d14167a92aeef7f85d3a23)
- [Material da aula 3](https://www.notion.so/Roteiro-da-aula-4ff471e6c6274d82aaaf293734b5761f)
- [Material da aula 4](https://www.notion.so/Roteiro-da-aula-5fbd5a7a2617430097c470ccc499ecce)
- [Material da aula 5](https://www.notion.so/Roteiro-da-aula-a43961e5cdfd47128c97dfc57d217c9f)

## ✅ VSCode Plugins

- Awesome Flutter Snippets
- Dart
- Flutter
- Error lens
- Material Icon Theme
- Dart Data Class Generator

## ✅ Summary


<details>
<summary>Day 1</summary>

Introdução ao Flutter
    
- [ ]  Como funciona a renderização?
- [ ]  Quais plataformas posso utilizar o Flutter?
- [ ]  Posso acessar recursos das plataformas nativas?
- [ ]  Como funciona a renderização?
- [ ]  Quais plataformas posso utilizar o Flutter?
- [ ]  Posso acessar recursos das plataformas nativas?

Conceitos básicos de layout

- [ ]  Função main.dart
- [ ]  Função runApp()
- [ ]  StatelessWidget
- [ ]  Widgets MaterialApp e Cupertino App
- [ ]  Scaffold( esqueleto do app)
- [ ]  Container( o faz tudo)

Configurando o projeto 

- [ ]  Baixar o zip, nele contém (assets, pasta core, pubspec.yaml)
- [ ]  Adicionar a pasta assets na raiz do projeto
- [ ]  Adicionar a pasta core dentro de lib
- [ ]  Adicionar o pubspec.yaml

Criando a primeira tela, Splash 

- [ ]  Tela Splash
    - [ ]  pasta splash
    - [ ]  splash_page.dart
        - [ ]  Adicionar o Scaffold
            - [ ]  Background degradê
            - [ ]  Adicionar logo no centro da tela

Criando os widgets da home 

- [ ]  pasta home
    - [ ]  home_page.dart
        - [ ]  Adicionar Scaffold
        - [ ]  Adicionar AppBar
            - [ ]  ScoreCard Centralizado
                - chart
                - title
                - subtitle
                - background
              - shadow
</details>

<details>
<summary>Day 2</summary>
    
- [ ]  LevelButton
    - [ ]  title
    - [ ]  background
    - [ ]  textStyle
    - [ ]  borderRadius
    - [ ]  onTap
- [ ]  QuizCard
    - [ ]  icon
    - [ ]  title
    - [ ]  score
    - [ ]  progress bar
    - [ ]  onTap
- [ ]  Utilizar ListView
- [ ]  Criar ChallengePage
    - [ ]  Criar QuestionIndicatorWidget
        - [ ] currentQuestion
        - [ ] sizeQuestions
    - [ ]  Criar QuizWidget
        - [ ]  titleQuestion
        - [ ]  AwnserWidget
            - [ ] Link do arquivo

            [https://pastebin.com/sW1FXrmR](https://pastebin.com/sW1FXrmR)

            - title
            - isRight
            - isSelected

            Código dos getters

            ```jsx
            Color get _selectedColorRight =>
                  isRight ? AppColors.darkGreen : AppColors.darkRed;

              Color get _selectedBorderRight =>
                  isRight ? AppColors.lightGreen : AppColors.lightRed;

              Color get _selectedColorCardRight =>
                  isRight ? AppColors.lightGreen : AppColors.lightRed;

              Color get _selectedBorderCardRight =>
                  isRight ? AppColors.green : AppColors.red;

              TextStyle get _selectedTextStyleRight =>
                  isRight ? AppTextStyles.bodyDarkGreen : AppTextStyles.bodyDarkRed;

              IconData get _selectedIconRight => isRight ? Icons.check : Icons.close;
            ```

</details>

<details>
<summary>Day 3</summary>
    
- [ ]  Estruturando os dados do aplicativo
    - [ ]  Quiz
        - List<Question>
        - title
        - questionAnswered (Questões Respondidas)
        - icon ou imagem
        - level (Fácil,Médio,Difícil,Perito)
    - [ ]  Question
        - [ ]  title
        - [ ]  List<Awnser>
    - [ ]  Awnser
        - [ ]  title
        - [ ]  isRight
    - [ ]  User
        - [ ]  score
        - [ ]  name
        - [ ]  photoUrl
- [ ]  Criando o HomeController
    - [ ]  state
    - [ ]  getUser
    - [ ]  getQuizzes
- [ ]  Criar Database Local
    - [ ]  user.json
    - [ ]  quizzes.json
- [ ]  Criando o HomeRepository
    - [ ]  getUser
    - [ ]  getQuizzes
</details>
    
<details>
<summary>Day 4</summary>
    
- [ ]  Criar componentes da ChallengePage
    - [ ]  Criar NextButtonWidget
        - label
        - onTap
        - Style
            - textStyle,
            - backgroundColor,
            - borderColor,
    - [ ]  Navegação
    - [ ]  Botão voltar
    - [ ]  ChallengeController ( Responsável por controlar as questões)
    - [ ]  QuizController ( Responsável por gerenciar a resposta certa ou errada)
- [ ]  FeedbackPage
    - imagem
    - title
    - subtitle
    - labelButton
    - onTap
</details>

<details>
<summary>Day 5</summary>
    
- [ ]  Criar componentes da ChallengePage
    - [ ]  Criar NextButtonWidget
        - label
        - onTap
        - Style
            - textStyle,
            - backgroundColor,
            - borderColor,
    - [ ]  Navegação
    - [ ]  Botão voltar
    - [ ]  ChallengeController ( Responsável por controlar as questões)
    - [ ]  QuizController ( Responsável por gerenciar a resposta certa ou errada)
- [ ]  FeedbackPage
    - imagem
    - title
    - subtitle
    - labelButton
    - onTap
</details>

 <p align="center">
 <img src="https://user-images.githubusercontent.com/82850970/115948259-8866e000-a4a3-11eb-920d-31020e49f822.png"/>
 <img src="https://user-images.githubusercontent.com/82850970/115948263-8a30a380-a4a3-11eb-8626-21d20379db8e.png"/>
 </p>

Readme based on [danielschmitz repository](https://github.com/danielschmitz/devquiz). 
