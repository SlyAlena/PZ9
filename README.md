# PZ9

![Alt text](URL_to_image "Optional title")
<img width="1268" height="415" alt="Снимок экрана (23)" src="https://github.com/user-attachments/assets/986402ed-09ba-4469-a1aa-0493059be776" />

Задание 1

    #include <iostream>
    using namespace std;

    int main() {
    setlocale(LC_ALL, "Russian");

    int n;
    cin >> n;

    // Ваш код:
    switch(n) {
        case 1:  cout << "Один"; break;
        case 2: cout << "Два" ; break;
        case 3: cout << "Три" ; break;
        default: cout << "Ошибка";
    }


    return 0;
    }

Задание 2

    #include <iostream>
    using namespace std;

    int main() {
    setlocale(LC_ALL, "Russian");

    int n;
    cin >> n;

    // Ваш код:
    switch(n) {
        case 1: cout << "Понедельник"; break;
        case 2: cout << "Вторник"; break;
        case 3: cout << "Среда"; break;
        case 4: cout << "Четверг"; break;
        case 5: cout << "Пятница"; break;    
        case 6: cout << "Суббота"; break;
        case 7: cout << "Воскресенье"; break;
        default: cout << "Неверный день";
    }


    return 0;
    }
    
Задание 3

    #include <iostream>
    using namespace std;

    int main() {
    setlocale(LC_ALL, "Russian");

    int n;
    cin >> n;

    // Ваш код:
    switch(n) {
        case 12:
        case 1:
        case 2:
            cout << "Зима"; break;
        case 3:
        case 4:
        case 5:
            cout << "Весна"; break;
        case 6:
        case 7:
        case 8:
            cout << "Лето"; break;
        case 9:
        case 10:
        case 11:
            cout << "Осень"; break;
            
        default: cout << "Ошибка";
    }
               
      

    return 0;
    }

Задание 4

    #include <iostream>
    using namespace std;

    int main() {
    setlocale(LC_ALL, "Russian");

    char op;
    int a, b;
    cin >> op >> a >> b;

    // Ваш код:
    switch(op) {
        case '+':
            cout << a + b; break;
        case '-':
            cout << a - b; break;
        case '*':
            cout << a * b; break;
        case '/':
            if(b == 0) cout << "Деление на ноль";
            else cout << a / b; break;
        
        default: cout << "Ошибка"; break;
    }


    return 0;
    }

Задание 5

    #include <iostream>
    using namespace std;

    int main() {
    setlocale(LC_ALL, "Russian");

    int n;
    cin >> n;

    // Ваш код:
    switch(n) {
        case 5: cout << "Отлично"; break;
        case 4: cout << "Хорошо"; break;
        case 3: cout << "Удовлетворительно"; break;
        case 2:
        case 1:
            cout << "Плохо"; break;
        default: cout << "Ошибка";
    }
            
            


    return 0;
    }

Задание 6

    #include <iostream>
    using namespace std;

    int main() {
    setlocale(LC_ALL, "Russian");

    int n;
    cin >> n;

    // Ваш код:
    switch(n) {
        case 0: cout << "Ноль"; break;
        case 1: cout << "Один"; break;
        case 2: cout << "Два"; break;
        case 3: cout << "Три"; break;
        case 4: cout << "Четыре"; break;
        case 5: cout << "Пять"; break;
        case 6: cout << "Шесть"; break;
        case 7: cout << "Семь"; break;
        case 8: cout << "Восемь"; break;
        case 9: cout << "Девять"; break;
        default: cout << "Ошибка";
    }
        
           


    return 0;
    }

Задание 7

    #include <iostream>
    using namespace std;

    int main() {
    setlocale(LC_ALL, "Russian");

    int a, b;
    int op;
    cin >> a >> b >> op;

    // Ваш код:
    switch(op) {
        case 1:
            cout << a + b; break;
        case 2:
            cout << a - b; break;
        case 3:
            cout << a * b; break;
        case 4:
            if(b == 0) cout << "Деление на ноль";
            else cout << a / b; break;
        
        default: cout << "Ошибка"; break;
    }



    return 0;
    }
      
    
