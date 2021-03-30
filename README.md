# simple go mod demo and calling module from another go code
# go-demo

# from hello dir
`go mod init github.com/gauravdevze/go-demo/hello`

# from greetings dir
`go mod init github.com/gauravdevze/go-demo/greetings`

# from hello directory

`go mod edit -replace=github.com/gauravdevze/go-demo/greetings=../greetings`

# from hello dir 

`go run .`
