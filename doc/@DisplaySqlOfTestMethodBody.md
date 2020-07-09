With this annotation the SQL statements are displayed in the console during the execution of the test method body. <br>

Compared to [@DisplaySql](./@DisplaySql), this annotation does not display SQL statements before (JUnit 4: @Before, @BeforeClass) and after (JUnit 4: @After, @AfterClass) the execution of the test method body. <br>

⚠️ *It is not recommended to commit your test with this annotation. Indeed, the SQL statements would pollute the logs and may slow down the continuous integration build.*