# hello-world

hello world 

hurray 

public class Test { 

@Test 

public static void screenshot () throws Exception {

System.setProperty("webdriver, gecko,driver", "d://"); 

Webdriver driver = new Firefoxdriver(); 

driver.get(""); 

driver.manage().timeouts().implicitlywait(10, timeunit.seconds); 

File srcfile = ((Takesscreenshot)driver).getscreenshotAs(outtype.FILE); 

fileutils.copyfile(srcfile, new file ("path")); 

driver.quit(); 

}
}

