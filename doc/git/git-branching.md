## Занияте 2. Git-branching

1. Создали ветку *git-merge* и переключились, сделали коммиты в ней, запушили в репозиторий командой:

` git push -u origin git-merge `

![all text](../img/git-branching/1.png)

2. Переключились на коммит *prepare for merge and rebase* и создали новую ветку *git-rebase*, сделали в ней коммиты

![all text](../img/git-branching/2.png)

![all text](../img/git-branching/3.png)

3. Промежуточный итог выглядел вот так:

![all text](../img/git-branching/4.png)

4. Переключились на *main* командой ` git checkout main ` и выполнили merge веток ` git merge git-merge `

5. Выполнили rebase, решая конфликты:

![all text](../img/git-branching/5.png)

6. Отправили ветку в удаленный репозиторий

![all text](../img/git-branching/6.png)