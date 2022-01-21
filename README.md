<h1 style="text-align: center;">
Hello World..
</h1>
<p> 
I am Debayan Roy
<br>
<h1>Welcome to my Github Profile</h1>

```java
public class Myself
{
  public enum My 
  {
    about("This is my bio data");
    public enum Name
    {
      firstName("Debayan"), 
      lastName("Roy"), 
      userName("dbynroy6");
      private String s; 
      Name(String s)
      {
        this.s = s;
      }
    }
    public enum Favourite
    {
      food("Anything"),
      drink("Coffee"),
      pLang("Java"),
      subj("Maths");
      private String s;
      Favourite(String s)
      {
        this.s = s;
      }
    }
    public enum Interests
    {
      i1("Programming"),
      i2("Advanced Calculus"),
      i3("Electric Circuits"),
      i4("Blackholes"),
      i5("Aerodynamics"),
      i6("Football");
      private String s;
      Interests(String s)
      {
        this.s = s;
      } 
    } 
    private String s;
    My(String s)
    {
      this.s = s;
    }
  }
  public static void main(String[] args)
  {
    String s = My.Favourite.pLang.s;
    System.out.println(s);
  }
}
```
<hr>
<hr>
<hr>

