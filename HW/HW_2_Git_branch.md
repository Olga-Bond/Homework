 Branch
 
1. На локальном репозитории сделать ветки для:                                                                                                                   
Postman === git branch Postman                                                                                                                                                 
Jmeter === git branch Jmeter                                                                                                                                                      CheckLists === git branch CheckLists                                                                                                                                           
Bag_Reports === git branch Bag_Reports                                                                                                                                   
SQL === git branch SQL                                                                                                                                                           Charles === git branch Charles                                                                                                                                                   Mobile testing === git branch Mobile_testing
2. Запушить все ветки на внешний репозиторий === git push -u origin --all
3. В ветке Bag_Reports сделать текстовый документ со структурой баг репорта === git checkout Bag_Reports === cat > bag_report.txt

 Heading                                                                                                                                                                                                 
 Summary: error 500                                                                                                                                                                             
 Project: Yandex.ru                                                                                                                                                                               
 Component: Email registration page                                                                                                                                                   
 Version: 22.1.4.627 beta                                                                                                                                                                      
 Severity: Blocker                                                                                                                                                                                    
 Priority: High                                                                                                                                                                                         
 Steps to Reproduce: Steps                                                                                                                                                                    
 Actual Result : page lock                                                                                                                                                                     
 Expected Result: opening a page                                                                                                                                                         
 Additional Information: Other                                                                                                                                                              
 Attachments                                                                                                                                                                                         

4. Запушить структуру багрепорта на внешний репозиторий === git add . === git commit -m "текст" === git push
5. Вмержить ветку Bag_Reports в Main === git checkout main === git merge Bag_Reports
6. Запушить main на внешний репозиторий === git push
7. В ветке CheckLists набросать структуру чек листа === git checkout CheckLists === cat > check_list.txt

 ID: 1                                                                                                                                                                                                       
 Check: checking the possibility of registration with empty form fields                                                                                               
 Result: Passed                                                                                                                                                                                      
 Comments:                                                                                                                                                                                            

8. Запушить структуру на внешний репозиторий === git add . === git commit -m "текст" === git push
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main === Compare & pull request === Create pull request === Merge pull request === Confirm merge
10. Синхронизировать Внешнюю и Локальную ветки Main === git checkout main === git pull
