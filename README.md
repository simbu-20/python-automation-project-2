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
     driver= self.driver
     self.driver.find_element(BY.XPATH,"//input
