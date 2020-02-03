Завршни квиз
###########
Добро дошли на крај 2. модула. До самог краја дели те завршни тест! Срећно! :)

.. activecode:: ово је исправно написана наредба for:
    for i in range (1:7)
   		print(i)

   
   .. mchoice:: vrednost_izraza_1
   :answer_a: Јесте!
   :answer_b: Није!
   :correct: b
   :feedback_a: Нетачно!
   :feedback_b: Тачно!
   
   
   
  .. activecode:: ког типа је следећа вредност:
   12 > 15
   
.. mchoice:: vrednost_izraza_1
   :answer_a: integer
   :answer_b: float
   :answer_c: string
   :answer_d: boolean
   :correct: d
   :feedback_a: Нетачно!
   :feedback_b: Нетачно!
   :feedback_c: Нетачно!
   :feedback_d: Тачно!
  
  
  
  .. activecode:: шта је резултат извршавања следеће наредбе:
   if 12 > 3:
      print(12 / 3)
   else:
      print(12 + 3)
   
.. mchoice:: vrednost_izraza_1
   :answer_a: 4
   :answer_b: 15
   :answer_c: 8
   :answer_d: 4.0
   :correct: d
   :feedback_a: Нетачно!
   :feedback_b: Нетачно!
   :feedback_c: Нетачно!
   :feedback_d: Тачно!
  
   
   
  .. activecode:: шта је резултат извршавања следеће наредбе:
   skola.loc["treca"]
   
.. mchoice:: vrednost_izraza_1
   :answer_a: исписује се једна врта табеле
   :answer_b: исписује се једна колона табеле
   :answer_c: исписује се колона са индексима
   :answer_d: исписује се насумична колона
   :correct: a
   :feedback_a: Тачно!
   :feedback_b: Нетачно!
   :feedback_c: Нетачно!
   :feedback_d: Нетачно!
   
   
   
   
    .. activecode:: шта је резултат извршавања следеће наредбе:
   skole.columns
   
.. mchoice:: vrednost_izraza_1
   :answer_a: исписује се називи колона табеле
   :answer_b: исписује се једна колона табеле
   :answer_c: исписује се колона са индексима
   :answer_d: исписује се насумична колона
   :correct: a
   :feedback_a: Тачно!
   :feedback_b: Нетачно!
   :feedback_c: Нетачно!
   :feedback_d: Нетачно!
   
 
  .. activecode:: шта је резултат извршавања следећих наредби:
  <pre>
  t['porast'] = 0
  for i in t.index:
      t.at[i,'porast'] = t.at[i,'Број ученика - други разред'] - t.at[i,'Број ученика - први разред']
  </pre>
   
   
.. mchoice:: vrednost_izraza_1
   :answer_a: прави се нова колона
   :answer_b: прави се нова врста
   :answer_c: прави се нова колона и уписује се разлика између ученика 2. и 1. разреда.
   :answer_d: прави се нова врста и уписује се разлика између ученика 2. и 1. разреда.
   :correct: c
   :feedback_a: Нетачно!
   :feedback_b: Нетачно!
   :feedback_c: Тачно!
   :feedback_d: Нетачно!
   
      
	  
	  
	  .. activecode:: koja funkcija je definisana sledećim kodom?
   def ime(n, m):
       
   
.. mchoice:: vrednost_izraza_1
   :answer_a: sum(lista)
   :answer_b: mean(lista)
   :answer_c: max(lista)
   :correct: b
   :feedback_a: Нетачно!
   :feedback_b: Тачно!
   :feedback_c: Нетачно!


.. activecode:: Марија је је била неколико пута у набавци. У листи nabavke дат је број артикала који је купљен у свакој од набавки: nabavke = [22, 11, 33, 18, 71, 9], број набавки у којима је била
 Марија одређујемо следећом наредбом:
   
   
.. mchoice:: vrednost_izraza_1
   :answer_a: sum(nabavke)
   :answer_b: mean(nabavke)
   :answer_c: len(nabavke)
   :correct: c
   :feedback_a: Нетачно!
   :feedback_a: Нетачно!
   :feedback_c: Тачно!

