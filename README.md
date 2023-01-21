public class Result {
    public static void main(String[]rags)
    {
        Scanner sc=new Scanner(System.in);
        int x1=sc.nextInt();
        int v1=sc.nextInt();
        int x2=sc.nextInt();
        int v2=sc.nextInt();
        for(int i=0;i<10000;i++)
        {
            x1=x1+v1;//2+1=3
            x2=x2+v2;//1+2=3
            if(x1==x2)//3==3
            {
                System.out.println("YES");
                System.exit(0);
            }
        }
        System.out.println("NO");
    }
}
