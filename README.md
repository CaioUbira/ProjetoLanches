# ProjetoLanches
Um projeto feito com Java para um cardápio com combos de lanches com foto dos lanches e os valores 



import java.awt.Color;
import javax.swing.ImageIcon;
public class NewJFrame extends javax.swing.JFrame {
    public NewJFrame() {
        initComponents();
        getContentPane().setBackground(Color.ORANGE);        
        ImageIcon icon1 = new ImageIcon("src/img/ifood1.png");
        icon1.setImage(icon1.getImage().getScaledInstance
        (jLabel3.getWidth(),jLabel3.getHeight(),1));
        jLabel3.setIcon(icon1);
        
        ImageIcon icon = new ImageIcon("src/img/semimagem.png");
        icon.setImage(icon.getImage().getScaledInstance
        (jLabel1.getWidth(),jLabel1.getHeight(),1));
        jLabel1.setIcon(icon);
         private void jRadioButton1ActionPerformed(java.awt.event.ActionEvent evt) {                                              
        try
        {
            ImageIcon icon = new ImageIcon("src/img/combo1.jpg");
            icon.setImage(icon.getImage().getScaledInstance
            (jLabel1.getWidth(),jLabel1.getHeight(),1));
            jLabel1.setIcon(icon);
            jTextField1.setText("R$ 38,00");
        }
        catch (Exception e){
            System.out.println("Imagem não encontrada");
        }
    }                                             

    private void jRadioButton2ActionPerformed(java.awt.event.ActionEvent evt) {                                              
         try
        {
            ImageIcon icon = new ImageIcon("src/img/combo2.jpg");
            icon.setImage(icon.getImage().getScaledInstance
            (jLabel1.getWidth(),jLabel1.getHeight(),1));
            jLabel1.setIcon(icon);
            jTextField1.setText("R$ 39,90");
        }
        catch (Exception e){
            System.out.println("Imagem não encontrada");
        }
    }                                             

    private void jRadioButton3ActionPerformed(java.awt.event.ActionEvent evt) {                                              
        try
        {
            ImageIcon icon = new ImageIcon("src/img/combo3.jpeg");
            icon.setImage(icon.getImage().getScaledInstance
            (jLabel1.getWidth(),jLabel1.getHeight(),1));
            jLabel1.setIcon(icon);
            jTextField1.setText("R$ 45,00");
        }
        catch (Exception e){
            System.out.println("Imagem não encontrada");
        }
    }        

