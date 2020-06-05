# reverse-string
     Public void reversewordinmystrong(stringstr)
     {
        String[] words=str.split("");
        String reverse string="";
        For (inti=0;I<words.length;I++)
         {
            String word=words[I];
            String reversewordinmystrong="";
            For(int j=word.length()-1;j>=0;j--)
            {
                Reverseword=reverseword+word.charAt(j);
            }
            Reversestring=reversestring+reverseword+"";
          }
           System.out.println(str);
           System.out.println(reversestring);
       }
      Public static void main(string[]args)
      {
         Obj.reversewordinmystring("Java");
         Obj.reversewordinmystring("this is an easy Java program");
      }
}
