#include <stdio.h>

int main(){

printf("-------------------------------\n");
printf(" CHUONG TRINH TINH DIEM TRUNG BINH \n");
float toan, ly, hoa, dtb;

printf(" Nhap diem toan: ");
scanf("%f", &toan);

printf(" Nhap diem ly: ");
scanf("%f", &ly);

printf(" Nhap diem hoa: ");
scanf("%f", &hoa);

dtb = ( toan * 3 + ly * 2 + hoa )/6;
printf(" Diem trung binh la: %.2f", dtb);

printf("\n");
printf("-------------------------------\n");
printf(" TOI LA THU KHOA NAM 2025");
    return 0;
}