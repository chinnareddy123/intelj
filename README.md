// JAVA STRINGS 

//FileName: CharAtExample.java

public class CharAtExample{  
public static void main(String args[]){  
String name="javatpoint";  
char ch=name.charAt(4);
}} 


//FileName: CompareToExample2.java

public class CompareToExample2{  
public static void main(String args[]){  
String s1="hello";  
String s2="";  
String s3="me";  
System.out.println(s1.compareTo(s2));  
System.out.println(s2.compareTo(s3));  
}}  

//FileName: ConcatExample.java

public class ConcatExample{    
public static void main(String args[]){    
String s1="java string";    
s1.concat("is immutable");    
System.out.println(s1);    
s1=s1.concat(" is immutable so assign it explicitly");    
System.out.println(s1);    
}}  

//FileName: ContainsExample.java

class ContainsExample{  
public static void main(String args[]){  
String name="what do you know about me";  
System.out.println(name.contains("do you know"));  
System.out.println(name.contains("about"));  
System.out.println(name.contains("hello"));  
}}  

//FileName: EndsWithExample.java

public class EndsWithExample{  
public static void main(String args[]){  
String s1="java by javatpoint";  
System.out.println(s1.endsWith("t"));  
System.out.println(s1.endsWith("point"));  
}}  

//FileName: EqualsExample.java

public class EqualsExample{  
public static void main(String args[]){  
String s1="javatpoint";  
String s2="javatpoint";  
String s3="JAVATPOINT";  
String s4="python";  
System.out.println(s1.equals(s2));
System.out.println(s1.equals(s3));  
System.out.println(s1.equals(s4));
}} 

//FileName: EqualsIgnoreCaseExample.java

public class EqualsIgnoreCaseExample{  
public static void main(String args[]){  
String s1="javatpoint";  
String s2="javatpoint";  
String s3="JAVATPOINT";  
String s4="python";  
System.out.println(s1.equalsIgnoreCase(s2)); 
System.out.println(s1.equalsIgnoreCase(s3));
System.out.println(s1.equalsIgnoreCase(s4));
}}  

//FileName:Java String format()

public class FormatExample{  
public static void main(String args[]){  
String name="sonoo";  
String sf1=String.format("name is %s",name);  
String sf2=String.format("value is %f",32.33434);  
String sf3=String.format("value is %32.12f",32.33434);  
System.out.println(sf1);  
System.out.println(sf2);  
System.out.println(sf3);  
}}  

//FileName: StringGetBytesExample.java

public class StringGetBytesExample{  
public static void main(String args[]){  
String s1="ABCDEFG";  
byte[] barr=s1.getBytes();  
for(int i=0;i<barr.length;i++){  
System.out.println(barr[i]);  
}  
}}  

//FileName: StringGetCharsExample.java

public class StringGetCharsExample{  
public static void main(String args[]){  
 String str = new String("hello javatpoint how r u");  
      char[] ch = new char[10];  
      try{  
         str.getChars(6, 16, ch, 0);  
         System.out.println(ch);  
      }catch(Exception ex){System.out.println(ex);}  
}}  

//FileName: IndexOfExample.java

public class IndexOfExample{  
public static void main(String args[]){  
String s1="this is index of example";  
int index1=s1.indexOf("is");
int index2=s1.indexOf("index");
System.out.println(index1+"  "+index2);  
int index3=s1.indexOf("is",4); 
System.out.println(index3);
int index4=s1.indexOf('s');
System.out.println(index4); 
}}  

//FileName: InternExample.java

public class InternExample{  
public static void main(String args[]){  
String s1=new String("hello");  
String s2="hello";  
String s3=s1.intern();
System.out.println(s1==s2);
System.out.println(s2==s3);
}}  

//FileName: StringIsEmptyExample.java

public class IsEmptyExample{  
public static void main(String args[]){  
String s1="";  
String s2="javatpoint";  
System.out.println(s1.isEmpty());  
System.out.println(s2.isEmpty());  
}}  

//FileName: StringJoinExample.java

public class StringJoinExample{  
public static void main(String args[]){  
String joinString1=String.join("-","welcome","to","javatpoint");  
System.out.println(joinString1);  
}}  

//FileName: LastIndexOfExample.java

public class LastIndexOfExample2 {  
    public static void main(String[] args) {  
        String str = "This is index of example";  
        int index = str.lastIndexOf('s',5);  
        System.out.println(index);        
    }  
}  

//FileName: LengthExample.java

public class LengthExample{  
public static void main(String args[]){  
String s1="javatpoint";  
String s2="python";  
System.out.println("string length is: "+s1.length()); 
System.out.println("string length is: "+s2.length());
}}  

//FileName: ReplaceExample1.java

public class ReplaceExample1{  
public static void main(String args[]){  
String s1="javatpoint is a very good website";  
String replaceString=s1.replace('a','e');
System.out.println(replaceString);  
}}  

//FileName: ReplaceAllExample1.java

public class ReplaceAllExample1{  
public static void main(String args[]){  
String s1="javatpoint is a very good website";  
String replaceString=s1.replaceAll("a","e");
System.out.println(replaceString);  
}}  

//FileName:Java String split() method example

public class SplitExample{  
public static void main(String args[]){  
String s1="java string split method by javatpoint";  
String[] words=s1.split("\\s");
for(String w:words){  
System.out.println(w);  
}  
}}  

//FileName: StartsWithExample.java

public class StartsWithExample  
{    
public static void main(String args[])  
{    
String s1="java string split method by javatpoint";    
System.out.println(s1.startsWith("ja")); 
System.out.println(s1.startsWith("java string"));   
System.out.println(s1.startsWith("Java string"));  
}  
}

//FileName: SubstringExample.java

public class SubstringExample{  
public static void main(String args[]){  
String s1="javatpoint";  
System.out.println(s1.substring(2,4));
System.out.println(s1.substring(2));
}}

//FileName:Java String toCharArray() method example

public class StringToCharArrayExample{  
public static void main(String args[]){  
String s1="hello";  
char[] ch=s1.toCharArray();  
for(int i=0;i<ch.length;i++){  
System.out.print(ch[i]);  
}  
}}  

//FileName:Java String toLowerCase() method example

public class StringLowerExample{  
public static void main(String args[]){  
String s1="JAVATPOINT HELLO stRIng";  
String s1lower=s1.toLowerCase();  
System.out.println(s1lower);  
}}  

//FileName:Java String toUpperCase() method example

public class StringUpperExample{  
public static void main(String args[]){  
String s1="hello string";  
String s1upper=s1.toUpperCase();  
System.out.println(s1upper);  
}}  

//FileName: StringTrimExample.java

public class StringTrimExample{  
public static void main(String args[]){  
String s1="  hello string   ";  
System.out.println(s1+"javatpoint"); 
System.out.println(s1.trim()+"javatpoint"); 
}}  

//FileName:Java String valueOf(boolean bol) Method Example

public class StringValueOfExample2 {  
    public static void main(String[] args) {          
        boolean bol = true;    
        boolean bol2 = false;    
        String s1 = String.valueOf(bol);    
        String s2 = String.valueOf(bol2);  
        System.out.println(s1);  
        System.out.println(s2);  
    }  
}  
