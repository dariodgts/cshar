# cshar
// repositorio c#

using System;

//INICIO CLASE ANIMAL
namespace ANIMAL
{
	/// <summary>
	/// Description of Animal.
	/// </summary>
	public class Animal
	{
	
			private String especie;
			private  String nombre;
			public Animal(){
			
			
			
			}
			
			public Animal(String especie, String nombre){
			
			this.especie= especie;
			this.nombre= nombre;	
			
			}
        public void setNombre(String nombre)
        {

            this.nombre = nombre;
        }
        public void setEspecie(String especie){
			
				this.especie= especie;
				
		}
			
			public String getNombre(){
				return nombre;
			}
			
			
			
			public String getEspecie(){
				return especie;
			}
	}
	
}
// FIN CLASE ANIMAL

/*public class TesterAnimal{
public static void Main(string[] args)
		{
	Animal animal= new Animal();
	Animal animal2= new Animal("GATO", "FELINO");
	animal.setNombre("perro");
	animal.setEspecie("canino");
	
	Console.WriteLine("Nombre animal: {0}", animal.getNombre());
	Console.WriteLine("Nombre animal: {0}", animal.getEspecie());
	Console.WriteLine("Nombre animal: {0}", animal2.getNombre());
	Console.WriteLine("Nombre animal: {0}", animal2.getEspecie());
}
}
*/


