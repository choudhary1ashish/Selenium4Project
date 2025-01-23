import org.openqa.selenium.WebDriver;
import org.openqa.selenium.chrome.ChromeDriver;

public class LoginAutomation {
    public static void main(String[] args) {
        System.setProperty("webdrive.chrome.driver", "C:\\Users\\ashish.k.choudhary\\Downloads\\chromedriver_win32\\chromedriver.exe");
     WebDriver driver = new ChromeDriver();
     driver.get("https://www.google.com");
     

    }
