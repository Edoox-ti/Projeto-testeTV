# teste-televis-o
//Simulado de função para com uma televisão, junto à um controle remoto


package testetelevisão;

import javax.swing.JOptionPane;

//DECLARAÇÃO DE VARIAVEIS E TIPO DE DADOS

class Televisao {
int canal;
String marca;
float tamanho;
	
//ATRIBUIÇÃO DE METODO SEM RETORNO
	void aumentaCanal() {
		canal = canal + 1;
	}

 
 /ATRIBUIÇÃO DE METODO SEM RETORNO
	void abaixaCanal() {
		canal = canal - 1;
	}
	 /ATRIBUIÇÃO DE DADOS
	void imprimir() {
		JOptionPane.showMessageDialog(null,
			"Canal: " + canal + 
			"\nMarca: " + marca + 
			"\nTamanho: " + tamanho);
	}
}    



\n


//CLASSE PRINCIPAL

    
package testetelevisão;

public class TesteTelevisão {

public static void main(String[] args) {


//DECLARAÇÃO DE VARIAVEIS E TIPO DE DADOS


Televisao t1 = new Televisao();
		t1.canal = 18;
		t1.marca = "Samsung";
		t1.tamanho = 42;


//ATRIBUIÇÃO DE MEOTODOS


Televisao t2 = new Televisao();
		t2.canal = 10;
		t2.marca = "Panasonic";
		t2.tamanho = 47;
		
		t1.aumentaCanal();
		t1.aumentaCanal();
		t1.abaixaCanal();
		t1.abaixaCanal();
		t1.abaixaCanal();
		t1.abaixaCanal();
		
		t2.aumentaCanal();
		t2.aumentaCanal();
		t2.aumentaCanal();
		t2.aumentaCanal();
		t2.aumentaCanal();
		t2.abaixaCanal();
		t2.abaixaCanal();
	

//IMPRESSÃO DE DADOS


t1.imprimir();
		t2.imprimir();
		
		

	}
    
}
   
    


