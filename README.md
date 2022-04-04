# Switch-Case
int month = DateTime.Now.Month;
            switch (month)// Expression -Kontrol etmek isteğimiz koşulu
            {
                case 1:
                    Console.WriteLine("Ocak ayındasınız:");
                    break;
                    case 2:
                    Console.WriteLine("Şubat ayındasınız:");
                    break;
                case 3:
                    Console.WriteLine("Mart ayındasınız:");
                    break;
                case 4:
                    Console.WriteLine("Nisan ayındasınız:");
                    break;

                default:
                    Console.WriteLine("Yanlış veri girdiniz:");
                    break;
            }
            switch (month)
            {
                case 12:
                case 1:
                case 3:
                    Console.WriteLine("Kış ayındasınız.");
                    break;


                default;
                    break;
            }
        }
    }
