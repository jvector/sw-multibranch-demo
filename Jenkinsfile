#!groovy
// Loads: https://gist.github.com/jglick/b13b509bc236566c8829
standardBuild {

    environment = 'golang:1.5.0'
	
    mainScript = '''

today = new java.util.Date()
println "Starting"
println today

go version
go build -v hello-world.go
'''

    postScript = '''
ls -l
./hello-world
'''

}
