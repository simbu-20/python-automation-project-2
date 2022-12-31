TEST CASE O1- SEARCH TEXT BOX

from selenium import webdriver
from selenium.webdriver.chrome.service import Service
from selenium.webdriver.common.alert import Alert
from webdriver_manager.chrome import ChromeDriverManager
import time
import unittest

class LoginTest(unittest.TestCase):
    driver = None

    @classmethod
    def setUpClass(cls):
        cls.driver = webdriver.Chrome(service=Service(ChromeDriverManager().install()))
        cls.driver.implicitly_wait(10)
        cls.driver.maximize_window()
    def test_01_login_invalid(self):
        driver = self.driver
        driver.get("https://opensourcedemo.orangehrmlive.com/")

        login = LoginPage(driver)
        login.enter_username("Admin")
        login.enter_password("Invalid password")
        login.click_login()
      
     def serach textbox (self)
        driver.find_element(BY.XPATH,"//input["@class='serach']").click()
     def --int--(self,driver):
        self.driver=driver
     time.sleep(30)   
     def enter Admin(self,Admin):
        self.driver.find_element(BY.XPATH,Self.Admin_textbox_xpath).send_keys(Admin)   
     def enter PIM(self,PIM):
        self.driver.find_element(BY.XPATH,Self.PIM_textbox_xpath).send_keys(PIM) 
     def enter Leave(self,Leave):
        self.driver.find_element(BY.XPATH,Self.Leve_textbox_xpath).send_keys(Leave)
     def enter Time(self,Time):
        self.driver.find_element(BY.XPATH,self.Time_textbox_xpath).send_keys(Time)
    def enter (self,Recuirement):
        self.driver.find_element(BY.XPATH,self.Recuirement_textbox_xpath).send_keys(Recuirement) 
  def enter My info(self,My info):
        self.driver.find_element(BY.XPATH,self.My info_textbox_xpath).send_keys(My info)
  def enter Performance(self,Performance):
        self.driver.find_element(BY.XPATH,self.Performance_textbox_xpath).send_keys(Performance)
  def enter Dashboard(self,Dashboard):
        self.driver.find_element(BY.XPATH,self.Dashboard_textbox_xpath).send_keys(Dashboard)
  def enter Directory(self,Directory):
        self.driver.find_element(BY.XPATH,self.Directory_textbox_xpath).send_keys(Directory)
  def enter Maintenance(self,Maintenance):
        self.driver.find_element(BY.XPATH,self.Maintenance_textbox_xpath).send_keys(Maintenance)
  def enter Buzz(self,Buzz):
        self.driver.find_element(BY.XPATH,self.Buzz_textbox_xpath).send_keys(Buzz)
   
   @classmethod
    def tearDownClass(cls):
        cls.driver.close()
        cls.driver.quit()
        print("Test Completed")
   
   TEST CASE -02 DROP DOWN 
   
from selenium import webdriver
from selenium.webdriver.chrome.service import Service
from selenium.webdriver.common.alert import Alert
from webdriver_manager.chrome import ChromeDriverManager
from selenium.webdriver.import Actionchains keys
from selenium.webdriver.common.BY import by
import time
driver.find_element(BY.XPATH,"//input[@class='Admin']").click()
driver.implicitly_wait(30)
driver.find_element(BY.XPATH,://class[@class='button']).click()
user role_dropdown=driver.find_element(BY.XPATH,"//div[@input='textbox 1']").send_keys(Admin)
status_dropdown=driver.find element_(BY.XPATH,"//div[@input='text box 2']").sendkeys (Enabled)
user role_dropdown=driver.find_element(BY.XPATH,"//div[@input='textbox 1']").send_keys(ESS)
status_dropdown=driver.find element_(BY.XPATH,"//div[@input='text box 2']").sendkeys (Disabled)

driver.quit()


TEST CASE 3

from selenium import webdriver
from selenium.webdriver.chrome.service import Service
from selenium.webdriver.common.alert import Alert
from webdriver_manager.chrome import ChromeDriverManager
from selenium.webdriver.import Actionchains keys
from selenium.webdriver.common.BY import by
import time

  def test_01_login_invalid(self):
        driver = self.driver
        driver.get("https://opensourcedemo.orangehrmlive.com/")

        login = LoginPage(driver)
        login.enter_username("Admin")
        login.enter_password("Invalid password")
        login.click_login()
      
class HomePage:

    def __init__(self, driver):
        self.driver = driver

        self.pim_button_xpath = "//span[text()='PIM']"
        self.add_button_xpath = "//button[text()=' Add ']"  # //button[normalize-space()='Add'] #
        self.firstname_textbox_name = "SLAMABARASAN"
        self.lastname_textbox_name = "SIVASANKARAN"

    def click_pim(self):
        self.driver.find_element(By.XPATH, self.pim_button_xpath).click()

    def add_employee(self, firstname, lastname):
        self.driver.find_element(By.XPATH, self.add_button_xpath).click()
        self.driver.find_element(By.NAME, self.firstname_textbox_name).clear()
        self.driver.find_element(By.NAME, self.firstname_textbox_name).send_keys(SILAMABARASAN)
        self.driver.find_element(By.NAME, self.lastname_textbox_name).clear()
        self.driver.find_element(By.NAME, self.lastname_textbox_name).send_keys(SIVASANAKARAN)

  def click_login details(self):
       self.driver.find_element(By.XPATH,self.span_button_xpath).click()
       
       def click_save(self):
        self.driver.find_element(By.XPATH, self.save_button_xpath).click()
        
        
        
    TEST CASE 4
    from selenium.webdriver.common.BY import by
    
  class HomePage:

    def __init__(self, driver):
        self.driver = driver
     driver.implicitly_wait(30)
        self.pim_button_xpath = "//span[text()='PIM']"
    def employee_list(self,employe_list ):
        self.driver.find_element(By.XPATH, self.href_button_xpath).click()
     def emp_personal details(self, personal_details)
      self.driver.find_element(By.XPATH, self.'href' personal_details_button_xpath).click()
     def conatct_details(self,contact_details ):
        self.driver.find_element(By.XPATH, self.'href'contact_details_button_xpath).click()
    def emer_conatacts(self,emer_contact details ):
        self.driver.find_element(By.XPATH, self.'href'emer_contact details_button_xpath).click()  
   def dependents(self,dependents ):
        self.driver.find_element(By.XPATH, self.'href'emer_contact details_button_xpath).click()
   def immigration(self,immigration ):
        self.driver.find_element(By.XPATH, self.'href'immigration_button_xpath).click()
   def job(self,job ):
        self.driver.find_element(By.XPATH, self.'href'job_button_xpath).click()            
   def salary(self,salary ):
        self.driver.find_element(By.XPATH, self.'href'salary_button_xpath).click()                 
    def tax_exemptions(self,tax_exemptions ):
        self.driver.find_element(By.XPATH, self.'href'taxemeptions_button_xpath).click()                 
   def report_to(self,report_to ):
        self.driver.find_element(By.XPATH, self.'href'report_to_button_xpath).click()            
    def qualifications(self,qualifications ):
        self.driver.find_element(By.XPATH, self.'href'qualifications_button_xpath).click()            
    def membership(self,membership):
        self.driver.find_element(By.XPATH, self.'href'membership_button_xpath).click() 
        
    TEST CASE 05
    def __init__(self, driver):
        self.driver = driver

        self.pim_button_xpath = "//span[text()='PIM']"
        Self.emp_list_button_xpath="//href[text(employeelist)='employee list']"
   def emp_personal details(self, personal_details)
      self.driver.find_element(By.XPATH, self.'href' personal_details_button_xpath).click()
    def emp_personal details(self, personal_details)   
   self.driver.find_element(By.NAME, self.firstname_textbox_name).clear()
        self.driver.find_element(By.NAME, self.firstname_textbox_name).send_keys(SILAMABARASAN)
        self.driver.find_element(By.NAME, self.lastname_textbox_name).clear()
        self.driver.find_element(By.NAME, self.lastname_textbox_name).send_keys(SIVASANAKARAN)
    
     def click_save(self):
        self.driver.find_element(By.XPATH, self.save_button_xpath).click()
        
  
TEST CASE 6
      def __init__(self, driver):
        self.driver = driver

        self.pim_button_xpath = "//span[text()='PIM']"
        Self.emp_list_button_xpath="//href[text(employeelist)='employee list']"
   def contact_details(self,contact details)
    Self.contact_details_button_xpath="//href[text(home)='bottom filed']"
   self.driver.find_element(By.class, self.home_textbox_name).send_keys(12345678900)
   
 def click_save(self):
        self.driver.find_element(By.XPATH, self.save_button_xpath).click()
        
TEST CASE 7
     def __init__(self, driver):
        self.driver = driver

        self.pim_button_xpath = "//span[text()='PIM']"
        Self.emergency_contact_button_xpath="//href[text(employeelist)='emergency contact']"
    def--int--(self)
    self=self.driver
     def enter name(self,name):
        self.driver.find_element(BY.XPATH,Self.name_textbox_xpath).send_keys(xxx)   
     def enter relation(self,relation):
        self.driver.find_element(BY.XPATH,Self.relation_textbox_xpath).send_keys(yyy) 
      def enter relation(self,mobile):
        self.driver.find_element(BY.XPATH,Self.mobile_textbox_xpath).send_keys(1234567890000)    
def click_save(self):
        self.driver.find_element(By.XPATH, self.save_button_xpath).click()
        
   TEST CASE 8 
      def __init__(self, driver):
        self.driver = driver

        self.pim_button_xpath = "//span[text()='PIM']"
   Self.dependents_button_xpath="//href[text(dependents)='dependents']"
   def enter name(self,name):
        self.driver.find_element(BY.XPATH,Self.name_textbox_xpath).send_keys(sss) 
     def enter relation(self,relation):
        self.driver.find_element(BY.XPATH,Self.relation_textbox_xpath).send_keys(yxz)
           
 def click_save(self):
        self.driver.find_element(By.XPATH, self.save_button_xpath).click()
