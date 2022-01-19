  int lastDigit(int a, int b)
{
    if (b==0) return 1;
    a%=10;
    b%=4;
    int last2[]={6,2,4,8};
    int last3[]={1,3,9,7};
    int last4[]={6,4};
    int last7[]={1,7,9,3};
    int last8[]={6,8,4,2};
    int last9[]={1,9};
    switch (a)
    {
        case 2:return last2[b];break;
        case 3:return last3[b];break;
        case 4:return last4[b%2];break;
        case 7:return last7[b];break;
        case 8:return last8[b];break;
        case 9:return last9[b%2];break;
        default:
        //Trường hợp tận cùng là 0,1,5,6
        return a;
    }
}
