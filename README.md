# demo
Me gusta el maní, solo estoy probando ésta wea de cosa
Alvaro Uribe Culpable 
fdfdfsdf
wgfr3gr3
s
fs
gf
wrg
r
g
r
import java.util.Scanner;
public class Main12 {
    public static void main(String[] args) {

        Scanner ver= new Scanner(System.in);
        int N= ver.nextShort();
        System.out.println(N);
        while(N > 1){
            if(N%2==0) {
                N = N / 2;
                System.out.println(N);
            }
            else {
                N=3*N+1;
                System.out.println(N);

            }
        }

    }
}
