import java.util.Scanner;
class Calculator {
    public static void main(String[] args) {
        int a;
        char op;
        int b;
        int ans;
        Scanner scan = new Scanner(System.in);
        a = scan.nextInt();
        op = scan.next().charAt(0);
        b = scan.nextInt();
        if(a < 10 && a >= 0);
        else System.exit(0);
        if(b < 10 && b >= 0);
        else System.exit(0);
        switch(op) {
            case '+': ans = a + b;
                break;
            case '-': ans = a - b;
                break;
            case '*': ans = a * b;
                break;
            case '/': ans = a / b;
                break;
            default:
                return;
        }
        System.out.print( "= " + ans);
    }
}
