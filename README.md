# -randomstorebd.com-




package com.fb;
import java.util.Scanner;
import org.openqa.selenium.By;
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.WebElement;
import org.openqa.selenium.chrome.ChromeDriver;
public class just {

	public static void main(String[] args) throws InterruptedException
	{
		WebDriver suiii=new ChromeDriver();
		suiii.get("https://randomstorebd.com/");
		suiii.findElement(By.xpath("//li[@id='menu-item-13751']//span[@class='nav-link-text'][normalize-space()='Sweatshirt']")).click();
		suiii.findElement(By.xpath("//div[@class='wd-header-my-account wd-tools-element wd-event-hover wd-design-7 wd-account-style-icon login-side-opener whb-7qrb5r43fmh57lkx4dry']//span[@class='wd-tools-icon']")).click();
		suiii.findElement(By.xpath("//input[@id='username']")).sendKeys("kshrabon782@gmail.com");
		suiii.findElement(By.xpath("//input[@id='password']")).sendKeys("Alamin420");
		suiii.findElement(By.xpath("//button[@name='login']")).click();
		suiii.findElement(By.xpath("//a[@class='woocommerce-LostPassword lost_password']")).click();

		
		
		
		
		
		
		
	}
	
	
	
}
