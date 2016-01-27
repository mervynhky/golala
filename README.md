# golala
Simple tutorials for beginners that are having a go with GoLang

### Why GOlang?
* Beaver looks cute. Reminds me of the Angry Beavers cartoon.

### Installation & Setup
* Download and install [Go](https://golang.org/dl/).
* Check `Environment Variables`. Once inside, under the `System Variables`, search for `Path` and ensure that `C:\GO\bin` is inside.
* Select a good IDE that can run GO. [Atom](https://atom.io/) text editor is good too.

## Atom
* Select `Install a Package`.
* Select `Open Installer`.
* Search for the `go-plus` package.
* Install.

##### Done? Let us create a new project!
* At the top left of the window, select `File` and then `Add Project Folder`, create or select a folder to store the GO files.
* Now, on the left there will be a column that displays the folder and its contents, with the folder name as the header.
* Again, at the top left, select "New File" and add a simple Hello World message.
```
package main

import "fmt"

func main(){
  fmt.Printf("Hello World\n")
}
```
* Now press the `CTRL+S` to save the file. Search for the `Go` folder directory and save the file as `HelloWorld.go`.
* It is important to specify the file as a `.go` type so that Atom recognises it as a `Go` file.
* Now open the `Command Prompt (CMD)` as an `Administrator`. Change the directory to where yo ustored the `Go` file.
* Now type this in the CMD. Use the `go run` command to run `Go` files. So type `go run HelloWorld.go` and it will then compile the file, then display the message `Hello, world`.

###### Notes
* The `fmt` library is basically an `input/output` library.
* `GoLang` doesn't use `semicolons`. Similar to `Python`, but `GoLang` utilises curly bracers like standard programming languages.
