# EnterpriseGradeTestAutomationFramework FOLDER TREE
```
├── API/
│   ├── TestArtifacts/
│   │   ├── Logs/
│   │   │   └── ClientExecution.log
│   │   ├── Reports/
│   │   │   └── testExe_Android11.0_20220830T205439536.json
│   │   
│   ├── TestAuxiliary/
│   ├── TestCases/
│   │   ├── Resource1TestCases/
│   │   │   └── Resource1.cs
│   │   ├── Resource2TestCases/
│   │   │   └── Resource2.cs
│   │   └── API_Initializer.cs
│   ├── TestData/
│   │   ├── Resource1Data/
│   │   │   └── Resource1Data.json
│   │   └── Resource2Data/
│   │       └── Resource2Data.json
│   ├── TestExecution/
│   ├── TestResources/
│   │   ├── Resource1/
│   │   │   ├── Resource1.cs
│   │   │   └── Resource1Schema.json
│   │   └── Resource2/
│   │       ├── Resource2.cs
│   │       └── Resource2Schema.json
│      
├── Common/
│   ├── Abstractions/
│   │   ├── IDefect.cs
│   │   ├── IPublisher.cs
│   │   ├── ITestCase.cs
│   │   └── ITestCycle.cs
│   ├── Concretes/
│   │   ├── Defect.cs
│   │   ├── Publisher.cs
│   │   ├── TestCase.cs
│   │   └── TestCycle.cs
│   └── GlobalHelper.cs
├── Mobile/
│   ├── TestArtifacts/
│   │   ├── ExecutionMedia/
│   │   ├── Logs/
│   │   │   ├── AppiumServerLogs.log
│   │   │   └── ClientExecutionLogs.log
│   │   ├── Reports/
│   │   │   └── testExe_Android11.0_20220830T205439536.json
│   │   ├── Standards/
│   │   
│   ├── TestAuxiliary/
│   │   ├── Config.json
│   │   ├── DriverOperations.cs
│   │   ├── ElementOperations.cs
│   │   └── Setup.cs
│   ├── TestCases/
│   │   ├── Screen1TestCases/
│   │   │   └── Screen1.cs
│   │   ├── Screen2TestCases/
│   │   │   └── Screen2.cs
│   │   └── Mobile_Initializer.cs
│   ├── TestData/
│   │   ├── Screen1Data/
│   │   │   └── Screen1Data.json
│   │   └── Screen2Data/
│   │       └── Screen2Data.json
│   ├── TestExecution/
│   ├── TestScreens/
│   │   ├── Screen1/
│   │   │   └── Screen1.cs
│   │   └── Screen2/
│   │       └── Screen2.cs  
├── Web/
│   ├── TestArtifacts/
│   │   ├── ExecutionMedia/
│   │   ├── Logs/
│   │   │   ├── ClientExecutionLogs.log
│   │   │   └── DriverServerExecutionLogs.log
│   │   ├── Reports/
│   │   │   └── testExe_WindowsChrome11.0_20220830T205439536.json
│   │   ├── Standards/
│   │ 
│   ├── TestAuxiliary/
│   │   ├── Config.json
│   │   ├── DriverOperations.cs
│   │   ├── ElementOperations.cs
│   │   └── Setup.cs
│   ├── TestCases/
│   │   ├── Page1TestCases/
│   │   │   └── Page1.cs
│   │   ├── Page2TestCases/
│   │   │   └── Page2.cs
│   │   └── Web_Initializer.cs
│   ├── TestData/
│   │   ├── Page1Data/
│   │   │   └── Page1Data.json
│   │   └── Page2Data/
│   │       └── Page2Data.json
│   ├── TestExecution/
│   │   ├── 0FetchedTestCases.json
│   │   ├── 1AdapterTestCases.json
│   │   ├── 2ExecutionTestCases.json
│   │   ├── 3PublishedTestCasesStatus.json
│   │   ├── DotnetCommnad.txt
│   │   ├── LastExecutionResult.json
│   │   └── Nunit3Command.txt
│   ├── TestPages/
│   │   ├── Page1/
│   │   │   └── Page1.cs
│   │   └── Page2/
│   │       └── Page2.cs
├── app.config
├── log4net.config
├── PilotEGTAF.csproj
└── Usings.cs
```

# Framework Walkthrough via Logs
```
2024-11-01 12:17:00,550 INFO-|_____________________________________________________________________________________________
2024-11-01 12:17:00,553 INFO-|___ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ WEB STARTS 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 
2024-11-01 12:17:00,554 INFO-|__[SetUpFixture]Web_Initializer.cs>Web_Setup()
2024-11-01 12:17:00,554 INFO-|Creating testcycle for module:Web,testType:Smoke and returning testCycleID
2024-11-01 12:17:00,555 INFO-|__✅ Created TestCycle
2024-11-01 12:17:00,555 INFO-|Fetching testcases for module:Web,testType:Smoke and returning list of testcases
2024-11-01 12:17:00,556 INFO-|__✅ Fetched TestCases
2024-11-01 12:17:00,556 INFO-|Attaching testcases for testcycleId:111111
2024-11-01 12:17:00,557 INFO-|__🔗 Linked fetched testcases to the created testcycle
2024-11-01 12:17:00,557 INFO-|_____✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨PAGE1 STARTS✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨
2024-11-01 12:17:00,557 INFO-|	 🏭PageFactory with POM for Page1
2024-11-01 12:17:00,558 INFO-|_____ 🧪 [TestFixture][OneTimeSetUp]Page1TestCases.cs/ClassSetup()>INITIALIZED Page1
2024-11-01 12:17:00,558 INFO-|_____ ⏱️ Started TestClass Timer
2024-11-01 12:17:00,560 INFO-|------------------------------------------------------------------
2024-11-01 12:17:00,560 INFO-|_______ 🧪 [TestFixture][SetUp]Page1TestCases.cs/TestSetup()
2024-11-01 12:17:00,561 INFO-|_______ ⏱️ Started TestMethod Timer
2024-11-01 12:17:00,565 INFO-|_______ 🎥✅ Started Screen recording
2024-11-01 12:17:00,566 INFO-|____________ 🧪[TestFixture][Test]Page1TestCases.cs/Test1()>CALLED Page1.Page1_Method1()
2024-11-01 12:17:00,566 INFO-|🎮Page1.cs/Page1_Method1()>USED Page1_Prop1:Page1Prop1Value
2024-11-01 12:17:00,566 INFO-|💽 Read from TestData/Page1Data/Page1Data.json and Printed 📈
2024-11-01 12:17:00,576 INFO-|_______ 🧪 [TestFixture][TearDown]Page1TestCases.cs/TestTearDown()
2024-11-01 12:17:00,577 INFO-|_______ ⏱️ Stopped TestMethod Timer and Calculated time taken for testcase
2024-11-01 12:17:00,577 INFO-|_______ ✅ Stored the testresult info into ExecutionTestCases.json
2024-11-01 12:17:00,579 INFO-|_______ 🎥❌Stopped Screen recording and based on testcase result: Pass(Delete Immediately for Storage Optimization) or Fail(Store it for defect)
2024-11-01 12:17:00,579 INFO-|------------------------------------------------------------------
2024-11-01 12:17:00,581 INFO-|------------------------------------------------------------------
2024-11-01 12:17:00,582 INFO-|_______ 🧪 [TestFixture][SetUp]Page1TestCases.cs/TestSetup()
2024-11-01 12:17:00,583 INFO-|_______ ⏱️ Started TestMethod Timer
2024-11-01 12:17:00,583 INFO-|_______ 🎥✅ Started Screen recording
2024-11-01 12:17:00,584 INFO-|____________ 🧪 [TestFixture][Test]Page1TestCases.cs/Test1()>CALLED Page1.Page1_Method2()
2024-11-01 12:17:00,584 INFO-|🎨Page1.cs>Page1_Method2()>USED Page1_Prop2:Page1Prop2Value
2024-11-01 12:17:00,587 INFO-|💽 Read from TestData/Page1Data/Page1Data.json and Printed 📈
2024-11-01 12:17:00,588 INFO-|_______ 🧪 [TestFixture][TearDown]Page1TestCases.cs/TestTearDown()
2024-11-01 12:17:00,589 INFO-|_______ ⏱️ Stopped TestMethod Timer and Calculated time taken for testcase
2024-11-01 12:17:00,589 INFO-|_______ ✅ Stored the testresult info into ExecutionTestCases.json
2024-11-01 12:17:00,589 INFO-|_______ 🎥❌Stopped Screen recording and based on testcase result: Pass(Delete Immediately for Storage Optimization) or Fail(Store it for defect)
2024-11-01 12:17:00,590 INFO-|------------------------------------------------------------------
2024-11-01 12:17:00,591 INFO-|_____ ⏱️ Stopped TestClass Timer and Calculated time taken for testclass
2024-11-01 12:17:00,591 INFO-|_____ 🧪 [TestFixture][OneTimeTearDown]Page1TestCases.cs/ClassTearDown()>DESTROYED Page1
2024-11-01 12:17:00,592 INFO-|_____✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨PAGE1 ENDS✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨
2024-11-01 12:17:00,593 INFO-|_____✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨PAGE2 STARTS✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨
2024-11-01 12:17:00,594 INFO-|	 🏭PageFactory with POM for Page2
2024-11-01 12:17:00,594 INFO-|_____ 🧪 [TestFixture][OneTimeSetUp]Page2TestCases.cs/ClassSetup()>INITIALIZED Page2
2024-11-01 12:17:00,595 INFO-|_____ ⏱️ Started TestClass Timer
2024-11-01 12:17:00,595 INFO-|------------------------------------------------------------------
2024-11-01 12:17:00,595 INFO-|_______ 🧪 [TestFixture][SetUp]Page2TestCases.cs/TestSetup()
2024-11-01 12:17:00,596 INFO-|_______ ⏱️ Started TestMethod Timer
2024-11-01 12:17:00,597 INFO-|_______ 🎥✅ Started Screen recording
2024-11-01 12:17:00,597 INFO-|____________ 🧪 [TestFixture][Test]Page2TestCases.cs/Test1()>CALLED Page2.Page2_Method1()
2024-11-01 12:17:00,598 INFO-|🎮Page2.cs>Page2_Method1()>USED Page2_Prop1:Page2Prop1Value
2024-11-01 12:17:00,598 INFO-|💾 Read from TestData/Page2Data/Page2Data.json and Printed 📉
2024-11-01 12:17:00,599 INFO-|_______ 🧪 [TestFixture][TearDown]Page2TestCases.cs/TestTearDown()
2024-11-01 12:17:00,599 INFO-|_______ ⏱️ Stopped TestMethod Timer and Calculated time taken for testcase
2024-11-01 12:17:00,599 INFO-|_______ ✅ Stored the testresult info into ExecutionTestCases.json
2024-11-01 12:17:00,600 INFO-|_______ 🎥❌ Stopped Screen recording and based on testcase result: Pass(Delete Immediately for Storage Optimization) or Fail(Store it for defect)
2024-11-01 12:17:00,601 INFO-|------------------------------------------------------------------
2024-11-01 12:17:00,601 INFO-|------------------------------------------------------------------
2024-11-01 12:17:00,601 INFO-|_______ 🧪 [TestFixture][SetUp]Page2TestCases.cs/TestSetup()
2024-11-01 12:17:00,602 INFO-|_______ ⏱️ Started TestMethod Timer
2024-11-01 12:17:00,602 INFO-|_______ 🎥✅ Started Screen recording
2024-11-01 12:17:00,602 INFO-|____________ 🧪 [TestFixture][Test]Page2TestCases.cs/Test1()>CALLED Page2.Page2_Method2()
2024-11-01 12:17:00,603 INFO-|🎨Page2.cs>Page2_Method2()>USED Page2_Prop2:Page2Prop2Value
2024-11-01 12:17:00,604 INFO-|💾 Read from TestData/Page2Data/Page2Data.json and Printed 📉
2024-11-01 12:17:00,604 INFO-|_______ 🧪 [TestFixture][TearDown]Page2TestCases.cs/TestTearDown()
2024-11-01 12:17:00,605 INFO-|_______ ⏱️ Stopped TestMethod Timer and Calculated time taken for testcase
2024-11-01 12:17:00,605 INFO-|_______ ✅ Stored the testresult info into ExecutionTestCases.json
2024-11-01 12:17:00,605 INFO-|_______ 🎥❌ Stopped Screen recording and based on testcase result: Pass(Delete Immediately for Storage Optimization) or Fail(Store it for defect)
2024-11-01 12:17:00,606 INFO-|------------------------------------------------------------------
2024-11-01 12:17:00,606 INFO-|_____ ⏱️ Stopped TestClass Timer and Calculated time taken for testclass
2024-11-01 12:17:00,606 INFO-|_____ 🧪 [TestFixture][OneTimeTearDown]Page2TestCases.cs/ClassTearDown()>DESTROYED Page2
2024-11-01 12:17:00,608 INFO-|_____✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨PAGE2 ENDS✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨
2024-11-01 12:17:00,608 INFO-|__[SetUpFixture]Web_Initializer.cs>Web_TearDown()
2024-11-01 12:17:00,608 INFO-|	📊Bulkpost/Published testresults from PublisedTestCasesStatus.json to Jira
2024-11-01 12:17:00,609 INFO-|	📊Bulkpost/Published testresults from PublisedTestCasesStatus.json to 🪝MS Teams
2024-11-01 12:17:00,609 INFO-|___ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ WEB ENDS 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 🖥️ 
2024-11-01 12:17:00,609 INFO-|_____________________________________________________________________________________________
2024-11-01 12:17:04,132 INFO-|_____________________________________________________________________________________________
2024-11-01 12:17:04,135 INFO-|___🧨🧨🧨🧨🧨🧨🧨🧨🧨🧨🧨🧨🧨🧨🧨🧨API STARTS🧨🧨🧨🧨🧨🧨🧨🧨🧨🧨🧨🧨🧨🧨🧨🧨
2024-11-01 12:17:04,136 INFO-|__[SetUpFixture]API_Initializer.cs>API_Setup()
2024-11-01 12:17:04,136 INFO-|__✅Created TestCycle
2024-11-01 12:17:04,136 INFO-|__✅Fetched TestCases
2024-11-01 12:17:04,137 INFO-|__🔗Linked fetched testcases to the created testcycle
2024-11-01 12:17:04,137 INFO-|_____✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨RESOURCE1 STARTS✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨
2024-11-01 12:17:04,138 INFO-|	 🏭ResourceFactory with ROM for Resource1
2024-11-01 12:17:04,138 INFO-|_____ 🧪 [TestFixture][OneTimeSetUp]Resource1TestCases.cs/ClassSetup()>INITIALIZED Resource1
2024-11-01 12:17:04,139 INFO-|_____ ⏱️ Started TestClass Timer
2024-11-01 12:17:04,140 INFO-|------------------------------------------------------------------
2024-11-01 12:17:04,140 INFO-|_______ 🧪 [TestFixture][SetUp]Resource1TestCases.cs/TestSetup()
2024-11-01 12:17:04,141 INFO-|_______ ⏱️ Started TestMethod Timer
2024-11-01 12:17:04,141 INFO-|_______ 🎥✅ Started Screen recording
2024-11-01 12:17:04,142 INFO-|____________ 🧪[TestFixture][Test]Resource1TestCases.cs/Test1()>CALLED Resource1.Resource1_Method1()
2024-11-01 12:17:04,142 INFO-|🎮Resource1.cs/Resource1_Method1()>USED Resource1_Prop1:Resource1Prop1Value
2024-11-01 12:17:04,146 INFO-|💽 Read from TestData/Resource1Data/Resource1Data.json and Printed 📈
2024-11-01 12:17:04,154 INFO-|_______ 🧪 [TestFixture][TearDown]Resource1TestCases.cs/TestTearDown()
2024-11-01 12:17:04,154 INFO-|_______ ⏱️ Stopped TestMethod Timer and Calculated time taken for testcase
2024-11-01 12:17:04,154 INFO-|_______ ✅ Stored the testresult info into ExecutionTestCases.json
2024-11-01 12:17:04,155 INFO-|_______ 🎥❌Stopped Screen recording and based on testcase result: Pass(Delete Immediately for Storage Optimization) or Fail(Store it for defect)
2024-11-01 12:17:04,155 INFO-|------------------------------------------------------------------
2024-11-01 12:17:04,157 INFO-|------------------------------------------------------------------
2024-11-01 12:17:04,158 INFO-|_______ 🧪 [TestFixture][SetUp]Resource1TestCases.cs/TestSetup()
2024-11-01 12:17:04,159 INFO-|_______ ⏱️ Started TestMethod Timer
2024-11-01 12:17:04,159 INFO-|_______ 🎥✅ Started Screen recording
2024-11-01 12:17:04,159 INFO-|____________ 🧪 [TestFixture][Test]Resource1TestCases.cs/Test1()>CALLED Resource1.Resource1_Method2()
2024-11-01 12:17:04,160 INFO-|🎨Resource1.cs>Resource1_Method2()>USED Resource1_Prop2:Resource1Prop2Value
2024-11-01 12:17:04,160 INFO-|💽 Read from TestData/Resource1Data/Resource1Data.json and Printed 📈
2024-11-01 12:17:04,161 INFO-|_______ 🧪 [TestFixture][TearDown]Resource1TestCases.cs/TestTearDown()
2024-11-01 12:17:04,161 INFO-|_______ ⏱️ Stopped TestMethod Timer and Calculated time taken for testcase
2024-11-01 12:17:04,164 INFO-|_______ ✅ Stored the testresult info into ExecutionTestCases.json
2024-11-01 12:17:04,164 INFO-|_______ 🎥❌Stopped Screen recording and based on testcase result: Pass(Delete Immediately for Storage Optimization) or Fail(Store it for defect)
2024-11-01 12:17:04,164 INFO-|------------------------------------------------------------------
2024-11-01 12:17:04,165 INFO-|_____ ⏱️ Stopped TestClass Timer and Calculated time taken for testclass
2024-11-01 12:17:04,165 INFO-|_____ 🧪 [TestFixture][OneTimeTearDown]Resource1TestCases.cs/ClassTearDown()>DESTROYED Resource1
2024-11-01 12:17:04,166 INFO-|_____✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨RESOURCE1 ENDS✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨
2024-11-01 12:17:04,167 INFO-|_____✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨RESOURCE2 STARTS✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨
2024-11-01 12:17:04,167 INFO-|	 🏭ResourceFactory with ROM for Resource2
2024-11-01 12:17:04,168 INFO-|_____ 🧪 [TestFixture][OneTimeSetUp]Resource2TestCases.cs/ClassSetup()>INITIALIZED Resource2
2024-11-01 12:17:04,169 INFO-|_____ ⏱️ Started TestClass Timer
2024-11-01 12:17:04,169 INFO-|------------------------------------------------------------------
2024-11-01 12:17:04,170 INFO-|_______ 🧪 [TestFixture][SetUp]Resource2TestCases.cs/TestSetup()
2024-11-01 12:17:04,170 INFO-|_______ ⏱️ Started TestMethod Timer
2024-11-01 12:17:04,170 INFO-|_______ 🎥✅ Started Screen recording
2024-11-01 12:17:04,171 INFO-|____________ 🧪[TestFixture][Test]Resource2TestCases.cs/Test1()>CALLED Resource2.Resource2_Method1()
2024-11-01 12:17:04,172 INFO-|🎮Resource2.cs/Resource2_Method1()>USED Resource2_Prop1:Resource2Prop1Value
2024-11-01 12:17:04,172 INFO-|💽 Read from TestData/Resource2Data/Resource2Data.json and Printed 📈
2024-11-01 12:17:04,173 INFO-|_______ 🧪 [TestFixture][TearDown]Resource2TestCases.cs/TestTearDown()
2024-11-01 12:17:04,173 INFO-|_______ ⏱️ Stopped TestMethod Timer and Calculated time taken for testcase
2024-11-01 12:17:04,173 INFO-|_______ ✅ Stored the testresult info into ExecutionTestCases.json
2024-11-01 12:17:04,173 INFO-|_______ 🎥❌Stopped Screen recording and based on testcase result: Pass(Delete Immediately for Storage Optimization) or Fail(Store it for defect)
2024-11-01 12:17:04,174 INFO-|------------------------------------------------------------------
2024-11-01 12:17:04,174 INFO-|------------------------------------------------------------------
2024-11-01 12:17:04,175 INFO-|_______ 🧪 [TestFixture][SetUp]Resource2TestCases.cs/TestSetup()
2024-11-01 12:17:04,175 INFO-|_______ ⏱️ Started TestMethod Timer
2024-11-01 12:17:04,176 INFO-|_______ 🎥✅ Started Screen recording
2024-11-01 12:17:04,176 INFO-|____________ 🧪 [TestFixture][Test]Resource2TestCases.cs/Test1()>CALLED Resource2.Resource2_Method2()
2024-11-01 12:17:04,176 INFO-|🎨Resource2.cs>Resource2_Method2()>USED Resource2_Prop2:Resource2Prop2Value
2024-11-01 12:17:04,177 INFO-|💽 Read from TestData/Resource2Data/Resource2Data.json and Printed 📈
2024-11-01 12:17:04,177 INFO-|_______ 🧪 [TestFixture][TearDown]Resource2TestCases.cs/TestTearDown()
2024-11-01 12:17:04,177 INFO-|_______ ⏱️ Stopped TestMethod Timer and Calculated time taken for testcase
2024-11-01 12:17:04,178 INFO-|_______ ✅ Stored the testresult info into ExecutionTestCases.json
2024-11-01 12:17:04,179 INFO-|_______ 🎥❌Stopped Screen recording and based on testcase result: Pass(Delete Immediately for Storage Optimization) or Fail(Store it for defect)
2024-11-01 12:17:04,179 INFO-|------------------------------------------------------------------
2024-11-01 12:17:04,179 INFO-|_____ ⏱️ Stopped TestClass Timer and Calculated time taken for testclass
2024-11-01 12:17:04,180 INFO-|_____ 🧪 [TestFixture][OneTimeTearDown]Resource2TestCases.cs/ClassTearDown()>DESTROYED Resource2
2024-11-01 12:17:04,180 INFO-|_____✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨RESOURCE2 ENDS✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨
2024-11-01 12:17:04,181 INFO-|__[SetUpFixture]API_Initializer.cs>API_TearDown()
2024-11-01 12:17:04,182 INFO-|__📊Bulkpost/Published testresults from PublisedTestCasesStatus.json to Jira
2024-11-01 12:17:04,182 INFO-|__📊Bulkpost/Published testresults from PublisedTestCasesStatus.json to 🪝MS Teams
2024-11-01 12:17:04,186 INFO-|___🧨🧨🧨🧨🧨🧨🧨🧨🧨🧨🧨🧨🧨🧨🧨🧨API ENDS🧨🧨🧨🧨🧨🧨🧨🧨🧨🧨🧨🧨🧨🧨🧨🧨
2024-11-01 12:17:04,186 INFO-|_____________________________________________________________________________________________
2024-11-01 12:17:06,131 INFO-|_____________________________________________________________________________________________
2024-11-01 12:17:06,134 INFO-|___📳📳📳📳📳📳📳📳📳📳📳📳📳📳📳📳MOBILE STARTS📳📳📳📳📳📳📳📳📳📳📳📳📳📳📳📳
2024-11-01 12:17:06,135 INFO-|__[SetUpFixture]Mobile_Initializer.cs>Mobile_Setup()
2024-11-01 12:17:06,135 INFO-|__✅Created TestCycle
2024-11-01 12:17:06,135 INFO-|__✅Fetched TestCases
2024-11-01 12:17:06,136 INFO-|__🔗Linked fetched testcases to the created testcycle
2024-11-01 12:17:06,136 INFO-|_____✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨SCREEN1 STARTS✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨
2024-11-01 12:17:06,137 INFO-|	 🏭ScreenFactory with SOM for Screen1
2024-11-01 12:17:06,137 INFO-|_____ 🧪 [TestFixture][OneTimeSetUp]Screen1TestCases.cs/ClassSetup()>INITIALIZED Screen1
2024-11-01 12:17:06,137 INFO-|_____ ⏱️ Started TestClass Timer
2024-11-01 12:17:06,139 INFO-|------------------------------------------------------------------
2024-11-01 12:17:06,140 INFO-|_______ 🧪 [TestFixture][SetUp]Screen1TestCases.cs/TestSetup()
2024-11-01 12:17:06,140 INFO-|_______ ⏱️ Started TestMethod Timer
2024-11-01 12:17:06,140 INFO-|_______ 🎥✅ Started Screen recording
2024-11-01 12:17:06,141 INFO-|____________ 🧪[TestFixture][Test]Screen1TestCases.cs/Test1()>CALLED Screen1.Screen1_Method1()
2024-11-01 12:17:06,142 INFO-|🎮Screen1.cs/Screen1_Method1()>USED Screen1_Prop1:Screen1Prop1Value
2024-11-01 12:17:06,145 INFO-|💽 Read from TestData/Screen1Data/Screen1Data.json and Printed 📈
2024-11-01 12:17:06,154 INFO-|_______ 🧪 [TestFixture][TearDown]Screen1TestCases.cs/TestTearDown()
2024-11-01 12:17:06,154 INFO-|_______ ⏱️ Stopped TestMethod Timer and Calculated time taken for testcase
2024-11-01 12:17:06,154 INFO-|_______ ✅ Stored the testresult info into ExecutionTestCases.json
2024-11-01 12:17:06,155 INFO-|_______ 🎥❌Stopped Screen recording and based on testcase result: Pass(Delete Immediately for Storage Optimization) or Fail(Store it for defect)
2024-11-01 12:17:06,155 INFO-|------------------------------------------------------------------
2024-11-01 12:17:06,156 INFO-|------------------------------------------------------------------
2024-11-01 12:17:06,158 INFO-|_______ 🧪 [TestFixture][SetUp]Screen1TestCases.cs/TestSetup()
2024-11-01 12:17:06,158 INFO-|_______ ⏱️ Started TestMethod Timer
2024-11-01 12:17:06,159 INFO-|_______ 🎥✅ Started Screen recording
2024-11-01 12:17:06,159 INFO-|____________ 🧪 [TestFixture][Test]Screen1TestCases.cs/Test1()>CALLED Screen1.Screen1_Method2()
2024-11-01 12:17:06,159 INFO-|🎨Screen1.cs>Screen1_Method2()>USED Screen1_Prop2:Screen1Prop2Value
2024-11-01 12:17:06,160 INFO-|💽 Read from TestData/Screen1Data/Screen1Data.json and Printed 📈
2024-11-01 12:17:06,160 INFO-|_______ 🧪 [TestFixture][TearDown]Screen1TestCases.cs/TestTearDown()
2024-11-01 12:17:06,160 INFO-|_______ ⏱️ Stopped TestMethod Timer and Calculated time taken for testcase
2024-11-01 12:17:06,163 INFO-|_______ ✅ Stored the testresult info into ExecutionTestCases.json
2024-11-01 12:17:06,163 INFO-|_______ 🎥❌Stopped Screen recording and based on testcase result: Pass(Delete Immediately for Storage Optimization) or Fail(Store it for defect)
2024-11-01 12:17:06,164 INFO-|------------------------------------------------------------------
2024-11-01 12:17:06,164 INFO-|_____ ⏱️ Stopped TestClass Timer and Calculated time taken for testclass
2024-11-01 12:17:06,165 INFO-|_____ 🧪 [TestFixture][OneTimeTearDown]Screen1TestCases.cs/ClassTearDown()>DESTROYED Screen1
2024-11-01 12:17:06,165 INFO-|_____✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨SCREEN1 ENDS✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨
2024-11-01 12:17:06,166 INFO-|_____✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨SCREEN2 STARTS✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨
2024-11-01 12:17:06,167 INFO-|	 🏭ScreenFactory with SOM for Screen2
2024-11-01 12:17:06,168 INFO-|_____ 🧪 [TestFixture][OneTimeSetUp]Screen2TestCases.cs/ClassSetup()>INITIALIZED Screen2
2024-11-01 12:17:06,168 INFO-|_____ ⏱️ Started TestClass Timer
2024-11-01 12:17:06,169 INFO-|------------------------------------------------------------------
2024-11-01 12:17:06,169 INFO-|_______ 🧪 [TestFixture][SetUp]Screen2TestCases.cs/TestSetup()
2024-11-01 12:17:06,169 INFO-|_______ ⏱️ Started TestMethod Timer
2024-11-01 12:17:06,170 INFO-|_______ 🎥✅ Started Screen recording
2024-11-01 12:17:06,170 INFO-|____________ 🧪[TestFixture][Test]Screen2TestCases.cs/Test1()>CALLED Screen2.Screen2_Method1()
2024-11-01 12:17:06,171 INFO-|🎮Screen2.cs/Screen2_Method1()>USED Screen2_Prop1:Screen2Prop1Value
2024-11-01 12:17:06,171 INFO-|💽 Read from TestData/Screen2Data/Screen2Data.json and Printed 📈
2024-11-01 12:17:06,172 INFO-|_______ 🧪 [TestFixture][TearDown]Screen2TestCases.cs/TestTearDown()
2024-11-01 12:17:06,172 INFO-|_______ ⏱️ Stopped TestMethod Timer and Calculated time taken for testcase
2024-11-01 12:17:06,173 INFO-|_______ ✅ Stored the testresult info into ExecutionTestCases.json
2024-11-01 12:17:06,173 INFO-|_______ 🎥❌Stopped Screen recording and based on testcase result: Pass(Delete Immediately for Storage Optimization) or Fail(Store it for defect)
2024-11-01 12:17:06,174 INFO-|------------------------------------------------------------------
2024-11-01 12:17:06,174 INFO-|------------------------------------------------------------------
2024-11-01 12:17:06,175 INFO-|_______ 🧪 [TestFixture][SetUp]Screen2TestCases.cs/TestSetup()
2024-11-01 12:17:06,175 INFO-|_______ ⏱️ Started TestMethod Timer
2024-11-01 12:17:06,176 INFO-|_______ 🎥✅ Started Screen recording
2024-11-01 12:17:06,176 INFO-|____________ 🧪 [TestFixture][Test]Screen2TestCases.cs/Test1()>CALLED Screen2.Screen2_Method2()
2024-11-01 12:17:06,176 INFO-|🎨Screen2.cs>Screen2_Method2()>USED Screen2_Prop2:Screen2Prop2Value
2024-11-01 12:17:06,177 INFO-|💽 Read from TestData/Screen2Data/Screen2Data.json and Printed 📈
2024-11-01 12:17:06,177 INFO-|_______ 🧪 [TestFixture][TearDown]Screen2TestCases.cs/TestTearDown()
2024-11-01 12:17:06,177 INFO-|_______ ⏱️ Stopped TestMethod Timer and Calculated time taken for testcase
2024-11-01 12:17:06,178 INFO-|_______ ✅ Stored the testresult info into ExecutionTestCases.json
2024-11-01 12:17:06,179 INFO-|_______ 🎥❌Stopped Screen recording and based on testcase result: Pass(Delete Immediately for Storage Optimization) or Fail(Store it for defect)
2024-11-01 12:17:06,179 INFO-|------------------------------------------------------------------
2024-11-01 12:17:06,179 INFO-|_____ ⏱️ Stopped TestClass Timer and Calculated time taken for testclass
2024-11-01 12:17:06,180 INFO-|_____ 🧪 [TestFixture][OneTimeTearDown]Screen2TestCases.cs/ClassTearDown()>DESTROYED Screen2
2024-11-01 12:17:06,180 INFO-|_____✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨SCREEN2 ENDS✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨
2024-11-01 12:17:06,181 INFO-|__[SetUpFixture]Mobile_Initializer.cs>Mobile_TearDown()
2024-11-01 12:17:06,182 INFO-|	📊Bulkpost/Published testresults from PublisedTestCasesStatus.json to Jira
2024-11-01 12:17:06,182 INFO-|	📊Bulkpost/Published testresults from PublisedTestCasesStatus.json to 🪝MS Teams
2024-11-01 12:17:06,182 INFO-|___📳📳📳📳📳📳📳📳📳📳📳📳📳📳📳📳MOBILE ENDS📳📳📳📳📳📳📳📳📳📳📳📳📳📳📳📳
2024-11-01 12:17:06,183 INFO-|_____________________________________________________________________________________________
```
Note: Go ahead with CSS selector ONLY 
![image](https://github.com/Rupesh253/EnterpriseGradeTestAutomationFramework/assets/18684949/f7508dee-73df-47fd-9cca-aeb8ee1315ce)

Appium 2.X.X:  
![image](https://github.com/Rupesh253/EnterpriseGradeTestAutomationFramework/assets/18684949/05cb57e6-509f-4c01-960a-32a24250b9ef)

Advanced Settings that you can play for optimization:  
```
{
  "ignoreUnimportantViews": false,
  "allowInvisibleElements": false,
  "elementResponseAttributes": "name,text",
  "snapshotMaxDepth": 70,
  "mjpegBilinearFiltering": false,
  "waitForSelectorTimeout": 10000,
  "serverPort": 6790,
  "simpleBoundsCalculation": false,
  "enableNotificationListener": true,
  "limitXPathContextScope": true,
  "includeExtrasInPageSource": false,
  "normalizeTagNames": false,
  "trackScrollEvents": true,
  "scrollAcknowledgmentTimeout": 200,
  "enableTopmostWindowFromActivePackage": false,
  "enableMultiWindows": false,
  "useResourcesForOrientationDetection": false,
  "shouldUseCompactResponses": true,
  "wakeLockTimeout": 86291856,
  "shutdownOnPowerDisconnect": true,
  "mjpegServerPort": 7810,
  "mjpegScalingFactor": 50,
  "disableIdLocatorAutocompletion": false,
  "enforceXPath1": false,
  "actionAcknowledgmentTimeout": 3000,
  "mjpegServerScreenshotQuality": 50,
  "keyInjectionDelay": 0,
  "waitForIdleTimeout": 10000,
  "mjpegServerFramerate": 10
}
```
![image](https://github.com/Rupesh253/EnterpriseGradeTestAutomationFramework/assets/18684949/a9bf5b9b-33da-4c7e-8b3b-35e4f2b43386)


```

