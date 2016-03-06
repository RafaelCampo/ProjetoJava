# ProjetoJava
Projeto do KitPet

package Kitpet;

public class KitPet {
	
	String [] vacinas = new String[6];
	String ultimaIdaVet;
	String proximaIdaVet;
	String nomeAnimal;
	String raçaAnimal;
	double idadeAnimal;
	
	void mostrarInfo(){
	
		System.out.println("Nome do animal: "+nomeAnimal);
		System.out.println("Raça do animal: "+raçaAnimal);
		System.out.println("Idade  do animal: "+idadeAnimal);
		System.out.println("Última ida ao veterinário: "+ultimaIdaVet);
		System.out.println("Próxima ida ao veterinário: "+proximaIdaVet);
		
		
	}
	

}
