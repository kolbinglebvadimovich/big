#include <iostream>
using namespace std;

int main()
{
    int number;
    int sum = 0;

    cout << "Введите целые числа (для завершения введите 0):" << endl;

    do 
    {
        cin >> number;
        sum += number;
     while (number != 0);
    }
    cout << "Сумма введённых чисел: " << sum << endl;

    return 0;
}


while 
{
    int number;
    int sum = 0;

    cout << "Введите целое число: ";
    cin >> number;
    
    int temp = abs(number);

    // Если ввели 0, сумма цифр тоже 0
    if (temp == 0) 
    {
        sum = 0;
    }
     else 
    {  while (temp > 0) 
        {
            sum += temp % 10;
            temp /= 10;
        }
    }

    cout << "Сумма цифр числа " << number << " равна: " << sum << endl;

    return 0;
}
while do
{
    int number;

    std::cout << "Введите целое число для таблицы умножения: " << std::endl;
    std::cin >> number; >> std::endl;

    std::cout << "\nТаблица умножения для числа " << number << ":\n"; << std::endl;
    std::cout << "--------------------------------\n"; << std::endl;

    // Выводим таблицу умножения от 1 до 10
    for (int i = 1; i <= 10; ++i) 
    {
       std::cout << number << " × " << i << " = " << (number * i) << std::endl;
    }

    return 0;
}
