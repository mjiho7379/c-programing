#include <stdio.h>

#define MAX_PRODUCTS 100

int main() {
    int n; 
    int stock[MAX_PRODUCTS];    
    int sold[MAX_PRODUCTS];     
    int inventory[MAX_PRODUCTS];
    int id;


    printf("상품 개수를 입력하세요: ");
    scanf("%d", &n);

    printf("입고 수량을 입력하세요: ");
    for (int i = 0; i < n; i++) {
        scanf("%d", &stock[i]);
    }

    printf("판매 수량을 입력하세요: ");
    for (int i = 0; i < n; i++) {
        scanf("%d", &sold[i]);
    }

    for (int i = 0; i < n; i++) {
        inventory[i] = stock[i] - sold[i];
    }

    
    printf("조회할 상품 ID를 입력하세요: ");
    scanf("%d", &id);

    printf("%d\n", inventory[id - 1]);

    for (int i = 0; i < n; i++) {
        printf("%d ", inventory[i]);
    }
    printf("\n");

    return 0;
}
