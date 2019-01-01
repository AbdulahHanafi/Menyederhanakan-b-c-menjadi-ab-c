# Menyederhanakan-b-c-menjadi-ab-c


codingam program lengkap

    #include<stdio.h>
    using namespace std;
    void pecahan ();
    main ()
    {
    pecahan ();
    }
    void pecahan ()
    {
    int a,b,l,t;
    printf("== Menyederhanakan Bilangan Pecahan ==\n\n");
    printf(" masukan Pembilang : ");
    scanf ("%d", &a);
    printf(" masukan Penyebut : ");
    scanf ("%d", &b);
    t=a/b;
    l=a%b;
    if (a%b==0)
        printf ("Bilangan (%d/%d)\n disederhanakan Menjadi %d",a,b,t);
    else if (a%b !=0)
        printf (" Bilangan (%d/d%)\n Disederhanakan Menjadi (%d/%d)",a,b,t,l,b);
    }
    
hasil program

![img](https://github.com/AbdulahHanafi/Menyederhanakan-b-c-menjadi-ab-c/blob/master/menyederhanakan%20bc%20menjadi%20abc.png?raw=true)
