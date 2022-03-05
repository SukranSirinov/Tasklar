# Tasklar
Console.WriteLine("Hello, World!");
string text = "Proqramlaşdırma çox vaxt tələb edir insandan";
char search = 'a';
byte count = 0;
for(int j=0;j<text.Length;j++)
{
    if(text[j]==search)
    {
        count++;
        Console.WriteLine("Metnin {j++} ci herfi {search}-a beraberdir");
        
    }
    Console.WriteLine("Metnde{0} eded {1} xarakteri var", count, search);
}
//Son
