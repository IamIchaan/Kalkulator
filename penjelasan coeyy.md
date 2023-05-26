         boolean out = true;
         do{
         Scanner input = new Scanner(System.in);
         int bil1, bil2, pil ,hasil = 0;
         System.out.println("PROGRAM JAVA KALKULATOR SEDERHANA");
         System.out.println("1. Perkalian");
         System.out.println("2. Pembagian");
         System.out.println("3. Penjumlahan");
         System.out.println("4. Pengurangan");
         System.out.println("----------------------------");
         System.out.print("Bilangan 1 : ");
         bil1=input.nextInt();
         System.out.print("Bilangan 2 : ");
         bil2=input.nextInt();
         System.out.print("Pilihan Operasi: ");
         pil=input.nextInt();
         
         switch (pil){
             case 1 : hasil=bil1*bil2;break;
             case 2 : hasil=bil1/bil2;break;
             case 3 : hasil=bil1+bil2;break;
             case 4 : hasil=bil1-bil2;break;
             default : System.out.println("Salah memasukan pilihan");
         }
         
          System.out.println("Hasil :"+hasil);
            System.out.println("afkh mwu lanjut? [True]/[False]");
            System.out.print("Input = ");
            out = input.nextBoolean();
    }while(out);
        System.out.println("Turu");
        }
PENJELASAN COEYY
KEGUNAAN PADA BARISAN 1 ATAU boolean out = true;
itu sangat penting dijadikan sebagai Error Handle buat JS jadi tidak bisa error.
Untuk Kegunaan do{
                  }while(out) itu digunakan sebagai perloopingan atau perngulangan jadi kalo
                  mislanya salah input, itu bisa diulangin lagi asalkan harus ada true/false(boolean)
untuk true digunakan sebagai melanjutkan/menjalankan java tsb, sedangkan false digunakan sebagai menghentikan sistem java tsb
moga paham :3
