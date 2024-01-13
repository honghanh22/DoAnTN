### Các loại Test Automation Framework phổ biến hiện nay
📦AutomationFrameworkCucumberTestNG
 ┣ 📂.github
 ┃ ┗ 📂workflows
 ┃ ┃ ┗ 📜maven.yml
 ┣ 📂src
 ┃ ┣ 📂main
 ┃ ┃ ┣ 📂java
 ┃ ┃ ┃ ┗ 📂com
 ┃ ┃ ┃ ┃ ┗ 📂anhtester
 ┃ ┃ ┃ ┃ ┃ ┣ 📂annotations
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜FrameworkAnnotation.java
 ┃ ┃ ┃ ┃ ┃ ┣ 📂config
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜ConfigFactory.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜Configuration.java
 ┃ ┃ ┃ ┃ ┃ ┣ 📂constants
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜FrameworkConstants.java
 ┃ ┃ ┃ ┃ ┃ ┣ 📂driver
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜BrowserFactory.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜DriverManager.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜TargetFactory.java
 ┃ ┃ ┃ ┃ ┃ ┣ 📂enums
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜AuthorType.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜Browser.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜CategoryType.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜FailureHandling.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜Platform.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜Project.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜Target.java
 ┃ ┃ ┃ ┃ ┃ ┣ 📂exceptions
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜FrameworkException.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜HeadlessNotSupportedException.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜InvalidPathForExcelException.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜InvalidPathForExtentReportFileException.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜InvalidPathForFilesException.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜InvalidRemoteWebDriverURLException.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜TargetNotValidException.java
 ┃ ┃ ┃ ┃ ┃ ┣ 📂helpers
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜CaptureHelpers.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜DatabaseHelpers.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜ExcelHelpers.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜FileHelpers.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜Helpers.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜PropertiesHelpers.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜ScreenRecoderHelpers.java
 ┃ ┃ ┃ ┃ ┃ ┣ 📂keywords
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜WebUI.java
 ┃ ┃ ┃ ┃ ┃ ┣ 📂mail
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜EmailAttachmentsSender.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜EmailConfig.java
 ┃ ┃ ┃ ┃ ┃ ┣ 📂report
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜AllureManager.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜ExtentReportManager.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜ExtentTestManager.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜TelegramManager.java
 ┃ ┃ ┃ ┃ ┃ ┗ 📂utils
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜BrowserInfoUtils.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜DataFakerUtils.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜DataGenerateUtils.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜DateUtils.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜DecodeUtils.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜EmailSendUtils.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜IconUtils.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜JsonUtils.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜LanguageUtils.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜LocalStorageUtils.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜LogUtils.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜ObjectUtils.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜ReportUtils.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜ZipUtils.java
 ┃ ┃ ┗ 📂resources
 ┃ ┃ ┃ ┣ 📂META-INF
 ┃ ┃ ┃ ┃ ┗ 📂services
 ┃ ┃ ┃ ┃ ┃ ┗ 📜io.qameta.allure.listener.TestLifecycleListener
 ┃ ┃ ┃ ┗ 📜log4j2.properties
 ┃ ┗ 📂test
 ┃ ┃ ┣ 📂java
 ┃ ┃ ┃ ┗ 📂com
 ┃ ┃ ┃ ┃ ┗ 📂anhtester
 ┃ ┃ ┃ ┃ ┃ ┣ 📂common
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜BaseTest.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜CommonPageCRM.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜CommonSteps.java
 ┃ ┃ ┃ ┃ ┃ ┣ 📂dataprovider
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜DataProviderManager.java
 ┃ ┃ ┃ ┃ ┃ ┣ 📂hooks
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜CucumberListener.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜Hooks.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜TestContext.java
 ┃ ┃ ┃ ┃ ┃ ┣ 📂listeners
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜AllureListener.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜TestListener.java
 ┃ ┃ ┃ ┃ ┃ ┣ 📂projects
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📂website
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂cms
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂pages
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜CommonPageCMS.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜LoginPage.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📂stepdefinitions
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜LoginSteps.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📂crm
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂models
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜ClientModel.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜SignInModel.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂pages
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂Clients
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜ClientPageCRM.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂Dashboard
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜DashboardPageCRM.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂Projects
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜ProjectPageCRM.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂SignIn
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜SignInPageCRM.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📂Tasks
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜TaskPage.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📂stepdefinitions
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜DashboardSteps.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜LoginSteps.java
 ┃ ┃ ┃ ┃ ┃ ┗ 📂runners
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜LoginCMSTestRunner.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜SigninCRMTestRunner.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜TestRunnerAllFeatureByTag.java
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜TestRunnerForDashboardHRM.java
 ┃ ┃ ┗ 📂resources
 ┃ ┃ ┃ ┣ 📂config
 ┃ ┃ ┃ ┃ ┣ 📜config.json
 ┃ ┃ ┃ ┃ ┣ 📜config.properties
 ┃ ┃ ┃ ┃ ┗ 📜data.properties
 ┃ ┃ ┃ ┣ 📂features
 ┃ ┃ ┃ ┃ ┣ 📜Dashboard.feature
 ┃ ┃ ┃ ┃ ┣ 📜LoginCMS.feature
 ┃ ┃ ┃ ┃ ┗ 📜SigninCRM.feature
 ┃ ┃ ┃ ┣ 📂objects
 ┃ ┃ ┃ ┃ ┗ 📜crm_locators.properties
 ┃ ┃ ┃ ┣ 📂suites
 ┃ ┃ ┃ ┃ ┣ 📜SuiteFeatureAll.xml
 ┃ ┃ ┃ ┃ ┣ 📜SuiteFeatureByTag.xml
 ┃ ┃ ┃ ┃ ┗ 📜SuiteFeatureLoginCMS.xml
 ┃ ┃ ┃ ┣ 📂testdata
 ┃ ┃ ┃ ┃ ┣ 📜ClientsDataExcel.xlsx
 ┃ ┃ ┃ ┃ ┣ 📜DOCX_File_01.docx
 ┃ ┃ ┃ ┃ ┣ 📜LoginCSV.csv
 ┃ ┃ ┃ ┃ ┗ 📜TxtFileData.txt
 ┃ ┃ ┃ ┣ 📜cucumber.properties
 ┃ ┃ ┃ ┣ 📜extent.properties
 ┃ ┃ ┃ ┗ 📜pdf-config.yaml
 ┣ 📂target
 ┃ ┣ 📂classes
 ┃ ┃ ┣ 📂anhtester
 ┃ ┃ ┃ ┗ 📂com
 ┃ ┃ ┃ ┃ ┣ 📂annotations
 ┃ ┃ ┃ ┃ ┃ ┗ 📜FrameworkAnnotation.class
 ┃ ┃ ┃ ┃ ┣ 📂config
 ┃ ┃ ┃ ┃ ┃ ┣ 📜ConfigFactory.class
 ┃ ┃ ┃ ┃ ┃ ┗ 📜Configuration.class
 ┃ ┃ ┃ ┃ ┣ 📂constants
 ┃ ┃ ┃ ┃ ┃ ┗ 📜FrameworkConstants.class
 ┃ ┃ ┃ ┃ ┣ 📂driver
 ┃ ┃ ┃ ┃ ┃ ┣ 📜BrowserFactory$1.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜BrowserFactory$2.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜BrowserFactory$3.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜BrowserFactory$4.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜BrowserFactory.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜DriverManager.class
 ┃ ┃ ┃ ┃ ┃ ┗ 📜TargetFactory.class
 ┃ ┃ ┃ ┃ ┣ 📂enums
 ┃ ┃ ┃ ┃ ┃ ┣ 📜AuthorType.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜Browser.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜CategoryType.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜FailureHandling.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜Platform.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜Project.class
 ┃ ┃ ┃ ┃ ┃ ┗ 📜Target.class
 ┃ ┃ ┃ ┃ ┣ 📂exceptions
 ┃ ┃ ┃ ┃ ┃ ┣ 📜FrameworkException.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜HeadlessNotSupportedException.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜InvalidPathForExcelException.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜InvalidPathForExtentReportFileException.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜InvalidPathForFilesException.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜InvalidRemoteWebDriverURLException.class
 ┃ ┃ ┃ ┃ ┃ ┗ 📜TargetNotValidException.class
 ┃ ┃ ┃ ┃ ┣ 📂helpers
 ┃ ┃ ┃ ┃ ┃ ┣ 📜CaptureHelpers.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜DatabaseHelpers.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜ExcelHelpers.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜FileHelpers.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜Helpers.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜PropertiesHelpers.class
 ┃ ┃ ┃ ┃ ┃ ┗ 📜ScreenRecoderHelpers.class
 ┃ ┃ ┃ ┃ ┣ 📂keywords
 ┃ ┃ ┃ ┃ ┃ ┗ 📜WebUI.class
 ┃ ┃ ┃ ┃ ┣ 📂mail
 ┃ ┃ ┃ ┃ ┃ ┣ 📜EmailAttachmentsSender$1.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜EmailAttachmentsSender.class
 ┃ ┃ ┃ ┃ ┃ ┗ 📜EmailConfig.class
 ┃ ┃ ┃ ┃ ┣ 📂report
 ┃ ┃ ┃ ┃ ┃ ┣ 📜AllureManager.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜ExtentReportManager.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜ExtentTestManager.class
 ┃ ┃ ┃ ┃ ┃ ┗ 📜TelegramManager.class
 ┃ ┃ ┃ ┃ ┗ 📂utils
 ┃ ┃ ┃ ┃ ┃ ┣ 📜BrowserInfoUtils.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜DataFakerUtils.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜DataGenerateUtils.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜DateUtils.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜DecodeUtils.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜EmailSendUtils.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜IconUtils.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜JsonUtils$1.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜JsonUtils.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜LanguageUtils.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜LocalStorageUtils.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜LogUtils.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜ObjectUtils.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜ReportUtils.class
 ┃ ┃ ┃ ┃ ┃ ┗ 📜ZipUtils.class
 ┃ ┃ ┣ 📂META-INF
 ┃ ┃ ┃ ┗ 📂services
 ┃ ┃ ┃ ┃ ┗ 📜io.qameta.allure.listener.TestLifecycleListener
 ┃ ┃ ┗ 📜log4j2.properties
 ┃ ┣ 📂generated-sources
 ┃ ┃ ┗ 📂annotations
 ┃ ┣ 📂generated-test-sources
 ┃ ┃ ┗ 📂test-annotations
 ┃ ┗ 📂test-classes
 ┃ ┃ ┣ 📂anhtester
 ┃ ┃ ┃ ┗ 📂com
 ┃ ┃ ┃ ┃ ┣ 📂common
 ┃ ┃ ┃ ┃ ┃ ┣ 📜BaseTest.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜CommonPageCRM.class
 ┃ ┃ ┃ ┃ ┃ ┗ 📜CommonSteps.class
 ┃ ┃ ┃ ┃ ┣ 📂dataprovider
 ┃ ┃ ┃ ┃ ┃ ┗ 📜DataProviderManager.class
 ┃ ┃ ┃ ┃ ┣ 📂hooks
 ┃ ┃ ┃ ┃ ┃ ┣ 📜CucumberListener.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜Hooks.class
 ┃ ┃ ┃ ┃ ┃ ┗ 📜TestContext.class
 ┃ ┃ ┃ ┃ ┣ 📂listeners
 ┃ ┃ ┃ ┃ ┃ ┣ 📜AllureListener.class
 ┃ ┃ ┃ ┃ ┃ ┗ 📜TestListener.class
 ┃ ┃ ┃ ┃ ┣ 📂projects
 ┃ ┃ ┃ ┃ ┃ ┗ 📂website
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂cms
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂pages
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜CommonPageCMS.class
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜LoginPage.class
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📂stepdefinitions
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜LoginSteps.class
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📂crm
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂models
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜ClientModel.class
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜SignInModel.class
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂pages
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂Clients
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜ClientPageCRM.class
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂Dashboard
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜DashboardPageCRM.class
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂Projects
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜ProjectPageCRM.class
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂SignIn
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜SignInPageCRM.class
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📂Tasks
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜TaskPage.class
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📂stepdefinitions
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜DashboardSteps.class
 ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜LoginSteps.class
 ┃ ┃ ┃ ┃ ┗ 📂runners
 ┃ ┃ ┃ ┃ ┃ ┣ 📜LoginCMSTestRunner.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜SigninCRMTestRunner.class
 ┃ ┃ ┃ ┃ ┃ ┣ 📜TestRunnerAllFeatureByTag.class
 ┃ ┃ ┃ ┃ ┃ ┗ 📜TestRunnerForDashboardHRM.class
 ┃ ┃ ┣ 📂config
 ┃ ┃ ┃ ┣ 📜config.json
 ┃ ┃ ┃ ┣ 📜config.properties
 ┃ ┃ ┃ ┗ 📜data.properties
 ┃ ┃ ┣ 📂features
 ┃ ┃ ┃ ┣ 📜Dashboard.feature
 ┃ ┃ ┃ ┣ 📜LoginCMS.feature
 ┃ ┃ ┃ ┗ 📜SigninCRM.feature
 ┃ ┃ ┣ 📂objects
 ┃ ┃ ┃ ┗ 📜crm_locators.properties
 ┃ ┃ ┣ 📂suites
 ┃ ┃ ┃ ┣ 📜SuiteFeatureAll.xml
 ┃ ┃ ┃ ┣ 📜SuiteFeatureByTag.xml
 ┃ ┃ ┃ ┗ 📜SuiteFeatureLoginCMS.xml
 ┃ ┃ ┣ 📂testdata
 ┃ ┃ ┃ ┣ 📜ClientsDataExcel.xlsx
 ┃ ┃ ┃ ┣ 📜DOCX_File_01.docx
 ┃ ┃ ┃ ┣ 📜LoginCSV.csv
 ┃ ┃ ┃ ┗ 📜TxtFileData.txt
 ┃ ┃ ┣ 📜cucumber.properties
 ┃ ┃ ┣ 📜extent.properties
 ┃ ┃ ┗ 📜pdf-config.yaml
 ┣ 📜.gitignore
 ┣ 📜CHANGELOG.txt
 ┣ 📜pom.xml
 ┗ 📜README.md
