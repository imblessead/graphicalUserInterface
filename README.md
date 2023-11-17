# graphicalUserInterface
Swing1

package graphicalUserInterface;

import javax.swing.JFrame;
import javax.swing.JOptionPane;

public class SomaGUI {
	//OptionPaneExample(){
	JFrame f;
	
	SomaGUI(){
		f = new JFrame();
		String numero=JOptionPane.showInputDialog(f ,"Digite um numero ? ");
		int numero1=Integer.parseInt(numero);
		String numero2=JOptionPane.showInputDialog(f ,"Digite um numero ? ");
		int numero3=Integer.parseInt(numero2);
		
		//processamento
		
		int soma= numero1+numero3;
		JOptionPane.showInputDialog(f, "soma dos valores digitados é : "+ soma );
	}
	
 public static void main(String[] args) {
	new SomaGUI();
}
}
