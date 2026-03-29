#include <iostream>
using namespace std;

int main()
{
    int number;
    int sum = 0;

    std::cout << "Введите целые числа (для завершения введите 0):" << std::endl;

    do 
    {
        std::cin >> number; >> std::endl;
        sum += number;
     while (number != 0);
    }
    std::cout << "Сумма введённых чисел: " << sum << std::endl;

    return 0;
}


while 
{
    int number;
    int sum = 0;

    std::cout << "Введите целое число: "; << std::endl;
    std::cin >> number; >> std::endl;
    
    int temp = abs(number);

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

    std::cout << "Сумма цифр числа " << number << " равна: " << sum << std::endl;

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
