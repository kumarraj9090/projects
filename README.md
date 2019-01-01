# projects
Amazing codes
import java.io.*;
import java.util.*;

public class Solution {

    public static void main(String[] args) {
        Scanner scan=new Scanner(System.in);
        int t=scan.nextInt();
        String e="",o="";
        String s[]=new String[t];
        //String s[]="Rank";
        for(int i=0;i<t;i++)
        {
s[i]=scan.next();
char ch[]=s[i].toCharArray();
for(int j=0;j<s[i].length();j++)
{
    if(j%2==0)
    {
        e+=ch[j];
    }
    else
    {
        o+=ch[j];
    }
}
        
        System.out.println(e+" "+o);
        e="";o="";
           }
    }
}

