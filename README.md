# mock-folder
This is a test folder that you can use for mocking some applications that depend on things like File System communication, for example.

## Usage
This should be obvious. Clone the repository and optionally delete the .git folder as it contains a lot of weird files which are only understood by Git(maybe :laughing:).

```shell
[shrihan@shrihans-pc ~] $ git clone https://github.com/swag-lab/mock-folder.git <mock-folder> # change <mock-folder> to an actual directory name
[shrihan@shrihans-pc ~] $ cd <mock-folder> # change <mock-folder> to the cloned directory name
[shrihan@shrihans-pc ~] $ rm -rf .git # for windows, rmdir /s/q .git ; optional...
```