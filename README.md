# 7-fer
 // Функція, що перетворює рядок у масив байтів
 private byte[] ToBytes(string s)
 {
     UnicodeEncoding enc = new UnicodeEncoding();
     return enc.GetBytes(s);
 }
