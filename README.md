class Program
    {
        static void Main(string[] args)
        {
            string name = "Иван";
            string surname = "Иванов";
            char cr = '!';
            char ch = ',';
            char space = ' ';
            byte age = 10;
            uint nomberInList = 23452;
            short seriaPasport = 1987; 
            uint pasport = 315456;
            float money = 21.5f;
            double growth = 73.40;
            decimal weight = 70.15m;
            bool married = true;

            Console.WriteLine($"Меня зовут {surname}{space}{name}{cr}, мне {age} лет. \n" +
                $"Паспорт: {seriaPasport}{space}{pasport}\n" +
                $"У меня денег: {money}\n" +
                $"Мой рост: {growth}{ch} и вес: {weight},\n" +
                $"Состою ли я в браке:{married}\n" +
                $"Мой номер в списке {nomberInList}");

        }

    }
