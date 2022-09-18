import javax.swing.*;
public class TestQueue {
    public static void main (String[] args){
        Queue q = new Queue();
        
        while (true){
            String actions[] = {"Enqueue", "Dequeue", "Exit"};

            Object selectedAction = JOptionPane.showInputDialog(null, "Empty\t: " + q.isEmpty() + "                Full\t: " + q.isFull() +
             "\nCapactiy\t: " + q.getCapacity()+ "                 Current size\t: " + q.getCurrentsize() + "\nPeek\t: " + q.peek() + "                      Last\t: " + q.last() + 
             "\nElements\t: " + q.display() + 
            "\n\n Select\t: ", "Menu", JOptionPane.INFORMATION_MESSAGE, null, actions, "Enqueue");

            if (selectedAction == "Enqueue"){
                String num = JOptionPane.showInputDialog("Enter the number you want to Enqueue: ");
                int num1 = Integer.parseInt(num);
                q.enqueue(num1);
            }else if(selectedAction == "Dequeue"){
                q.dequeue();
            }else{
                break;
            }
        }
    }
}
