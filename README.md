[ # kottans-frontend](https://github.com/kottans/frontend/blob/2022_UA/tasks/git-intro.md)

# Git та GitHub

Ознайомтеся з Git і GitHub.

1. Прослухайте тижні 1 і 2 курсу [Introduction to Git and GitHub](https://www.coursera.org/learn/introduction-git-github)
Для того, щоб проходити курс безкоштовно, треба натиснути кнопку "Enroll for free" і потім на лінк внизу "Audit course"

Ви можете вдатися до автоматично перекладених субтитрів, зокрема, якщо ви відчуваєте що це допоможе вам краще засвоїти відеокурс.

2. Пройдіть наступні рівні тут learngitbranching.js.org:

  - Основи: Introduction Sequence
![Introduction Sequence](https://github.com/ValeriiZa/kottans-frontend/blob/019c55fde9ec9bbf306033b6d05c4e6ebc1a6fae/Screenshot%202022-08-03%20at%2023.03.15.png)

  - Віддалені репозиторії: Push & Pull -- віддалені репозиторії в Git!
![Push & Pull -- Git Remotes!](./Screenshot%202022-08-04%20at%2020.07.24.png)

3. Створіть репозиторій та назвіть його `kottans-frontend`.

4. Створіть `README.md` для репозиторію.

5. Опишіть свої враження від вивченого матеріалу.

**Здивувало**. В описі [https://learngitbranching.js.org](https://learngitbranching.js.org) говорять, що команда `git switch` є експерементальною, але не вказують станом на який рік. Пропонують використовувати `git checkout`. 
А в [https://git-scm.com/docs/gittutorial](https://git-scm.com/docs/gittutorial) говориться вже про єдину команду `git switch`.
Можна редагувати коміти: 'git commit --amend', треба дослідитии svn на подібну можливість для **подальшого користування**.

**Сподобалась** 'git cherry-pick <Commit1> <Commit2> ...: на відміну від `git merge <Commit>` дозволяє кілька вказаних комітів додати.
Та й взагалі, добрі люди створили цей сайтец.


6. Надішліть pull-request сюди [Kottans/mock-repo](https://github.com/Kottans/mock-repo) пропонуючи зміни.

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

7. Вивчіть додаткові матеріали нижче, щоб покращити свої навички. Якщо ви вважаєте, що це вплине на вашу загальну ефективність курсу, подумайте над тим, щоб повернутись до них пізніше, наприклад коли ви виконаєте всі обов’язкові завдання.

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

