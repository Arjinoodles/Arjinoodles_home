import java.awt.Color;
import java.awt.event.ActionEvent;
import java.awt.event.ActionListener;
import javax.swing.*;
public  class Calculater implements ActionListener{
	JFrame frame;
	 JButton button0, button1 , button2, button3, button4, button5, button6, button7, button8, button9,buttonAdd,buttonSub , buttonclear;
	 JButton buttonEq , buttonMul,buttonDiv , buttonFac, buttonDec , buttonPerc/* , button */;
	 JTextField f1;
	 JTextField f2;
	 double num1=0,num2=0,op=0,res=0;
	 boolean dec =false;
    public Calculater() {
    	frame=new JFrame("Caluctator");
		frame.setSize(600,500);
		frame.setLayout(null);
		frame.setLocation(500, 100);
		frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		f1=new JTextField();
		f1.setBounds(10,10,470,40);
		f1.setBackground(Color.GRAY);
		frame.add(f1);
		frame.setResizable(false);
		/*f2=new JTextField();
		f2.setBounds(100,160,200,40);
		frame.add(f2);*/
		System.out.println("Opened successfully");
		//buttons 0-9
		button0=new JButton("0");
		button0.setBounds(50,300,100,40);
		frame.add(button0);
		buttonDec=new JButton(".");
		buttonDec.setBounds(150,300,100,40);
		frame.add(buttonDec);
		button1=new JButton("1");
		button1.setBounds(50,240,70,40);
		frame.add(button1);
		button2=new JButton("2");
		button2.setBounds(150,240,70,40);
		frame.add(button2);
		button3=new JButton("3");
		button3.setBounds(250,240,70,40);
		frame.add(button3);
		button4=new JButton("4");
		button4.setBounds(50,180,70,40);
		frame.add(button4);
		frame.setVisible(true);
		button5=new JButton("5");
		button5.setBounds(150,180,70,40);
		frame.add(button5);
		button6=new JButton("6");
		button6.setBounds(250,180,70,40);
		frame.add(button6);
		button7=new JButton("7");
		button7.setBounds(50,120,70,40);
		frame.add(button7);
		button8=new JButton("8");
		button8.setBounds(150,120,70,40);
		frame.add(button8);
		button9=new JButton("9");
		button9.setBounds(250,120,70,40);
		frame.add(button9);
		buttonAdd=new JButton("+");
		buttonAdd.setBounds(400,120,70,40);
		/*buttonAdd.setBackground(Color.RED);
		buttonAdd.setOpaque(true);
		buttonAdd.setBorderPainted(false);*/
		frame.add(buttonAdd);
		buttonMul=new JButton("x");
		buttonMul.setBounds(400,280,70,40);
		frame.add(buttonMul);
		buttonDiv=new JButton("÷");
		buttonDiv.setBounds(400,230,70,40);
		frame.add(buttonDiv);
		buttonSub=new JButton("-");
		buttonSub.setBounds(400,170,70,40);
		frame.add(buttonSub);
		buttonEq=new JButton("=");
		buttonEq.setBounds(400,360,70,40);
		frame.add(buttonEq);
		buttonclear=new JButton("clear");
		buttonclear.setBounds(50,400,150,40);
		frame.add(buttonclear);
		buttonFac=new JButton("!");
		buttonFac.setBounds(480,120,70,40);
		frame.add(buttonFac);
		buttonPerc=new JButton("%");
		buttonPerc.setBounds(480,170,70,40);
		frame.add(buttonPerc);
		//action listeners
		button0.addActionListener(this);
		button1.addActionListener(this);
		button2.addActionListener(this);
		button3.addActionListener(this);
		button4.addActionListener(this);
		button5.addActionListener(this);
		button6.addActionListener(this);
		button7.addActionListener(this);
		button8.addActionListener(this);
		button9.addActionListener(this);
		buttonAdd.addActionListener(this);
		buttonSub.addActionListener(this);
		buttonclear.addActionListener(this);
		buttonEq.addActionListener(this);
		buttonMul.addActionListener(this);
		buttonDiv.addActionListener(this);
		buttonFac.addActionListener(this);
		buttonDec.addActionListener(this);
	    buttonPerc.addActionListener(this);
		frame.getContentPane().setBackground(Color.DARK_GRAY);
		frame.setVisible(true);
    }
	@Override
	public void actionPerformed(ActionEvent e) {
		if(e.getSource()==button0) {
			f1.setText(f1.getText().concat("0"));
		}
		if(e.getSource()==button1) {
			f1.setText(f1.getText().concat("1"));
		}
		if(e.getSource()==button2) {
			f1.setText(f1.getText().concat("2"));
		}
		if(e.getSource()==button3) {
			f1.setText(f1.getText().concat("3"));
		}
		if(e.getSource()==button4) {
			f1.setText(f1.getText().concat("4"));
		}
		if(e.getSource()==button5) {
			f1.setText(f1.getText().concat("5"));
		}
		if(e.getSource()==button6) {
			f1.setText(f1.getText().concat("6"));
		}
		if(e.getSource()==button7) {
			f1.setText(f1.getText().concat("7"));
		}
		if(e.getSource()==button8) {
			f1.setText(f1.getText().concat("8"));
		}
		if(e.getSource()==button9) {
			f1.setText(f1.getText().concat("9"));
		}
		if(e.getSource()==buttonDec) {
			if(!f1.getText().contains(".")) {
			f1.setText(f1.getText().concat("."));
			}	
		}
		if(e.getSource()==buttonAdd) {
			num1=Double.parseDouble(f1.getText());
			op=1;
			f1.setText("");
		}
		if(e.getSource()==buttonSub) {
			num1=Double.parseDouble(f1.getText());
			op=2;

			f1.setText("");
		}
		if(e.getSource()==buttonMul) {
			num1=Double.parseDouble(f1.getText());
			op=3;
			f1.setText("");
		}
		if(e.getSource()==buttonDiv) {
			num1=Double.parseDouble(f1.getText());
			op=4;
			f1.setText("");
		}
		if(e.getSource()==buttonclear) {
			f1.setText("");
		}
		if(e.getSource()==buttonFac) {
			num1=Double.parseDouble(f1.getText());
			double result=1;
			for(int i=1;i<=num1;i++) {
			result=result*i;	
			}
			f1.setText(""+result);
	//made by Arjinoodes on github		
		}
		if(e.getSource()==buttonPerc) {
			num1=Double.parseDouble(f1.getText());
			res=num1*num2/100;
			f1.setText(""+res);
		}
		//Equals DO NOt MESS AROUND
		if(e.getSource()==buttonEq) {
			num2=Double.parseDouble(f1.getText());
			if(op==1) {
				res=num1+num2;
			}
			if(op==2) {
				res=num1-num2;
			}
			if(op==3) {
				res=num1*num2;
			}
			if(op==4) {
				res=num1/num2;
			}
			res=Math.round(res*100000.0)/100000.0;
			f1.setText(""+res);
			num1=res;	
		}
		}	
public static void main(String[]args) {
	new Calculater();
}	
}
