//package con.example.helloworld;

import javax.swing.*;
import java.net.URL;
public class Monopoly {


    public static void main(String[] args) {
            JFrame frame = new JFrame();
            URL image = Monopoly.class.getClassLoader().getResource("51AnnChCJcL._AC_SY580_.png");

            ImageIcon icon = new ImageIcon(image);
            JLabel label = new JLabel(icon);
            frame.add(label);
            frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
            frame.pack();
            frame.setVisible(true);

        }

    }

