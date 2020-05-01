    #include <stdio.h>
    #include <stdlib.h>

    int main() {
    
    int yaricap;
    int merkezaci;
    float alan;
    float pi= 3.14;

    printf("Yaricap degerini giriniz: ");
    scanf("%d", &yaricap);

    printf("Merkez aci degerini giriniz: ");
    scanf("%d", &merkezaci);

    printf("-------------------------------\n");

    alan= (merkezaci*yaricap*yaricap*pi)/360;

    printf("Acinin taradigi alan %f santimetrekaredir.", alan);

    return 0; }
