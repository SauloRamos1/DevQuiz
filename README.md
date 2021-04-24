# DevQuiz

A Flutter project created on NeverStopLearning 05.
<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2FM5BUOZMoLds8KcWEUpqQwb%2FDevQuiz-Copy%3Fnode-id%3D2%253A3" allowfullscreen></iframe>
<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2FM5BUOZMoLds8KcWEUpqQwb%2FDevQuiz-Copy%3Fnode-id%3D0%253A1" allowfullscreen></iframe>

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
    - title
    - background
    - textStyle
    - borderRadius
    - onTap
- [ ]  QuizCard
    - icon
    - title
    - score
    - progress bar
    - onTap
- [ ]  Utilizar ListView
- [ ]  Criar ChallengePage
    - [ ]  Criar QuestionIndicatorWidget
        - currentQuestion
        - sizeQuestions
    - [ ]  Criar QuizWidget
        - titleQuestion
        - [ ]  AwnserWidget
            - Link do arquivo

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
