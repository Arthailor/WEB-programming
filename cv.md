# Curriculum Vitae

![Photo](https://sun9-30.userapi.com/impg/TYUEQHoBARd_ANzVo5lMfk8Eou2PiUuqoERQCw/hUBTnukOCdE.jpg?size=608x1080&quality=95&sign=e130ee7d0c8fdfdbcde3b9f5fc65fe46&type=album)

## 1. Name
Osmolovskiy Denis

## 2. Contact Information
- Phone: +375293297403
- Email: denart020@gmail.com
- Contacts: [VK](https://vk.com/termexr)

## 3. About Me
Well I am a Belarusian-Russian University student with a passion for programming and a strong interest in the English language. I am committed to improving my programming skills and enhancing my English proficiency, driven by a thirst for knowledge and a desire to excel. With ambition and dedication, i am poised to make a significant impact in my chosen fields.

## 4. Skills
- Programming Languages: Java, C#
- Web Development: HTML/CSS, JavaScript
- Version Control: Git
- Development Tools: Visual Studio Code, IntelliJ IDEA

## 5. Code Examples

C#

static void Main(string[] args)
        {
           try
           {
                string text1,text2;
                 using (FileStream fs = new FileStream("data.bin", FileMode.Open))
                 {
                     using (BinaryReader br = new BinaryReader(fs, Encoding.Default))
                     {
                         text1 = br.ReadString();
                         text2 = br.ReadString();
                         Console.WriteLine("Результаты предыдущего раза");
                         Console.WriteLine(text2);
                         Console.WriteLine();
                         Console.WriteLine("Исходный текст");
                         Console.WriteLine(text1);
                     }
                 }
                Console.WriteLine();
               Console.WriteLine("Введите символ который хотите заменить");
               char c1 = char.Parse(Console.ReadLine());
                Console.WriteLine();
               Console.WriteLine("Введите символ которым хотите заменить");
               char c2 = Convert.ToChar(Console.ReadLine());
               text2 = text1.Replace(c1, c2);
               Console.WriteLine("Итог - "+text2);
               Console.ReadKey();
                using (FileStream fs = new FileStream("data.bin", FileMode.Create))
                {
                    using (BinaryWriter bw = new BinaryWriter(fs, Encoding.Default))
                    {
                        bw.Write(text1);
                        bw.Write(text2);
                    }
                }
           }    
           catch
           {
               Console.WriteLine("Ошибка");
           }
        }

## 6. Courses and Training
1. Introduction to Programming
1. Web Development Bootcamp
1. Java Fundamentals

## 7. Languages
Fluent in written and spoken Russian.
Fluent in written English.

---