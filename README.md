# mengubah-nilai-ke-huruf

    #include<stdio.h>
    #include<conio.h>
    int tukar (int nilai);
    int main (void)
    {
    int nilai ;
    printf ("masukkan nilai 1 sampai 4 : ");
    scanf ("%d",&nilai);
    tukar (nilai);
    getch();
    }
    int tukar (int nilai)
    {
    switch(nilai)
    {
    case 1 :
        printf(" nilai huruf : A");break;
    case 2 :
        printf(" nilai huruf : B");break;
    case 3 :
        printf(" nilai huruf : C");break;
    case 4 :
        printf(" nilai huruf : D");break;
    }
    return (nilai);
    }
    
![img](https://raw.githubusercontent.com/VIKTORKEVIN/mengubah-nilai-ke-huruf/master/nilai%20ke%20huruf.png)
