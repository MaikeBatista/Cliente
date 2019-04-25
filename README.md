import java.awt.Container;
import java.util.List;
import java.util.Vector;
import javax.swing.JOptionPane;

public class principal {
	static final int QTEREGISTROS =10;
	
	public static String codigo[]= new String[QTEREGISTROS];
	public static String nome[]= new String[QTEREGISTROS];
	public static String email[]= new String[QTEREGISTROS];
	public static String cidade[]= new String[QTEREGISTROS];
	public static String uf[]= new String[QTEREGISTROS];
	
	public static void main(String[] args) {
		
		String opcao = "";
		JOptionPane entrada = new JOptionPane();
		JOptionPane saida = new JOptionPane();
		while(!opcao.equals("6")) {
			opcao=entrada.showInputDialog("**Menu de opções**\n\n"+
					 					"1 - Cadastrar\n"+
					 					"2 - Consultar\n"+
					 					"3 - Atualizar\n"+
					 					"4 - Excluir\n"+
					 					"5 - Listar\n"+
					 					"6 - Sair\n"+
					 					"Escolha sua opção: "
					);
		switch(opcao) { 	 
			case "1": 
				cadastrar();
				break;
			case "2": 
				consultar();	
				break;
			case "3":
				System.exit(0);
				break;
			case "4": 
				System.exit(0);	
				break;
			case "5": 
				System.exit(0);
				break;
			case "6": 
				System.exit(0);
				break;
			default:
		 JOptionPane.showMessageDialog(
				 null,
				"Opção inválida"
		  );
	
	}
		}}
private static void sair() {
	}
private static void listar() {
	}
private static void excluir() {
	}
public static void consultar() {
	codigo.equals(JOptionPane.showInputDialog(null, "codigo deseja buscar"));
/*
    for(int i=0;i<i;i++){
        if(codigo.length.getcodigo().equals(codigo.length)){
                Object consultar;
				JOptionPane.showMessageDialog(null, ((Object) consultar).get(i).getcodigo());
     }

       }
        */
    }
public static void cadastrar() {
		// TODO Auto-generated method stub	
	for(int i=0;i<1;i++) {
	codigo[i] = JOptionPane.showInputDialog("Digite codigo");
	nome[i] = JOptionPane.showInputDialog("Digite nome");
	email[i] = JOptionPane.showInputDialog("Digite email");
	cidade[i] = JOptionPane.showInputDialog("Digite cidade");
	uf[i] = JOptionPane.showInputDialog("Digite UF");
	}
	
	}
	
public static void Mensagem (String texto) {
	JOptionPane.showMessageDialog(null, texto);
	
}
}
