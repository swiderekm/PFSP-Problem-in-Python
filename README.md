<h1>Permutation flowshop scheduling problem</h1></br>

馃嚨馃嚤 Celem projektu jest odnalezienie kolejno艣ci zada艅, przy kt贸rej czas wykonania zada艅 na danych maszynach jest najkr贸tszy. Do znalezienia rozwi膮zania u偶yty zostanie algorytm iteracyjnej wspinaczki. Projekt realizowany jest w ca艂o艣ci w j臋zyku Python i zosta艂 napisany na podstawie programu dla problemu komiwoja偶era.</br>
Ograniczeniami, z kt贸rym si臋 mierzymy, s膮: wszystkie poprzednie kroki musz膮 zosta膰 sko艅czone oraz odpowiednia maszyna musi by膰 wolna. Na podstawie czasu potrzebnego do wykonania poprzednich krok贸w i do zwolnienia si臋 maszyny, obliczany jest czas, kt贸ry minie od rozpocz臋cia procesu do danego zadania. W zale偶no艣ci od tego, w jakiej kolejno艣ci u艂o偶ymy zadania, ostateczny czas mo偶e si臋 r贸偶ni膰.</br>
Do uruchomienia projektu niezb臋dne jest pobranie pakiet贸w: 'numpy', 'openpyxl', 'pandas'.</br>
Do projektu do艂膮czony jest przyk艂adowy plik z excela: 'data_PFSP_20_10.xlsx', kt贸ry zawiera 20 zada艅 oraz 10 maszyn.</br>
Wykorzystywane parametry w projekcie: liczba iteracji, maksymalna liczba iteracji bez poprawy, maksymalna liczba utworzonych s膮siedztw, maksymalna liczba utworzonych s膮siedztw w ci膮gu 1 iteracji.</br></br>


馃嚞馃嚙 The main goal of this project is to find the order for which the execution time will be the shortest possible. To find the result we will use hill climbing alghoritm. The project is fully written in Python and is based on the TSP Problem. </br>
The restriction encountered the project: previous steps have to be completed and specific machine has to be available for use. Based on the time needed to complete previous tasks and machines exempted from the usage there is calculated time which will pass form the beginning of specific task. Depending on the order of the tasks the final result might differ.</br>
To use the program it is essential to download packages: 'numpy', 'openpyxl', 'pandas'.</br>
There is sample Excel file attached: 'data_PFSP_20_10.xlsx' which contains 20 tasks and 10 machines.</br>
Parameters included in this project: number of iterations, maximum number of iteration without improvement of the result, maximum number of created neighbourhoods, maximum number of created neighbourhoods in one iteration.
