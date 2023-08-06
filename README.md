# CodeClauseInternshipPasswordManager
import java.util.HashMap;
import java.util.Map;
public class PasswordManager {
    private static final Map<String, String> passwords = new HashMap<>();
    public static void main(String[] args) {
        // Add some passwords to the password manager
        passwords.put("website1", "password1");
        passwords.put("website2", "password2");
        passwords.put("website3", "password3");
        // Get the password for a website
        String password = passwords.get("website1");
        System.out.println("The password for website1 is " + password);
    }
}
