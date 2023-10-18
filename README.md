# sixassignment
//Pyramid
int n;
    printf("How many rows:");
    scanf("%d",&n);
    
 int i,j,k;
 
    for(i=1;i<=n;i++){
        for(j=n;j>i;j--){
            printf(" ");
        } 
        
        for(k=1;k<=i;k++){
            printf("%d ",i);
        }printf("\n");
    }

//Diamond    
int n;
    printf("How many rows:");
    scanf("%d",&n);
    
    
    int i,j,k;
    for(i=1;i<=n;i++){
        for(j=n;j>i;j--){
            printf(" ");
        }
        
        for(k=1;k<=i;k++){
            printf("**");
        }printf("\n");
    }
    
    for(i=1;i<=n;i++){
        for(j=1;j<i;j++){
            printf(" ");
        }
        
        for(k=n;k>=i;k--){
            printf("**");
        }printf("\n");
    }

 
 
