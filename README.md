# GoogleTets
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.firefox.FirefoxDriver;

/**
 * Created by freeman on 18.03.2016.
 */
public class GoogleTest
{
    public static void main(String[] args)
    {
        //System.out.println("Simple Test");
        WebDriver browser =new FirefoxDriver();
        browser.get("http://google.com");
        browser.close();
    }

}

