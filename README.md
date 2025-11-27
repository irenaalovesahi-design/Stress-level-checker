# Stress-level-checker
#include <stdio.h>

int main() {
    int bpm;

    printf("=== Aplikasi Penentu Tempo Musik ===\n");
    printf("Masukkan BPM (Beat Per Minute): ");
    scanf("%d", &bpm);

    printf("\nKategori Tempo: ");

    if (bpm <= 40) {
        printf("Grave (sangat lambat)\n");
    }
    else if (bpm <= 60) {
        printf("Largo (lambat)\n");
    }
    else if (bpm <= 76) {
        printf("Adagio (lebih lambat)\n");
    }
    else if (bpm <= 108) {
        printf("Andante (sedang)\n");
    }
    else if (bpm <= 120) {
        printf("Moderato (agak cepat)\n");
    }
    else if (bpm <= 168) {
        printf("Allegro (cepat)\n");
    }
    else if (bpm <= 200) {
        printf("Presto (sangat cepat)\n");
    }
    else {
        printf("Prestissimo (super cepat)\n");
    }

    printf("\nTerima kasih telah menggunakan program!\n");
    return 0;
}
