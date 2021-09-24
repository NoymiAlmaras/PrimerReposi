# PrimerReposi
Tarea
/**
 * Write a description of class Empleado here.
 * 
 * @author Noymi Almaras 
 * @version (a version number or a date)
 */
public class Empleado
{
    // Atributos
    private String nombre;
    private int edad;
    private int salario;

    public Empleado(String nombre, int edad) { //Constructores
        this.nombre = nombre;
        this.edad = edad;
        salario = 200;
    }

    public  void  setNombre (String valor ) {
        nombre = valor;
    }

    public  void  setEdad ( int  valor ) {
        edad = valor;
    } 

    public  void  setSalario (int valor ) {
        salario = valor;
    } 

    public  String  getNombre () {
        return nombre;
    }

    public  int  getEdad () {
        return edad;
    }

    public  int getSalario () {
        return salario;
    }

}
