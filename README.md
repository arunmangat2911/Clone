# Clone


import java.util.ArrayList;


public class JoinArrayList {
    
   public static void main(String[] args) {
       
       ArrayList<Integer> obj = new ArrayList<Integer>();
       obj.add(10);
       obj.add(20);
       obj.add(30);
       obj.add(40);
       obj.add(60);
       System.out.println(obj);
       
       ArrayList<Integer> obj1 = (ArrayList<Integer>)obj.clone();
       System.out.println(obj1);
       
       obj1.add(50);
       System.out.println(obj1);
       
   }
}
