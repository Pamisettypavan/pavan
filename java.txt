package JavaConcepts;

public class forLoop {
    public static void main(String[] args){
        for(int i=1;i<=5;i++){
            System.out.println("hello world!!");
        }
        System.out.println("Out of for loop");
        for(int i=5;i>0;i--){
            System.out.println(i);
        }
        System.out.println("========");
        for(int i=2;i<=20;i=i+2){
            System.out.println(i);
        }
        System.out.println("========");
        for(int i=5;i<=50;i=i+5){
            System.out.println(i);
        }
        System.out.println("===============");
        for(int i=0;i<2;i++){
            for(int j=0;j<4;j++){
                System.out.println(i+","+j);
            }
        }
    }

}
