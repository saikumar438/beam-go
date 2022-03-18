# beam-go
# Saikumar Mylavarapu
### Download and Install
- Download and Install GO from [Download](https://go.dev/doc/install)


### Checking the Version
- After Downoad and Install, Check your GO version using the command  `go version`


### Get the SDK and the examples
- Apache Beam Go SDK is using the command `go get -u github.com/apache/beam/sdks/v2/go/pkg/beam`

### Install the wordcount example using the command 
- go install github.com/apache/beam/sdks/v2/go/examples/wordcount

### Run WordCount
- First we need to get the wordcound.go
- We can get it by using the command `go install github.com/apache/beam/sdks/v2/go/examples/wordcount` and create a input file sample.txt with some data.
- Now we need to run the word count using the command `go run wordcount.go --input sample.txt --output counts`
- Run the command `go run wordcount.go --input sample.txt --output mylavarapu_counts` 
- Now we can find the output in the file mylavarapu_counts