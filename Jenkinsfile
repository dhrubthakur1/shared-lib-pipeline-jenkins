@Library(['first-shared-lib','shared-lib-pipeline']) _
//@Library('shared-lib-pipeline') _
welcomeJob.call()
welcomeJob.testFun('A')
//def conf = ['url':'https://github.com/dhrubthakur1/spring4-mvc-example.git', 'branch':'main', 'tomcatId':'tomcatadmin', 'tomcatUrl':'http://localhost:7070', 'contextPath':'spring7']
def conf = ['url':url, 'branch':'main', 'tomcatId':tomcatId, 'tomcatUrl':tomcatURL, 'contextPath':contextPath]
sharedPipeline.call(conf)
