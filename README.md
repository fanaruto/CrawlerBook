# CrawlerBook
学习爬虫的日记(Learn the journal of the crawler)

#今天换find为XPATH XPATH真是万金油

from selenium.webdriver.common.by import By

self.driver.find_element(By.XPATH, '//*[@id="key"]')
self.driver.find_element(By.XPATH, "//button/i[@class='iconfont']").click()
