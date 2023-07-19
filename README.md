#include<stdio.h>
int main(){
        int num[]={12,21,45,75,34,89,45,67};

        int value;
        int pos =-1,i;

        printf("enter the value:");
        scanf("%d",&value);

        for(i=0;i<8;i++){
            if(value==num[i]){
                pos = i+1;
                break;
            }
        }
        if(pos==-1){
            printf("item is not found");
        }else{
            printf("the value position is %d",pos);
        }
        return 0;

}
    
