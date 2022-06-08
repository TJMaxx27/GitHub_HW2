# GitHub_HW2
1. На локальном репозитории сделать ветки для:
- Postman
- Jmeter
- CheckLists
- Bag Reports
- SQL
- Charles
- Mobile testing
```bash
git branch Postman && git branch Jmeter && git branch CheckLists && git branch Bug_Reports && git branch SQL && git branch Charles && git branch Mobile_testing
```

2. Запушить все ветки на внешний репозиторий
```bash
git push -u --all
```
3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта
```bash
git checkout Bug_Reports && touch fst_br.txt && vim fst_br.txt --> Text
```
4. Запушить структуру багрепорта на внешний репозиторий
```bash
git add . && git commit -m "bug report" && git push
```
5. Вмержить ветку Bag Reports в Main
```bash
git checkout main && git merge Bug_Reports
```
6. Запушить main на внешний репозиторий.
```bash
git push
```
7. В ветке CheckLists набросать структуру чек листа.
```bash
vim checklist.txt --> text
```
8. Запушить структуру на внешний репозиторий
```bash
git add . --> git commit -m "add checklist.txt" -> git push origin CheckLists
```
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
```bash
В вебинтерфейсе: Compare & pull request --> Create pull request --> Merge pull request --> Confirm merge
```
10. Синхронизировать Внешнюю и Локальную ветки Main
```bash
git checkout main && git pull
```
