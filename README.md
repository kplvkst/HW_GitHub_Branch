# HW_GitHub_Branch

GitHub. HW_2
1. На локальном репозитории сделать ветки для:
- Postman
git branch Postman
- Jmeter
git branch Jmeter
- CheckLists
git branch CheckLists
- Bug Reports
git branch Bug_Reports
- SQL
git branch SQL
- Charles
git branch Charles
- Mobile testing
git branch Mobile_testing

2. Запушить все ветки на внешний репозиторий
git push origin --all
3. В ветке Bug_Reports сделать текстовый документ со структурой баг репорта
git checkout Bug_Reports
vim bug_report.txt
4. Запушить структуру багрепорта на внешний репозиторий
git add .
git commit -m "create bug_report.txt"
git push
5. Вмержить ветку Bug_Reports в Main
git checkout main
git merge Bug_Reports
6. Запушить main на внешний репозиторий.
git add .
git commit -m "merge Bug_Reports"
git push
7. В ветке CheckLists набросать структуру чек листа.
git checkout CheckLists
vim checklist.txt
8. Запушить структуру на внешний репозиторий
git add .
git commit -m "create checklist.txt"
git push
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
10. Синхронизировать Внешнюю и Локальную ветки Main
git checkout main
git pull