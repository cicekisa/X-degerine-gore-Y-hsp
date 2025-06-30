// y= 3x² fonksiyonunda verilen x değerine göre y değerini bulunuz. (Örnek: x=2 ise y=12 olmalıdır.)
# X-degerine-gore-Y-hsp
#include <stdio.h>

int main(){
float x,y;
printf("hesaplanacak degeri giriniz:");
scanf("%f",&x);

y = 3 * (x * x);
printf("girilen degere gore hesaplanan deger: %f\n",y);


return 0;
}
