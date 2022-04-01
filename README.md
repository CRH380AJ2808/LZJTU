# LZJTU
//[P58 例3.4]
#include<math.h>
int main()
{
    double a, b, c, s, area;
    a = 3.67;
    b = 5.43;
    c = 6.21;
    s = (a + b + c) / 2;
        area = sqrt(s * (s - a) * (s - b) * (s - c));
    printf("a=%f\tb=%f\t\n", a, b, c);
    printf("area=%f\n", area);

    return 0;
}
