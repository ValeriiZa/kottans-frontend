[ # kottans-frontend](https://github.com/kottans/frontend/blob/2022_UA/tasks/git-intro.md)

# Git та GitHub

Ознайомтеся з Git і GitHub.

1. Прослухайте тижні 1 і 2 курсу [Introduction to Git and GitHub](https://www.coursera.org/learn/introduction-git-github)
Для того, щоб проходити курс безкоштовно, треба натиснути кнопку "Enroll for free" і потім на лінк внизу "Audit course"

  Ви можете вдатися до автоматично перекладених субтитрів, зокрема, якщо ви відчуваєте що це допоможе вам краще засвоїти відеокурс.

   #### Week 1

  <details>
  <summary>Course introduction.</summary>
  <p>

  Could be usufull manual:
   - [Pro Git](https://git-scm.com/book/en/v2) : This book (available online and in print) covers all the fundamentals of how Git works and how to use it. Refer to it if you want to learn more about the subjects that we cover throughout the course.
   - [Git tutorial](https://git-scm.com/docs/gittutorial) : This tutorial includes a very brief reference of all Git commands available. You can use it to quickly review the commands that you need to use.

  ![Course introduction is completed.](https://github.com/ValeriiZa/kottans-frontend/blob/abab7381ebda699e5af3b8799dfac75f5a64e9d7/Screenshot%202022-08-06%20at%2002.07.21.png)

  </p>
  </details>

  <details>
  <summary>Befor version control</summary>
  <p>

  Схоже, Sublime.app використовує команду [diff](https://man7.org/linux/man-pages/man1/diff.1.html) для пошуку різниці між файлами.
  Дізнався нову команду [patch](https://man7.org/linux/man-pages/man1/patch.1.html) . Разом із `diff` є зручний механізм для роботи зі змінами в текстових файлах. При нагоді буду використовувати 'diff' + 'patch', де не підходить графічний інтерфейс svn.

  ![Befor version control is completed](https://github.com/ValeriiZa/kottans-frontend/blob/abab7381ebda699e5af3b8799dfac75f5a64e9d7/Screenshot%202022-08-06%20at%2002.05.40.png)

  </p>
  </details>

  <details>
  <summary>"Version control system", "Using GIT", "Module Wrap Up"</summary>
  <p>

  !["Version control system", "Using GIT", "Module Wrap Up"](https://github.com/ValeriiZa/kottans-frontend/blob/ef9d3a99b58484531e880de00b2210e538c4664b/Screenshot%202022-08-06%20at%2021.58.38.png)

  </p>
  </details>

   #### Week 2

  <details>
  <summary>"Advanced Git interaction", "Undoing Things", "Using GIT", "Module Wrap Up"</summary>
  <p>

  !["Version control system", "Using GIT", "Module Wrap Up"](https://github.com/ValeriiZa/kottans-frontend/blob/1a5ce99c7c8c13ed480387c429b08b0852fb2684/Screenshot%202022-08-07%20at%2023.43.44.png)

  </p>
  </details>


2. Пройдіть наступні рівні тут learngitbranching.js.org:

  <details>
  <summary>Основи: Introduction Sequence</summary>
  <p>

  ![Introduction Sequence](https://github.com/ValeriiZa/kottans-frontend/blob/019c55fde9ec9bbf306033b6d05c4e6ebc1a6fae/Screenshot%202022-08-03%20at%2023.03.15.png)

  </p>
  </details>

  <details>
  <summary>Віддалені репозиторії: Push & Pull -- віддалені репозиторії в Git!</summary>
  <p>

  ![Push \& Pull -- Git Remotes!](https://github.com/ValeriiZa/kottans-frontend/blob/fb769917b85b416f2f7178655bedbe3290253dbc/Screenshot%202022-08-04%20at%2020.07.24.png)

  </p>
  </details>

3. Створіть репозиторій та назвіть його `kottans-frontend`.

4. Створіть `README.md` для репозиторію.

<details>
<summary>5. Опишіть свої враження від вивченого матеріалу.</summary>
<p>

**Здивувало**. В описі [https://learngitbranching.js.org](https://learngitbranching.js.org) говорять, що команда `git switch` є експерементальною, але не вказують станом на який рік. Пропонують використовувати `git checkout`. 
А в [https://git-scm.com/docs/gittutorial](https://git-scm.com/docs/gittutorial) говориться вже про єдину команду `git switch`.
Можна редагувати коміти: 'git commit --amend', треба дослідитии svn на подібну можливість для **подальшого користування**.

**Сподобалась** 'git cherry-pick <Commit1> <Commit2> ...: на відміну від `git merge <Commit>` дозволяє кілька вказаних комітів додати.
Та й взагалі, добрі люди створили цей сайтец.

В Курсері **сподовся** механізм перевірки прослуханого відео: тест, і додавання короткої [виписки](https://training.github.com/downloads/github-git-cheat-sheet.pdf) для користування командами (крім лінків на [мануал](https://git-scm.com/docs/gittutorial) розробника).

</p>
</details>


<details>
<summary>
6. Надішліть pull-request сюди [Kottans/mock-repo](https://github.com/Kottans/mock-repo) пропонуючи зміни.
 
</summary>
<p>

  **Як зробити pull-request**

  - Форкніть цей репозиторій [Kottans/mock-repo](https://github.com/Kottans/mock-repo)
  - Клонуйте свій форк локально на свій комп'ютер: `git clone https://github.com/YOUR_USERNAME/mock-repo.git`
  - Додайте цей репозиторій [Kottans/mock-repo](https://github.com/Kottans/mock-repo) як upstream: `git remote add upstream https://github.com/kottans/mock-repo.git`
  - `git checkout master` і потім створіть нову гілку, ім'я на ваш роздум (aka feature branch): `git checkout -b BRANCH_NAME`.
  - Внесіть деякі зміни до свого локального сховища. Це може бути що завгодно, насправді. Якщо ви знайшли помилку в README - чудово! Подбайте про те, щоб дати своєму PR значуще (осмислене) ім’я та опис.
  - Внесіть зміни до новоствореної гілки (Сommit)
  - Перейдіть до гілки master: `git checkout master`
  - Витягніть останні зміни з гілки upstream master: `git pull upstream master`
  - Об’єднайте головну гілку зі своєю гілкою: `git checkout BRANCH_NAME && git merge master`
  - Вирішіть будь-які конфлікти мержу, якщо такі є (Resolve merge conflicts)
  - Надішліть гілку до вашого віддаленого сховища: `git push --set-upstream origin BRANCH_NAME`
  - Зробіть pull-request з вашого репозиторію до [цього](https://github.com/Kottans/mock-repo) репозиторію через GitHub web-interface
  - Якщо вас попросять виправити merge конфлікт, зверніться до додаткових матеріалів для отримання відповідної інформації
**Зауважте, що ваш PR можуть не розглянути швидко.**

</p>
</details>

<details>
<summary>7. Вивчіть додаткові матеріали нижче, щоб покращити свої навички. Якщо ви вважаєте, що це вплине на вашу загальну ефективність курсу, подумайте над тим, щоб повернутись до них пізніше, наприклад коли ви виконаєте всі обов’язкові завдання.</summary>
<p>

Коли ви закінчите це завдання, ви можете приступити до наступного.

** Додаткові матеріали

 - [Лекція по Git від Олексія Руденка](https://www.youtube.com/playlist?list=PLS8sEUxbfFY9MnPIFPTNlaS5xX7P5Ge-5)

 - [Git за 30 хвилин](https://codeguida.com/post/453)

 - [Git tips](http://sixrevisions.com/web-development/git-tips/) — закріпити свої знання про Git

 - [About Merge Conflicts](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/about-merge-conflicts)

 - [Resoilving a Merge Conflict](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/resolving-a-merge-conflict-using-the-command-line)

 - [Communicating using Markdown](https://lab.github.com/githubtraining/communicating-using-markdown)

 - [Learn anything front-end](https://learn-anything.xyz/web-development/front-end)

 - [TypingClub](https://www.typingclub.com/) — покращити швидкість набору на клавіатурі

 - [How to Learn and Cope with Negative Thoughts](https://guides.hexlet.io/learning/)

## Готово?

➡️ Ідіть далі [Linux, Command Line, HTTP Tools](https://github.com/kottans/frontend/blob/2022_UA/tasks/linux-cli-http.md)

⤴️ Повернутися до змісту курсу: [Contents](https://github.com/kottans/frontend/blob/2022_UA/contents.md)

</p>
</details>

 
## Linux CLI, and HTTP

[Linux CLI, and HTTP](https://github.com/kottans/frontend/blob/2022_UA/tasks/linux-cli-http.md)

RSA: Rivest - Shamir - Adelman (Рон Рівест, Аді Шамір і Леонард Адлман)!


<details>
<summary>Linux CLI</summary>
<p>

Напередодні знайшов ключ до команди ```kill -9 PID```. Ото б пройти цей квест раніше. =)

Дивно, ніколи не задумувався достукуватись до домашньої директорії іншого користувача на компі ```~userName/```

![Quiz 1](https://github.com/ValeriiZa/kottans-frontend/blob/f29f9e01f440c0dc6e9d8fed6d53179d182cddf9/task_linux_cli/Screenshot%202022-08-09%20at%2015.28.30.png)

![Quiz 2](https://github.com/ValeriiZa/kottans-frontend/blob/f29f9e01f440c0dc6e9d8fed6d53179d182cddf9/task_linux_cli/Screenshot%202022-08-09%20at%2021.28.30.png)

![Quiz 3](https://github.com/ValeriiZa/kottans-frontend/blob/f29f9e01f440c0dc6e9d8fed6d53179d182cddf9/task_linux_cli/Screenshot%202022-08-11%20at%2000.13.16.png)

![Quiz 4](https://github.com/ValeriiZa/kottans-frontend/blob/f29f9e01f440c0dc6e9d8fed6d53179d182cddf9/task_linux_cli/Screenshot%202022-08-11%20at%2000.46.38.png)

</p>
</details>


## Git Collaboration

<details>
<summary>Git Collaboration</summary>
<p>

Для подальшого використання варто обміркувати думку створення гілки тільки під реліз/зборку.

Коміти найменшу логічну зміни окремо (навіть якщо це: декорація, одруківка, ...)!

Позитивним в GIT вбачаю можливість вносити зміни в текст і зі HTML сторінки, і з командног рядка. Також, можливсіть створювати задачі та ставити на задачі виконавця. Тобто інтеграція системи контролю версій із системою відстеження помилок та управління проєктами.

Але чи замінить GIT повноцінно JIRA?

Варто дослідити графічні інтерфейси для локального GIT проекта? Відстежувати зміни проекта в Terminal та сторінці (сервер) не зовсім зручно.

![Week 3](https://github.com/ValeriiZa/kottans-frontend/blob/4e470f96d574820ec824cefde9208b2a6da1c113/task_git_collaboration/Screenshot%202022-08-19%20at%2022.01.57.png)

![Week 4](https://github.com/ValeriiZa/kottans-frontend/blob/4e470f96d574820ec824cefde9208b2a6da1c113/task_git_collaboration/Screenshot%202022-08-19%20at%2022.02.09.png)

</p>
</details>



<sup>Як стверджує народна мудрість від китайців-одногрупників: я умію - ти умієш.</sup>
