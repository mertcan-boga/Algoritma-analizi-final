# Algoritma-analizi-final
import java.util.*;
public class soru6 {

static void sayibul(ArrayList<Integer> dizi){
	int enbuyuk=0;
	int sayac=0;
	int n=dizi.size();
	for(int i=0;i<n;i++){
		if(dizi.get(i)==0){
			sayac=sayac+1;
			enbuyuk=sayac;
		}
		else if(dizi.get(i)==1){	
				if(sayac>enbuyuk){
				enbuyuk=sayac;}
			sayac=0;
			
		}		
	}	
	System.out.print("Ard arda en cok gelen sıfır sayısı:");
	System.out.print(enbuyuk);
}
	
	
	
public static void main(String[] args) {

	Scanner tara=new Scanner(System.in);
	ArrayList<Integer> dizi=new ArrayList<Integer>();
	System.out.println("Sayı Giriniz");
	dizi.add(tara.nextInt());

	while(dizi.get(dizi.size() - 1)!=2){
	System.out.println("Sayı Giriniz");
	dizi.add(tara.nextInt());
}

	int n=dizi.size();
	soru6 sonuc =new soru6() ;
	int c;
	sonuc.sayibul(dizi);
	
}
}
