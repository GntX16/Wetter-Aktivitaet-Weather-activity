
import java.util.Scanner;
public class WetterTest {
    public static void main(String[] args) {
        //Variablen anlegen + die gegebenen Werte zuweisen
        int aktuellesWetter;
                        
        //Scanner nötig für die Eingabe
        Scanner scan = new Scanner(System.in);
        //Eingabe Nachricht für Nutzer
        System.out.print("Bitte teilen Sie mit, "
                        + "\nob gerade die Sonne scheint (1), "
                        + "\nob es gerade regnet (2), "
                        + "\nob es gerade schneit (3), "
                        + "\nob es gerade blitzt (4) oder "
                        + "\nob es gerade stuermt (5):");
        aktuellesWetter = scan.nextInt();
        scan.close();

        //wir brauchen Vergleichsoperator (==), nicht Zuweisungsoperator (=), denn es muss verglichen werden
        if (aktuellesWetter == 1) {
            System.out.println("Fußball spielen oder schwimmen gehen");
        }
        else if (aktuellesWetter == 2) {
            System.out.println("Spazieren gehen, oder ins Kino gehen");
        }
        else if (aktuellesWetter == 3) {
            System.out.println("Einen Schneemann bauen oder Schlittenfahren");
        }
        //Mit logischem ODER || können wir beide Fälle zusammen, sie sind jedoch 2 seperate Prüfungen
        else if (aktuellesWetter == 4 || aktuellesWetter == 5) {
            System.out.println("Karten spielen");
        }
        else {
            System.out.println("Überprüfen Sie bitte Ihre Eingabe. Eingabewerte beachten!");
        } //6 Testvorläufe um unser Prog vollständig zu testen!
    }
}
