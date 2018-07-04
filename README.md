# Hello-world
package org.Test;

import org.openqa.selenium.WebDriver;
import org.openqa.selenium.chrome.ChromeDriver;

public class Login {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		System.setProperty("webdriver.chrome.driver", "/Users/arunkumar.vadivel/Desktop/Selenium and eclipse/chromedriver");

		WebDriver driver = new ChromeDriver();
		String url = "https://www.google.com";
		driver.get(url);
		String value = driver.getTitle();
		System.out.println(value);	
		driver.quit();
		
	}

}

