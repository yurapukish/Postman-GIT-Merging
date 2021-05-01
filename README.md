# Postman-GIT-Merging


Task 2. Postman, GIT.

Postman.

endpoint_1: object_info_1
method: GET
request_params: 
   1) age (int)
   2) weight (int)
   3) name (str)

response: 
{'name': name,
          'age': age,
          'daily_food': weight * 0.012,
          'daily_sleep': weight * 2.5}
========

endpoint_2: object_info_2
method: GET
request_params: 
   1) age (int)
   2) salary (int)
   3) name (str)

response: 
{'start_qa_salary': salary,
          'qa_salary_after_6_months': salary * 2,
          'qa_salary_after_12_months': salary * 2.7,
          'qa_salary_after_1.5_year': salary * 3.3,
          'qa_salary_after_3.5_years': salary * 3.8,
          'person': {'u_name': [user_name, salary, age],
                     'u_age': age,
                     'u_salary_5_years': salary * 4.2}
          }

=========

endpoint_3: object_info_3
method: GET
request_params: 
   1) age (int)
   2) salary (int)
   3) name (str)

response: 
result = {'name': name,
          'age': age,
          'salary': salary,
          'family': {'children': [['Alex', 24], ['Kate', 12]],
                     'pets': {'cat':{'name':'Sunny',
                                     'age': 3},
                              'dog':{'name':'Luky',
                                     'age': 4}},
                     'u_salary_1_5_year': salary * 4}
          }

=========

endpoint_4: object_info_4
method: GET
request_params: 
   1) age (int)
   2) name (str)
   3) salary (int)

response: 
result = {'name': name,
          'age': int(age),
          'salary': [salary, str(salary * 2), str(salary * 3)]}

============================

endpoint_5: user_info_1
method: POST
form_params: 
   1) age (int)
   2) weight (int)
   3) name (str)

response: 
{'name': name,
          'age': age,
          'daily_food': weight * 0.012,
          'daily_sleep': weight * 2.5}
========

endpoint_6: user_info_2
method: POST
form_params: 
   1) age (int)
   2) salary (int)
   3) name (str)

response: 
{'start_qa_salary': salary,
          'qa_salary_after_6_months': salary * 2,
          'qa_salary_after_12_months': salary * 2.7,
          'qa_salary_after_1.5_year': salary * 3.3,
          'qa_salary_after_3.5_years': salary * 3.8,
          'person': {'u_name': [user_name, salary, age],
                     'u_age': age,
                     'u_salary_5_years': salary * 4.2}
          }

=========

endpoint_7: user_info_3
method: POST
form_params: 
   1) age (int)
   2) salary (int)
   3) name (str)

response: 
result = {'name': name,
          'age': age,
          'salary': salary,
          'family': {'children': [['Alex', 24], ['Kate', 12]],
                     'u_salary_1_5_year': salary * 4}
          }

=========

endpoint_8: user_info_4
method: POST
form_params: 
   1) age (int)
   2) name (str)
   3) salary (int)

response: 
result = {'name': name,
          'age': int(age),
          'salary': [salary, str(salary * 2.5), str(salary * 3.5)]}






Задание.
1) Выполнить в Postman endpoints 1,2,7,8.
2) Сделать репозиторий в Гит
3) Склонировать репозиторий на локальный компьютер.
4) Експортировать тесты endpoints 1,2,7,8 и окружение в папку git склонированного репозитория.
5) Запушить тесты на внешний репозиторий
6) Сделать в GIT отдельную ветку.
7) Сделать тесты ендроинтов 3, 6 в Postman
8) Кспортировать тесты в новую, созданную ветку GIT.
9) Запушить новую ветку на внешний репозиторий. Тесты должны появиться на внешнем репозитории созданной в ветке
10) Вмержить изменения новой ветки в основную.
11) Запушить изменения основной ветки на внешний репозиторий.
12) Сделать в GIT отдельную ветку.
13) Сделать тесты ендроинтов 4,5 в Postman
14) Экспортировать тесты в созданную ветку GIT.
15) Запушить новую ветку на внешний репозиторий. Тесты должны появиться на внешнем репозитории созданной в ветке.
16) Вмержить изменения ветки в основную ветку.
17) Запушить изменения основной ветки на внешний репозиторий.
