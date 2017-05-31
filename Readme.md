![IMAGE](https://raw.github.com/ctava/linearregression-go/master/Data-regression.png)

0. Install Golang, git, setup `$GOPATH`, and `PATH=$PATH:$GOPATH/bin`
1. go gets
   ```
   go get github.com/gocarina/gocsv
   go get github.com/gonum/plot
   go get github.com/gonum/plot/plotter
   go get github.com/gonum/plot/plotutil
   go get github.com/gonum/plot/vg
   go get github.com/pkg/errors
   go get github.com/sajari/regression```
2. run the source
`go run main.go`


Notes:
This script predicts the amount of data that will be created based on fitting a sample data set to a linear regression model.

data-createdate.csv was created from relational database that simply has a date timestamp of when data was created. the creation of data is - in theory - in a linear relationship between the dates that data has been created and time.

