#define _CRT_SECURE_NO_WARNINGS

#include<stdio.h>

int main()

{

    int g = 0;
    
    while (scanf("%d", &g) != EOF)
    {
        for (int i = 0; i < g; i++)
        {

            for (int j = 0; j < i; j++)
            {
                printf(" ");
            }
            for (int j = 0; j < g - i; j++)
            {
                printf("* ");
            }
            printf("\n");
        }
    }
    
    return 0;
    
}


int main()//菱形

{

    int a = 0;
    int b = 0;
    int c = 0;
    int g = 0;
    while (scanf("%d", &g) != EOF)
    {
        g += 1;
        for (b = 1; b <= g ; b++)
        {
            for (a = 1; a <= g - b; a++)
            {
                printf(" ");
            }
            for (c = 1; c <= b; c++)
            {
                printf("* ");
            }
            printf("\n");
        }
        for (int i = 0; i < g - 1; i++)
        {
            for (int j = 0; j < i; j++)
            {
                printf(" ");
            }
            for (int j = 0; j < g - i - 1; j++)
            {
                printf(" *");
            }
            printf("\n");
        }
    }
    return 0;
    
}

int main()

{

    int a = 0;
    int b = 0;
    int g = 0;
    while (scanf("%d", &g) != EOF)
    {
        g += 1;
        for (b = g; b > 0; b--)
        {
            for (a = b; a > 0; a--)
            {
                printf("* ");
            }
            printf("\n");
        }
        for (b = 1; b <= g - 1; b++)
        {
            for (a = 0; a <= b; a++)
            {
                printf("* ");
            }
            printf("\n");
        }
    }
    
    return 0;
    
}


int main()

{

    int a = 0;
    int b = 0;
    int c = 0;
    int g = 0;
    while (scanf("%d", &g) != EOF)
    {
        for (b = 0; b <= g; b++)
        {
            for (a = 1; a <= g - b; a++)
            {
                printf("  ");
            }
            for (c = 0; c <= b; c++)
            {
                printf("*");
            }
            printf("\n");
        }
        for (b = 1; b <= g;b++)
        {
            for (c = 1; c <= b; c++)
            {
                printf("  ");
            }
            for (a = 0; a <= g - b; a++)
            {
                printf("*");
            }
            printf("\n");
        }
    }
    
    return 0;
    
}


int main()

{

    int a = 0;
    int b = 0;
    int c = 0;
    int g = 0;
    while (scanf("%d", &g) != EOF)
    {
        for (b = 1; b <= g; b++)
        {
            for (a = 1; a <= g - b; a++)
            {
                printf("  ");
            }
            for (c = 1; c <= b; c++)
            {
                printf("*");
            }
            printf("\n");
        }
        for (b = 1; b <= g - 1; b++)
        {
            for (c = 1; c <= b; c++)
            {
                printf("  ");
            }
            for (a = 1; a <= g - b; a++)
            {
                printf("*");
            }
            printf("\n");
        }
    }
    
    return 0;
}


int main()

{

    int a = 0;
    int b = 0;
    int g = 0;
    while (scanf("%d", &g)!=EOF)
    {
        printf("*\n");
        for (b = 1; b <= g - 1; b++)
        {
            for (a = 1; a <= b; a++)
            {
                printf(" ");
            }
            printf("*\n");
        }
    }
    
    return 0;
    
}

int main()

{

    int a = 0;
    int b = 0;
    int c = 0;
    int g = 0;
    while (scanf("%d", &g) != EOF)
    {
        for (b = 1; b <= g; b++)
        {
            for (a = 1; a <= g - b; a++)
            {
                printf(" ");
            }
            for (c = 1; c <= b; c++)
            {
                printf("* ");
            }
            printf("\n");
        }
    }
    return 0;
    
}


int main()

{

    int a = 0;
    int b = 0;
    int g = 0;
    while (scanf("%d", &g)!=EOF)
    {
        for (b = g - 1; b > 0; b--)
        {
            for (a = 1; a <= b; a++)
            {
                printf(" ");
            }
            printf("*\n");
        }
        printf("*\n");
    }
    
    return 0;
    
}

int main()

{

    int n = 0;
    //多组输入
    while (scanf(" %d", &n)!=EOF)//5
    {
        //控制行数
        for (int i = 0; i < n; i++)
        {
            //控制列
            for (int j = 0; j < n; j++)
            {
                if (i == j || i + j == n - 1)
                {
                    printf("*");
                }
                else
                {
                    printf(" ");
                }
            }
            printf("\n");
        }
    }

    return 0;
    
}

int main()

{

    int a = 0;
    int b = 0;
    int c = 0;
    int g = 0;
    while (scanf("%d", &g)!=EOF)
    {
        for (b = 1; b <= g; b++)
        {
            if (b == 1 || b == g)
            {
                for (a = 1; a <= g; a++)
                {
                    printf("* ");
                }
                printf("\n");
            }
            else
            {
                for (c = 1; c <= g; c++)
                {
                    if (c == 1 || c == g)
                    {
                        printf("* ");
                    }
                    else
                    {
                        printf("  ");
                    }
                }
                printf("\n");
            }
        }
        printf("\n");
    }
    
    return 0;
    
}

int main()

{

    int a = 0;
    int b = 0;
    int c = 0;
    int g = 0;
    while (scanf("%d", &g)!=EOF)
    {
        for (b = 1; b <= g; b++)
        {
            if (b == 1 || b == 2 || b == g)
            {
                for (a = 1; a <= b; a++)
                {
                    printf("* ");
                }
                printf("\n");
            }
            else
            {
                for (c = 1; c <= g - 1; c++)
                {
                    if (c == 1 || c == b)
                    {
                        printf("* ");
                    }
                    else
                    {
                        printf("  ");
                    }
                }
                printf("\n");
            }
        }
    }
    
    return 0;
    
}

int main()

{

    int a = 0;
    int b = 0;
    int g = 0;
    while (scanf("%d", &g) != EOF)
    {
        for (b = 1; b <= g; b++)
        {
            for (a = 1; a <= b; a++)
            {
                printf("%d ", b);
            }
            printf("\n");
        }
    }
    
    return 0;
    
}

int main()

{

    int a = 0;
    int b = 0;
    int g = 0;
    while (scanf("%d", &g)!=EOF)
    {
        for (b = 1; b <= g; b++)
        {
            for (a = 1; a <= b; a++)
            {
                printf("%d ", a);
            }
            printf("\n");
        }
    }
    
    return 0;
    
}
