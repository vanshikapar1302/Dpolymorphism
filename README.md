# Dpolymorphism
class A1{
    void m1(){
    System.out.println("Coming from m1");
    }
}
class B1 extends A1{
     void m2(){
    System.out.println("Coming from m2");
    }
}

    public class dpoly {
    public static void main(String[] args) {
        System.out.println("A");
        A1 b1=new B1();
        b1.m1();


    }
    
}
