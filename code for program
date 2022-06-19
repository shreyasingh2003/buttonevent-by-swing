import java.awt.*;
import java.awt.event.*;
import javax.swing.*;

public class button {
  public button(){
      JFrame Frm= new JFrame("MY NEW WINDOW");
      JLabel lab=new JLabel("press the button");
      Frm.setLayout(new FlowLayout());
      Frm.setSize(300,300);
      Frm.add(lab);
      Frm.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
      JButton jb=new JButton ("BLUE");
         jb.addActionListener(new ActionListener(){
           public void actionPerformed(ActionEvent arg) {
               String s= jb.getText();
               if(s.equals("BLUE")){
               Frm.getContentPane().setBackground(Color.blue) ; 
               lab.setText("blue button is pressed")  ;
              }
            }
         });
         JButton jb2 =new JButton ("RED");
         jb2.addActionListener(new ActionListener(){
           public void actionPerformed(ActionEvent arg) {
               String s =jb2.getText();
               if(s.equals("RED")){
                Frm.getContentPane().setBackground(Color.red);   
                lab.setText("red button is pressed");
              }
            }
         });
         Frm.add(jb);
         Frm.add(jb2);
         Frm.setVisible(true);
  }    
      public static void  main(String[] args) {
        SwingUtilities.invokeLater(new Runnable (){
            public void run(){
                new  button();
            }
        });
      }
}







    

